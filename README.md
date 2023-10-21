IMDb Movie Review Sentiment Analysis

This project focuses on sentiment analysis of IMDb movie reviews to determine whether a review is positive or negative. IMDb is a popular platform for movie enthusiasts to express their opinions about movies, making it a valuable source of data for sentiment analysis.

Key Features

Data Exploration: Analyzed the IMDb movie review dataset to gain insights into the distribution of reviews. Explored the average, minimum, and maximum review lengths.

Word Cloud: Generated a word cloud to visually represent the most common words used in IMDb movie reviews after removing stop words.

Top 20 Most Frequent Words: Used a bar plot to display the top 20 most frequent words in IMDb reviews with stop words removed.

Topic Modeling with LDA: Employed Latent Dirichlet Allocation (LDA) for topic modeling to identify prevalent topics in movie reviews.

Data Distribution: Examined the data distribution of positive and negative reviews and visualized it using a bar plot.

Train-Test Split: Divided the dataset into a training set (80%) and a testing set (20%) to evaluate the model's performance.

Model Pipelines: Created model pipelines for both logistic regression and multinomial Naive Bayes to perform sentiment analysis.

SentimentIntensityAnalyzer: Utilized the NLTK SentimentIntensityAnalyzer to predict sentiment scores for movie reviews. The scores include positive, neutral, and negative scores.

Technologies Used:
Python
NLTK (Natural Language Toolkit)
Scikit-learn
WordCloud
Matplotlib
Latent Dirichlet Allocation (LDA)

This project aims to provide valuable insights into sentiment analysis of IMDb movie reviews, which can be useful for understanding audience opinions and preferences. Whether you're interested in data analysis or sentiment analysis, this project offers a comprehensive exploration of the IMDb dataset with various data visualization techniques and model building.

How to Use
Clone the repository to your local machine.
Run Jupyter notebooks to explore the data, perform sentiment analysis, and visualize results.
