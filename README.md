# Online-Marketing-Machine-Learning

Objective of this case study is to explore Online Lead Conversion for a Life Insurance company. Some people are interested in buying insurance products from this company hence they visit the site of this Life Insurance Company and fill out a survey asking about attributes like income, age etc. These people are then followed and some of them become customers from leads. Company have all the past data of who became customers from lead. Idea is to learn something from this data and when

some new lead comes, assign a propensity of him/her converting to a customer based on attributes asked in the survey. This sort of problem is called as Predictive Modelling

Concept:

Predictive modelling is being used by companies and individuals all over the world to extract value from historical data. These are the mathematical algorithms, which are used to "learn" the patterns hidden on all this data. The term supervised learning or classification is also used which means you have past cases tagged or classified (Converted to Customer or Not) and you want to use this learning on new data. (machine learning)

Here are the attributes of the survey

Attribute

age

Job

marital

education

smoker

monthlyincome

houseowner

loan

contact

mod

monthlyhouseholdincome

target_buy

Description

Age of the Lead

Job Category e.g. Management

Marital Status

Education of Lead

Is Lead smoker or not (Binary – Yes / No)

Monthly Income

Is home owner or not (Binary – Yes / No)

Is having loan or not (Binary – Yes / No)

Contact type e.g. Cellphone

Days elapsed since survey was filled

Monthly Income of all family members

altogether

Is converted to customer or not (Binary –Yes

/No). This is known as Target or Response

and this is what we are modelling.
Handle the missing data and perform necessary data pre-processing.


Summarise the data.
Perform Chi-Square test to find correlation between target variable and independent variables. (lower the p value more its related).
Plot graph using seaborn and matplotlib for significant predictors against target variable.
After feature selection, train using prediction model.
For a new lead, predict if it will convert to a successful lead or not.
Use different classification techniques and compare accuracy score and also plot them in a bar graph.
