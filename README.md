# Text-Features-Extraction-using-NLP

This is a text classification project where one needs to classify news articles into different categories based on their content. We have a dataset of news articles and their corresponding categories.
Dataset name: reuters_bag_of_words.csv

STEPS FOLLOWED IN THE PROJECT:

1.	Loaded the news articles dataset into a Pandas dataframe. dataset name: retuers_bag_of_words
2.	Preprocessed the text by removing stop words, converting all text to lowercase, and removing special characters.
3.	Used counter vectorization to convert the preprocessed text into a matrix of token counts.
4.	Calculated the TF-IDF (Term Frequency-Inverse Document Frequency) score for each word in the dataset using Scikit-learn.
5.	Converted the TF-IDF scores into a Pandas dataframe and display the top 10 words with the highest scores.
6.	Saved the TF-IDF dataframe to a CSV file called tfidf.csv for further data analysis in future. 
