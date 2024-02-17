# Sentiment-Analysis

The provided Python code performs sentiment analysis on Twitter data using TextBlob and visualizes the sentiment distribution. Here's a concise summary of the code:

Import Libraries:

Pandas for data manipulation, TextBlob for sentiment analysis, and Matplotlib/Seaborn for visualization are imported.
Load Dataset:

The Twitter dataset is loaded from the specified path, and basic information about the dataset is displayed using df.info().
Sentiment Analysis using TextBlob:

Sentiment polarity is calculated for each tweet in the 'clean_text' column using TextBlob and added to the dataframe as 'Sentiment'.
Convert Sentiment Polarity to Labels:

Sentiment labels ('Positive', 'Negative', 'Neutral') are assigned based on the sentiment polarity values.
Data Visualization:

A pie chart is created to visualize the distribution of sentiments using Seaborn's countplot.
Save Dataset with Sentiment Analysis Results:

The dataset with sentiment analysis results can be saved to a CSV file (the line is commented out in the provided code).
In summary, this code demonstrates sentiment analysis on Twitter data using TextBlob and provides a visual representation of sentiment distribution. It is a simple yet effective way to understand the overall sentiment patterns in the given dataset.
