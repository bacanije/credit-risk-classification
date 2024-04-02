# Credit Risk Classificaiton

Using the machine learning model, it allows us to evaluate the lending data to idenitfy creditworthiness of borrowers.

The instructions for this Challenge are divided into the following subsections:

- Split the Data into Training and Testing Sets

- Create a Logistic Regression Model with the Original Data

- Write a Credit Risk Analysis Report

## Analysis Report 

The varaibles included in this dataset consisted of:
- 	loan size
- 	interest rate
- 	borrower income
- 	debt to income
- 	num of accounts
- 	derogatory marks
- 	total debt
- 	loan status

Logistic Regression Model Overview:
The model shows us how well it is performing. Particularly in terms of its ability to correctly identify positive and negative instances, as well as its errors in misclassifying instances as positive when they are negative and vice versa.

Precision (positive predictions): For class 0, precision is 100%, indicating that almost all instances predicted as class 0 were correct. For class 1, precision is 87%, indicating that 87% of instances predicted as class 1 were correct.

Recall (measures the ability of the model to correctly identify instances of a class): Recall is 100% for class 0, all instances of class 0 was identified. Recall for class 1 is 89%, indicating that the model captured 89% of the actual instances of class 1.

F1-score (harmonic mean of precision and recall) Class 0 = 1.00, indicating excellent performance. Class 1 = 0.88, indicating good performance but slightly lower than class 0.

Accuracy: The overall accuracy of the model is 99%, indicating that it correctly classified 99% of the instances in the test set.

Summary:
We can obeserve that for a healthy loan, the precision is 1.00, meaning that the model predicts a healthy loan is correct 100% of the time. The high-risk loan precision is 0.87, indicating that when the model predicts a loan as high-risk, it is correct 87% of the time.





