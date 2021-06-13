# Week-9-IP---KNN-and-Naive-Bayes
1. Defining the Question -
2. 
3.   
4.   
TITANIC DATASET 



a) Specifying the Question
Specifying the Data Analytic Question Using Titanic data implement KNN classifier to create a model that would accurately classify whether a passenger would survive or not, given the different feaures from the data

b) Defining the Metric for Success
Randomly partition each dataset into two parts i.e 80 - 20 sets.

For dataset 1, because we don't have the label for the test set, we will use the train set to create train and test data (i.e. splitting further), then perform K-nearest neighbor classification.

For dataset 2, perform classification of the testing set samples using the Naive Bayes Classifier.

Compute the accuracy (percentage of correct classification).

Report the confusion matrix of each classifier.

Repeat step 2 to step 4 twice, each time splitting the datasets differently i.e. 70-30, 60-40, then note the outcomes of your modeling.

Suggest and apply at least one of the optimization techniques that you learned earlier this week.

c) Understanding the context
Titanic was a passenger ship that sank in North Atlantic ocean in 1912 after striking an iceberg. It is reported that majority of the passengers died while a few of them survived. As a Data Scientist, use the Titanic data to implement KNN classification by creating a model that would classify whether or not a passenger survived. Here is a description of the columns provided:

Survival — Survival 0 = No, 1 = Yes

Pclas — Ticket class: 1 = 1st, 2 = 2nd, 3 = 3rd

Sex — Male or Female

Age — Age in years

Sibsp — the number of siblings and spouses travelling with the passenger

Parch — the number of parents and children travelling with the passenger

Ticket — Ticket number

Fare — Passenger fare

Cabin — Cabin number

Embarked — Port of Embarkation: C = Cherbourg, Q = Queenstown, S = Southampton

d) Recording the Experimental Design
Reading and previewing the dataset

Data validation

Tidying up the data

EDA

Model perfomance optimization

Implementing the solution

Conclusion and challenging the solution


1. Defining the Question - 

SPAM DATASET 
a) Specifying the Question
This week's project requires us to implement a Naive Bayes classifier on the provided dataset in order to classify an e-mail as spam or not.

b) Defining the Metric for Success
The metric for success will be the accuracy score for each model. A model with an accuracy of above 80% will be considered a good model.

We'll also use a confusion matrix for each of the models to evaluate it's performance. A model with a low number of false negatives and false positives will be considered a good model as this means that most of the positive and negative examples are correctly recognized

c) Understanding the context
Spamming is the use of messaging systems to send an unsolicited message (spam) to large numbers of recipients for the purpose of commercial advertising, for the purpose of non-commercial proselytizing, or for any prohibited purpose (especially the fraudulent purpose of phishing). While the most widely recognized form of spam is email spam, the term is applied to similar abuses in other media: instant messaging spam, Usenet newsgroup spam, Web search engine spam, spam in blogs, wiki spam, online classified ads spam, mobile phone messaging spam, Internet forum spam, junk fax transmissions, social spam, spam mobile apps television advertising and file sharing spam.

The "spam" concept is diverse: advertisements for products/web sites, make money fast schemes, chain letters etc.

In this project we'll be dealing with e-mail spam, also referred to as junk email, which is unsolicited messages sent in bulk by e-mail (spamming).

d) Recording the Experimental Design
The following are the steps taken to implement the solution :

Define the question, the metric for success, the context, experimental design taken. Read and explore the given dataset. Define the appropriateness of the available data to answer the given question. Find and deal with outliers, anomalies, and missing data within the dataset. Perform exploratory analysis recording our observations. Build a baseline model to use as a benchmark for our model Build a Naive Bayes Classifier Model using an 80-20 split as train and test respectively Repeat the above step twice using 70-30 split and 60-40 split. Optimize the model for better performance Challenge our solution and give recommendations as to how we could improve the model performance.

e) Data Relevance
The collection of spam e-mails in this dataset came from the postmaster and individuals who had filed spam.

The Spambase data set was created by Mark Hopkins, Erik Reeber, George Forman, and Jaap Suermondt at Hewlett-Packard Labs. It includes 4601 observations corresponding to email messages, 1813 of which are spam. From the original email messages, 58 different attributes were computed.

We therefnore can conclude that our dataset is very relevant to answer the given question
