# Logistic-regression-project-with-Python
This project implements Logistic Regression using Python to classify binary outcomes. The aim is to predict probabilities and make classifications based on input features.
In this project we will be working with a fake advertising data set, indicating whether or not a particular internet user clicked on an Advertisement. We will try to create a model that will predict whether or not they will click on an ad based off the features of that user.

This data set contains the following features:

'Daily Time Spent on Site': consumer time on site in minutes

'Age': cutomer age in years

'Area Income': Avg. Income of geographical area of consumer

'Daily Internet Usage': Avg. minutes a day consumer is on the internet

'Ad Topic Line': Headline of the advertisement

'City': City of consumer

'Male': Whether or not consumer was male

'Country': Country of consumer

'Timestamp': Time at which consumer clicked on Ad or closed window

'Clicked on Ad': 0 or 1 indicated clicking on Ad

![image](https://github.com/user-attachments/assets/2ea58ec1-0e62-4aff-a085-b6be893be2e4)
![image](https://github.com/user-attachments/assets/a4e01a93-5225-4de0-ae0d-8d06b962d81e)
![image](https://github.com/user-attachments/assets/8d375a3b-9798-4b0a-b046-c6165a1e5a99)
![image](https://github.com/user-attachments/assets/ceccae9d-7a9e-46fd-bc2e-5178931683d2)
![image](https://github.com/user-attachments/assets/7d05a4b3-170d-4ec0-9de6-a75edb6ec054)


Confusion matrix:
[[133  12]

 [ 15 140]]

Classification report:


            precision    recall  f1-score   support

           0       0.90      0.92      0.91       145
           
           1       0.92      0.90      0.91       155

    accuracy                           0.91       300
