# What Key Factors Shape Bank Account Access?

## Project Motivation
Based on economic data and bank account access data in the Global Findex Database 2021 from World Bank Databank, we try to analyze the effects of GDP per Capita, income, gender and education levels on bank account access, aiming at predicting bank account access rate and distinguish bank account access class. This exploration seeks to contribute to the development of sustainable policies that promote financial inclusion and reduce inequality, ensuring a more equitable and prosperous future for all.

## File Description
- A Descriptive Jupyter Notebook.
- `economic_data.csv`: economic indicators data downloaded from World Bank.
- `bank_account_access_data.xlsx`: bank account ownership data downloaded from Globa Findex Database 2021.
- `data.csv`: Combined economic data and bank ownership data for bank account access analysis and modeling.
- `requirements.txt`: libraries installed to run this notebook.
## Libraries Used
### The following libraries are required to run this program
- matplotlib==3.10.1 
- numpy==2.2.5 
- pandas==2.2.3 
- pandas_datareader==0.10.0 
- pycountry==24.6.1 
- scikit_learn==1.6.1 
- seaborn==0.13.2 
- shap==0.47.1 
- xgboost==3.0.0

To install the libraries, go to the terminal and run the following command: `pip install -r requirements.txt`

## Project Content
- [Business Understanding](#business-understanding)
- [Data Understanding](#data-understanding)
    - [Data collection & cleaning](#1-data-collection--cleaning)
    - [Exploratory Data Analysis](#2-exploratory-data-analysis)
- [Data Preparation](#Data-Preparation)
    - [Encode categorical variables](#encode-categorical-variables)
    - [Transform data](#Transform-data)
- [Modeling](#Modeling)
    - [Linear Regression](#linear-regression)
    - [Classification Models](#classification-models)
        - [Logistic Regression](#1-logistic-regression)
        - [Random Forest](#2-random-forest)
        - [XGBoost](#3-xgboost-model)
- [Evaluation](#evaluation)
## Results and Conclusions
- Results and discussion were **published on Medium: [What Key Factors Shape Bank Account Access?](https://medium.com/@wangcy0317/what-key-factors-shape-bank-account-access-dd94b6a4f6f2)**

- **Key findings:**
    1. Economy has significant impact on account access. However, living in a rich country does not mean you'll     automatically have a bank account. The bank account access is affected by multiple factors.
   
    2. The education gap and gender gap in bank account access can be narrowed by increasing income. In general, education level has a greater impact than gender on account access.
   
    3. Logistic regression classification model can effectively predict the account access class based on income, education gap and gender gap. This can be helpful for policy decisions and interventions that can enhance access to banking services for all, particularly focusing on vulnerable groups such as low-income individuals and females in specific regions.

## Licensing, Authors, Acknowledgements
- This is my first project for Udacity Data Scientist Nanodegree Program.
- Acknowledgement should go to [World Bank Databank](https://databank.worldbank.org/) for the collection of datasets.
- Acknowledgement should also go to the mentors from Udacity for knowledge transfer and technical assistance. 
