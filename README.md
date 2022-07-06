# Basic-QnA

This is an AI that can answer questions asked by users.

Built in python, this AI can read data, remove stopwords and link all the important words in a set of documents. (using Term Frequency by Inverse Document Frequency)

Most importantly, it can take a query input from user and return the closest lines that answer the query.

Python Libraries Used :
- nltk - for tokenization of dataset
- math - for calculating the tf-idf values for each unique word
- sys & os - for iterating through the dataset dictionaries
- string - for data preprocessing (removing punctuations and nltk.corpus was used to remove stopwords in english)


