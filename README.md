## Project 3: Customer Churn Prediction

### Objective

The objective of this project is to predict whether a bank customer is likely to leave the bank or not using the Churn Modelling Dataset.

### Dataset Used

Churn Modelling Dataset

### Tools and Libraries Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

### Project Description

In this project, I used the Churn Modelling Dataset to predict customer churn. First, I loaded the dataset using pandas and checked its structure using head, shape, columns, info, and describe functions.

After that, I checked missing values and duplicate records to make sure the dataset was clean. I also removed unnecessary columns such as RowNumber, CustomerId, and Surname because they were not useful for prediction.

Then, I performed Exploratory Data Analysis using different graphs. I created visualizations to understand customer churn count, churn by geography, churn by gender, and age distribution of customers.

Categorical columns such as Geography and Gender were converted into numerical form using one-hot encoding because machine learning models work with numerical data. Then, I separated the dataset into input features and target variable. The target variable was Exited because it shows whether the customer left the bank or not.

A Decision Tree Classifier model was trained using the training data and tested using the testing data. The model performance was evaluated using accuracy, confusion matrix, and classification report.

Feature importance was also analyzed to understand which features had the most effect on customer churn prediction.

### Conclusion

This project helped me understand how classification models are used for predicting customer behavior. The analysis showed that customer details such as age, balance, activity status, and other banking features can help predict customer churn. The Decision Tree Classifier was successfully trained and evaluated, and feature importance was used to identify the most important factors affecting churn.
