# What Key Factors Shape Bank Account Access?

## Project Motivation
Based on economic data and bank account access data in the Global Findex Database 2021 from World Bank Databank, we try to analyze the effects of GDP per Capita, income, gender and education levels on bank account access, aiming at predicting bank account access rate and distinguish bank account access class. This exploration seeks to contribute to the development of sustainable policies that promote financial inclusion and reduce inequality, ensuring a more equitable and prosperous future for all.

## File Description
- A Descriptive Jupyter Notebook.
- A dataset: Detailed Listings data for bank account access analysis.

## Project Content
- [Questions and Goals](#questions-and-goals)
- [Data Collection](#data-collection)
- [Explorary Data Analysis (EDA)](#eda)
- [Data Preprocessing](#data-preprocessing)
- [Data Modeling and Model Evaluation](#data-modeling-and-model-evaluation)
    - [Linear Regression](#linear-regression)
    - [Classification](#classification)
        - [Logistic Regression](#1-logistic-regression)
        - [Random Forest](#2-random-forest)
        - [XGBoost](#3-xgboost-model)
        - [Comparison of Different Models](#4-comparison-of-different-models)
## Results and Conclusions
Results and discussion were **published on Medium: What Key Factors Shape Bank Account Access?**
**Key findings:**
1. Economy has significant impact on account access. However, living in a rich country does not mean you'll automatically have a bank account. The account access is affected by multiple factors.
   
2. The education gap and gender gap in bank account access can be narrowed by increasing income. In general, education level has a greater impact than gender on account access.
   
3. Logistic regression classification model can effectively predict the account access class based on income, education gap and gender gap. This can be helpful for policy decisions and interventions that can enhance access to banking services for all, particularly focusing on vulnerable groups such as low-income individuals and females in specific regions.

## Licensing, Authors, Acknowledgements
- This is my first project for Udacity Data Scientist Nanodegree Program.
- Acknowledgement should go to [World Bank Databank](https://databank.worldbank.org/) for the collection of datasets.
- Acknowledgement should also go to the mentors from Udacity for knowledge transfer and technical assistance. 
