# Sentiment_Analysis
 Applying a sentimental analysis on the data provided by kaggle about the linkedIn app experience

This code snippet performs a comprehensive analysis of LinkedIn reviews data using Python libraries like pandas, matplotlib, seaborn, textblob, and wordcloud. Here's a detailed breakdown:

1.Imports: The code imports necessary libraries: pandas for data manipulation, matplotlib for plotting graphs, seaborn for statistical data visualization, textblob for sentiment analysis, and wordcloud for generating word clouds.

2.Load Data: It loads the LinkedIn reviews dataset from a CSV file named "linkedin-reviews.csv" into a pandas DataFrame called linkedin_data.

3.Initial Data Exploration:It prints the first few rows of the dataset to understand its structure.
Plots the distribution of ratings using seaborn's countplot.

4.Text Preprocessing:Calculates the length of each review and adds a new column 'Review Length' to the DataFrame.
Plots the distribution of review lengths using seaborn's histplot.

5.Sentiment Analysis: Utilizes TextBlob for sentiment analysis of the reviews.
Defines a function textblob_sentiment_analysis() that classifies reviews as Positive, Negative, or Neutral based on polarity scores.
Applies sentiment analysis to each review and adds a new column 'Sentiment' to the DataFrame.
Displays the first few rows with sentiment information.

6.Visualizing Sentiment Distribution: Calculates the distribution of sentiments (Positive, Negative, Neutral) in the dataset.
Plots the distribution of sentiments using seaborn's barplot.
Plots a count of sentiment distribution across different ratings using seaborn's countplot with the hue representing sentiment.

7.Word Cloud Generation: Defines a function generate_word_cloud() to generate a word cloud for each sentiment category.
Generates word clouds for each sentiment (Positive, Negative, Neutral) based on the reviews using the wordcloud library.
