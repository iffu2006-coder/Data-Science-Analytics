## Project 2: Predicting Insurance Claim Amounts

### Objective

The objective of this project is to predict medical insurance charges based on personal data such as age, BMI, smoking status, gender, region, and number of children.

### Dataset Used

Medical Cost Personal Dataset

### Tools and Libraries Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

### Project Description

In this project, I used the Medical Cost Personal Dataset to predict insurance claim amounts. First, I loaded the dataset using pandas and checked its structure using functions such as head, shape, columns, info, and describe. I also checked missing values and duplicate records.

After that, I performed data visualization to understand how age, BMI, and smoking status affect insurance charges. I created graphs such as box plot and scatter plots using Matplotlib and Seaborn.

Categorical features such as sex, smoker, and region were converted into numerical form using one-hot encoding. Then, I separated the dataset into features and target variable. The target variable was charges because the aim was to predict insurance charges.

A Linear Regression model was trained using the training data and tested on the testing data. The model performance was evaluated using MAE, RMSE, and R2 Score.

### Conclusion

The project showed that smoking status, age, and BMI are important factors that affect insurance charges. Smokers usually have higher insurance charges compared to non-smokers. The Linear Regression model was able to predict charges and was evaluated using proper regression evaluation metrics.

Ifra Shakir
