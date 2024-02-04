# LifeExpectancyPredictor
## 1. What is the nature of dataset?
### The nature of dataset is completely numerical based. It consists of multiple columns which predict life expectancy of a person living in a specific country.

## 2. What are the features?
### Country - Displays the country name
### Year - Displays the year
### Status - It displays whether the country is developed or not.
### Life Expectancy - Life expectancy in age.
### Adult Mortality - Adult Mortality of both genders (probability of dying between 15 and 60 years per 1000 population).
### Infant Death - Number of Infant Deaths per 1000 population].
### Alcohol - Consumption of alcohol recorded per capita in liters.
### percentage_expentiture - Expenditure on health as a percentage of GDP
### Hepatitis B - Immunization coverage among 1 year old.
### Measles - Number of cases per 1000 population

## 3. How did we approach the problem?
### Here are the steps which I followed:
### 1. Data Preprocessing:
#### a. Checked all the columns which consist of null values
#### b. Filled the null values with mean. (This has lead to outliers so I removed them furthur.)
### 2. EDA:
#### a. Did an extensive EDA with all the columns
#### b. Also used boxplot for finding the outliers and then removed them by IQR.
### 3. Feature Engineering:
#### Converted all the categorical features and encoded them.
### 3. Modeling:
#### a. Used Artifical Neural Network. 
#### b. Made 2 hidden layers
#### c. Also used early stopping to avoid overfitting
#### d. Model predicted with r2 score of 0.84.
