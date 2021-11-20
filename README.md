# Topic_Modelling
LDA based Topic Modelling for categorizing Customer Complaints
1. Problem Statement:

For a company, analyzing customer complaints is the best way to know how its products or services are performing. Often times companies use narrowly defined set of rules to categorise complaints but in reality the complaints data submitted by customers / consumers depicts another story. When consumers log a complaint, they are unaware of the business terminologies that the companies uses to categorise a complaint. In a hurry consumers pick a category that seems close to the options provided or they pick a group defined as others. Most of the complaints are categorised wrongly. This wrong classification results in routing complaints to wrong groups to resolve the complaints. The wrong classification also leads to a longer waiting time and incomplete resolution of complaints leading to customer dissatisfaction.  Indirectly it hits the bottom line of a company.

1.1. About the problem:

The problem is an unsupervised learning problem. Hence, we can use LDA to reclassify customer complaints based on the exact language used in the complaints. TF-IDF algorithm can help us find words with more weightage. Combining TF-IDF and LDA algorithms we could find NLP recommended word themes. Our goal is to find the root causes of complaints quicker and label the categories accuratley. This can help route the complaints to the right group for quicker resolution.

To improve the accuracy, we aim to build a customised knowledge graph for all the complaints using cosine similarity metric.

Dataset Description:**
The dataset comprises of Consumer Complaints on Financial Products.

Each week the CFPB sends thousands of consumers’ complaints about financial products and services to companies for response. Those complaints are published here after the company responds. By adding their voice consumers help improve the finanacial market place.

The dataset has complaints belonging to categories such as

Debt collection,
Consumer loan,
Mortgage,
Credit card,
Credit reporting,
Student loan,
Bank account or service,
Payday loan,
Money transfers, and
other financial products.
There are five steps to submit a complaint:

Step 1: What is this complaint about?

Step 2: What type of problem are you having?

Step 3: What happened?

Step 4: What company is this complaint about?

Step 5: Who are the people involved?

Our data set has information about the above five questions. The data set also has information about dates, amounts, and other details about the complaint such as billing statements or letters from the company.

The dataset is available in the link https://www.kaggle.com/cfpb/us-consumer-finance-complaints
