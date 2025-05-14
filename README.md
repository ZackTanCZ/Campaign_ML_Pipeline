# Data Mining Project
Ever wondered about how a data mining project is formulated and executed , leading to the delivery of hidden and valuable insights which provided you with an 'aha' moment and equipped you with knowledge to make more well-informed decision? There are some frameworks to guide a data mining project, a prime example being **Cr**oss **I**ndustry **S**tandard **P**rocess for **D**ata **M**ining(CRISP-DM). It can be simplifed into the following structure:  

`
Data Ingestion --> Data Processing --> Exploratory Data Analysis --> Data Modeling --> Model evaluation --> Deployment
`

In an large scale project, this structure is broken down into several components and delegated to their respective specialist to be maintained and optimised.  
* Data Engineer -> Data Ingestion, Data Processing and Deployment
* Data Analyst -> Exploratory Data Analysis
* Data Scientist -> Data Modeling, Model evaluation

Often, each area of expertise will work in tandem to ensure a successful project. For example, data analyst may share their finding from the dataset and the data engineer sets out to engineer new features to augment the dataset with more predicitive power. With that being said, responsibilties may overlap in smaller scale projects such as an data analyst managing the data pipeline and deriving insights.

## Data Processing
Data processing is an critical process to ensure the integerity of our data. This adheres to the Computer Science paradign of 'Garbage In, Garbage Out', feeding unsanitized input to model will likely result in unusable output or invalid analysis.

## Exploratory Data Analysis
Exploratory Data Analysis (EDA) is considered an pivotal aspect of the data mining project, it provides a technical understanding of the dataset and unraveals valuable insights hidden within the data. These insights can help empower decision makers to make well-informed decisions and develop better performing predictive models

## Assignment
In this project, we will perform EDA on a dataset to develop an understanding of the dataset and derive some insights to drive decision making.

## Data Cleaning Strategy/Framework - C.L.E.A.N
### Conceptualise
Consider the following:  
* What story is the data telling me?
* What is the target variable?
* what are the important predictor variables?
  
### Locate solvable problems
* Identify but do not change any abnormalities observed
  * Nulls, duplicates, format inconsistency, inconsistent categories 
* log down any abnormalities observed
* Decide if they can be resolved without business domain or stakeholder knowledge
* Avoid replacing values in-place for solvable problems
  
### Evaluate unsolvable problems
*

### Augment the data

### Note and Document
