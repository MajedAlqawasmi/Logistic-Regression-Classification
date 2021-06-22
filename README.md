# A_Beautiful_Repo

# Ironhack Project - Binary classification with Logistic regression 🏦 💳
by [Majed Alqawasmi](https://github.com/MajedAlqawasmi) June 2021
<br/><br/>
## Prediciting loan risk classifiction for each customer 

![Classification Case Study](Presentation_Material/EQS-Blog_Compliance-Risk-Assessment-1-1024x576.jpg)

## Table of content

- [Lesson](https://github.com/lillaszulyovszky/ironhack-case-study-classification/blob/main/README.md#Lesson)
- [Data](https://github.com/lillaszulyovszky/ironhack-case-study-classification/blob/main/README.md#data)
- [Process & Tools](https://github.com/lillaszulyovszky/ironhack-case-study-classification#process--tools)
- [Visualization](https://github.com/lillaszulyovszky/ironhack-case-study-classification#visualizations)
- [Key Take Aways](https://github.com/lillaszulyovszky/ironhack-case-study-classification#key-take-aways)

## Lesson
Machine learning example to predict loan risk status of customers based on bank data set we have.

## Data

We used a set of data referring a Bank in the Czech Republic.

## Process & Tools

**Process**
Our ways of working included an iterative/agile approach circling through the following steps:

![workflow](https://github.com/lillaszulyovszky/ironhack-case-study-classification/blob/main/images/presentation/workflow.png?raw=true")
- **Github:** set up our Github repo to collaborate on. We did 104 commits in 4 days. <br/>
- **SQL:** started with the independent task of completing the SQL queries<br/>
- **EDA:** assessment of dataframe to prepare for cleaning<br/>
- **Data cleaning & wrangling in Python:** drop 'customer_number' column, drop null values, convert float columns to int<br/>
- **Prepocessing:** 3 methods - Normalizer, Dummies and SMOTE<br/>
- **Machine Learning Model:** using scikit learn<br/>
**- iteration 1 (X):** In our first iteration we only used preprocessing and encoding and used this as a benchmark for the following iterations as comparison<br/>
**- iteration 2 (X_i2):** SMOTE sampling to improve the imbalance of the target<br/>
**- iteration 3 (X_i3):** dropping quarterly balance columns to reduce noise<br/>
**- iteration 4 (X_i4):** encoding numerical features to categorical ones<br/>

**Tools**
 - **Jupyter [notebook](https://github.com/MajedAlqawasmi/A_Beautiful_Repo/blob/main/Logistic_regression_bank_outline.ipynb)
 - **Database:** MyWorkbench - [Link to SQL folder](https://github.com/lillaszulyovszky/ironhack-case-study-classification/tree/main/sql)
 - **Vizualizations:** seaborn / matplotlib

## Visualizations

For further visualisations please do check out the [notebook](https://github.com/MajedAlqawasmi/A_Beautiful_Repo/blob/main/Logistic_regression_bank_outline.ipynb)

## Key Take Aways

### 78% have accepable risk status whn it comes to lending, with a low false positive & false nagative rates.
