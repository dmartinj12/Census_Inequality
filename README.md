## George Washington University Data Analytics Bootcamp

## Final Group Project 

# Census Inequality - Analyzing and Modeling Census Income

![alt text](Visualizations/IncomeBy.jpg)

##  Objective

Create machine learning models utilizing the Census Income dataset to predict the outcome of personal income is either greater than $50K or not based on the features in the dataset.

## Data

For our analysis, we used the following dataset:

[Adult Census Income](https://www.kaggle.com/datasets/lovishbansal123/adult-census-income)

The Adult Census Income dataset is a rich resource for understanding the socio-economic factors that influence income levels. It contains demographic and employment information from the U.S. Census Bureau, including age, work class, education level, marital status, occupation, relationship, race, gender, hours per week worked, and native country. The dataset also includes an ‘income’ column, indicating whether the individual’s income exceeds 50K per year. This dataset is often used for classification tasks in machine learning, where the goal is to predict whether an individual’s income exceeds 50K based on the other attributes. Please note that all personal data in this dataset has been anonymized to protect privacy.



## Approach

## Data Preprocessing

Before running our models, the data was cleansed:

* Jupyter Notebook Preprocessing Analysis - [PreprocessingAnalysis.ipynb](Code/PreprocessingAnalysis.ipynb)

Chris/DT_Model.ipynb
* Analyzed the following dataset features and target:
    * age
    * workclass
    * fnlwgt
    * education
    * education_num
    * marital_status
    * occupation
    * relationship
    * race
    * sex
    * capital_gain
    * capital_loss
    * hours_per_week
    * native_country
    * `income` (Target Outcome)

* The following features were dropped:
    * education - redundant string value that education_num was better in representing
    * capital_gain - > 90% were 0
    * capital_loss - > 90% were 0
    * native_country - > 90% were U.S. 

## Machine Learning Models

In Python, we utilized the following machine learning models to analyze the Adult Census Income dataset:
 
* K Nearest Neighbor - [PredictiveDawson.ipynb](Code/PredictiveDawson.ipynb)
* Decision Tree - [DT_Model.ipynb](Code/DT_Model.ipynb)
* Random Forest - [RandomForest.ipynb](Code/RandomForest.ipynb)
* Gradient Boosting - [GradientBoosting.ipynb](Code/GradientBoosting.ipynb)
* Logistic Regression - [LogisticRegression.ipynb](Code/LogisticRegression.ipynb)
* Neural Network - [NeuralNetwork.ipynb](Code/NeuralNetwork.ipynb)
* Principal Component Analysis - [PCA.ipynb](Code/pca.ipynb)

## Visualizations

The model prediction results, python visualizations were generated and then were posted to a tableau dashboard.

### [Link to website](https://public.tableau.com/app/profile/dawson.martin.jones/viz/Census_Predicting/CensusPredicting?publish=yes)

## Team Members
* Dawson Martin-Jones
* Daniel Montano
* Gboyega Adega
* Christopher Purcell
