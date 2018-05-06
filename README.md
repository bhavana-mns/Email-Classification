# Email-Classification
To classify emails into different categories, build different models, and compare them

Data Set - Enron Email Dataset

The emails are classified into the following categories:

1.Company Business, Strategy

2.Purely Personal

3.Personal but in professional context (e.g., it was good working with you)

4.Logistic Arrangements (meeting scheduling,technical support)             

5.Employment arrangements (job seeking, hiring, recommendations etc)

6.Document editing/checking (collaboration)

7.Empty message (due to missing attachment)

8.Empty message

The data is initially preprocessed, and all attributes are added to the corresponding columns, and a CSV file is created. The features are extracted using TFIDF(Term Frequency-Inverse Document Frequency). To obtain a vector representation , Latent Semantic Analysis(LSA) is performed. Stop words are removed, and all classes are balanced. 

The models built are:
KNN

SVM

Naive Bayes

Logistic Regression

A confusion matrix is built to compare all models
