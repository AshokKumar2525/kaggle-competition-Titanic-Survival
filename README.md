<h2>:ship:Titanic Passanger Survival Analysis</h2>


```python
from IPython.display import Image
Image(url= "https://static1.squarespace.com/static/5006453fe4b09ef2252ba068/5095eabce4b06cb305058603/5095eabce4b02d37bef4c24c/1352002236895/100_anniversary_titanic_sinking_by_esai8mellows-d4xbme8.jpg")
```




<img src="https://static1.squarespace.com/static/5006453fe4b09ef2252ba068/5095eabce4b06cb305058603/5095eabce4b02d37bef4c24c/1352002236895/100_anniversary_titanic_sinking_by_esai8mellows-d4xbme8.jpg"/>

This project uses the Titanic Survival Challenge dataset to predict the likelihood of survival for passengers based on various features, using Logistic Regression. Achieving a score of 84% accuracy, this model aims to provide a simple yet effective approach for classification tasks in machine learning.

## :bar_chart:Project Overview
The Titanic dataset provides a range of features about passengers, including age, gender, fare, cabin class, and more. Our goal is to leverage these features to predict survival probabilities using Logistic Regression.

## :file_folder:Dataset
The dataset is sourced from Kaggle's Titanic Survival Challenge. It contains the following key features:

<b>PassengerId:</b> Unique ID for each passenger
<b>Pclass:</b> Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
<b>Name:</b> Name of the passenger
<b>Sex:</b> Gender of the passenger
<b>Age:</b> Age of the passenger
<b>SibSp:</b> Number of siblings/spouses aboard
<b>Parch:</b> Number of parents/children aboard
<b>Ticket:</b> Ticket number
<b>Fare:</b> Passenger fare
<b>Cabin:</b> Cabin number
<b>Embarked:</b> Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## :robot:Model
The Logistic Regression model was chosen due to its simplicity and effectiveness for binary classification tasks. With this approach, we achieved an 84% accuracy score on the validation set.

## :hammer_and_wrench:Key Steps in the Workflow:
<b>Data Preprocessing:</b> Handling missing values, encoding categorical variables, and scaling.
<b>Feature Engineering:</b> Creating new features and selecting the most impactful ones for prediction.
<b>Model Training:</b> Training the Logistic Regression model on the preprocessed data.
</b>Evaluation:</b> Evaluating the model performance with accuracy metrics.

## :inbox_tray:Installation
Clone the repository:
```bash
git clone <https://github.com/AshokKumar2525/kaggle-competition-Titanic.git>
```
## Install the necessary packages:
```python
pip install -r requirements.txt
```