# NLP_project

# Abstract
This project aims to develop a Natural Language Processing (NLP) model
to detect fake news and genuine news. The dataset used in the project
includes two CSV files, one containing fake news and the other containing
genuine news. The project includes data pre-processing steps such as
tokenization, stemming, and stop word removal. The preprocessed data is
split into training and testing sets. The TFIDF vectorization technique is
used to convert the text data into numerical form. Two machine learning
models, Logistic Regression, and Passive Aggressive Classifier, are used
to build the classification model. The accuracy of the models is evaluated
using the accuracy score metric from the scikit-learn library. The model can
help identify fake news, which can be used to counter the spread of
misinformation.
# OBJECTIVE
The objective of this project is to develop a natural language
processing model using Python that can accurately detect whether a
news article is fake or genuine. The model will be trained on a dataset
consisting of two sets of news articles: one containing fake news
articles and the other containing genuine news articles. The model
will pre-process the data by removing stop words, stemming the
words, and vectorising the text using the TF-IDF method. Finally, the
model will use two machine learning algorithms (Logistic Regression
and Passive Aggressive Classifier) to classify the news articles as
fake or genuine, and evaluate its accuracy using the test dataset.
# INTRODUCTION
In today's world, the spread of fake news is a major concern. With the
widespread use of social media platforms, anyone can share
information without verifying its authenticity. Fake news can cause
significant harm to individuals, organizations, and society as a whole.
Therefore, the detection of fake news is of utmost importance. In this
project, we aim to use Natural Language Processing (NLP) techniques
to distinguish between fake and genuine news articles. We use the
Python programming language and the NLTK library to pre-process
the data, including tokenization, stemming, and stop word removal.
We use a dataset consisting of two CSV files containing real and fake
news articles. We merge these datasets, pre-process them, and split
them into training and testing sets. We use the TF-IDF vectorization
technique to convert the text data into a numerical format suitable for
machine learning algorithms. We then build two machine learning
models, namely Logistic Regression and Passive-Aggressive
Classifier, to classify news articles as fake or genuine. Finally, we
evaluate the accuracy of the models and choose the one with better
performance. The proposed system can be used to automatically
identify fake news articles, which can help prevent their spread and
reduce the impact of false information on individuals and society.

# METHODOLOGY
The methodology for the project of natural language processing to
distinguish fake news and genuine news involves the following steps:
1. Data Collection :
    The first step is to collect the data in the form of
    fake news and genuine news articles. For this project, we have used
    two datasets: Fake.csv and True.csv.
2. Data Pre-processing: In this step, we have performed various pre-processing steps to clean and
    prepare the data for analysis. This includes tokenization, stemming,
    stop words removal, and concatenation of the fake and genuine news
    articles.
   
4. Data Splitting: The next step is to split the dataset into
    training and testing sets. We have used a 75:25 split ratio for this
    project.
5. Vectorization: We have used the TF-IDF vectorization technique to convert the text data into numerical form, which can be
    used for analysis by machine learning algorithms.
6. Building of ML Models: We have used two machine learning algorithms - Logistic
    Regression and Passive Aggressive Classifier - to build models for
    distinguishing fake news from genuine news.
7. Model Evaluation: Finally, we have evaluated the performance of both models using
    accuracy score as the evaluation metric. The output of the code
    includes the accuracy scores for both models. The Logistic
    Regression model achieved an accuracy of 98.9%, while the Passive
    Aggressive Classifier achieved an accuracy of 99.5%. These results
    indicate that both models are effective in distinguishing fake news
    from genuine news.
   
    

# CONCLUSION
In conclusion, natural language processing (NLP) techniques have been
utilized to develop a model to distinguish between fake and genuine news
articles. The project involved data pre-processing steps such as
tokenization, stemming, and stop word removal. The dataset was split into
training and testing sets, and Tfidf Vectorizer was used for vectorization.
Two machine learning models, Logistic Regression and Passive
Aggressive Classifier, were trained and evaluated based on their accuracy
score. The model achieved a high accuracy score, indicating that NLP
techniques can effectively detect fake news. Further improvements can be
made by incorporating more advanced NLP techniques and increasing the
size of the dataset. Overall, this project demonstrates the potential of NLP
in the field of journalism and information integrity.


