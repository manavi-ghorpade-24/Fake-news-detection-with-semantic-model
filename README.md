# Fake-news-detection-with-semantic-model

The goal of this project is to propose a model to identify the fake news prediction. In this
project, we built a classify model to recognize the fake news based on the title and text by using
machine learning, semantics and natural language processing. The proposed system contains a
Vectorization for finding the relationship between the words and with the obtained information
of the existing relations, the articles are categorized into fake and real news

In this project we are using the dataset which has text data in it. So first of all we are
going to use natural language processing using the TfidfVectorizer to convert the data into a
usable vector (in the form of numerical values). This combines 2 concepts: Term Frequency (TF)
and the Document Frequency (DF). It checks for the count of the word by how often the word
appears in the document.
Then, we will split the data into training and testing data. After this, we are going to use
some Sklearn algorithms to check for the maximum accuracy we get from the testing data. So the
algorithms that we are going to use are: Passive Aggressive Classifier (PAC), Gradient Boost
Classifier (GB), Logistic Regression Classifier (LR), and Support Vector Classifier (SVC).
And lastly, we will calculate the accuracy score, the performance matrix, and the
classification report for every prediction model. The model with the maximum accuracy will be
known.

