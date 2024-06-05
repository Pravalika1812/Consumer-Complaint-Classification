# Consumer-Complaint-Classification

In this project, we developed a Natural Language Processing (NLP) system to automate
the classification of consumer complaints in the
financial sector. We applied several machine
learning models—Multinomial Naive Bayes,
Random Forest, Decision Tree, Gradient Boost,
XGBoost, and KNN—along with the advanced
NLP model BERT (Bidirectional Encoder Representations from Transformers), aiming to improve the efficiency of complaint resolution processes. Using data from the Consumer Financial Protection Bureau, we performed extensive
preprocessing to prepare for effective model
training. Each model was evaluated on metrics such as accuracy, precision, recall, and F1-
score. XGBoost showed the best overall performance, while BERT excelled in handling complex textual content, and KNN demonstrated
high precision but faced challenges in model
generalization. This project highlights the utility of NLP and machine learning in streamlining complaint management in the financial
sector, which could lead to quicker resolutions
and enhanced customer satisfaction.

For this project, we utilized a real-time dataset obtained from the Consumer Financial Bureau, an official website of the United States Government.
The dataset spans a decade of consumer submissions, ranging from December 2011 to February 2024, comprises 4,858,723 rows and 18 columns, 
including features such as Date received, Product, Sub-product, Issue, Sub-issue, Consumer colaint narrative, Company public response, Company, State, ZIP code, Tags, Consumer consent
provided?, Submitted via, Date sent to company,Company response to consumer, Timely response,Consumer disputed, and Complaint id.
The relevant features that we are considering for the classification are Product, Sub-product and Consumercomplaint narrative.

We took the data from the website : https://www.consumerfinance.gov/data-research/consumer-complaints/
