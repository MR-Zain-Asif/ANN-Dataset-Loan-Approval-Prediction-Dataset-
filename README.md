# Loan Approval Prediction using ANN

## Objective
Build an Artificial Neural Network (ANN) to predict loan approval status based on applicant information.

## Steps Performed

1. Loaded the dataset using Pandas.
2. Explored the dataset and checked for missing values.
3. Removed the Loan ID column.
4. Encoded categorical features using LabelEncoder.
5. Split the data into training and testing sets.
6. Applied StandardScaler for feature scaling.
7. Built an ANN with three hidden layers using ReLU activation and a Sigmoid output layer.
8. Compiled the model using Adam optimizer and Binary Crossentropy loss.
9. Trained the model for 20 epochs.
10. Evaluated the model using Accuracy, Confusion Matrix, and Classification Report.
11. Saved the trained model.

## Observation

The dataset was successfully preprocessed by encoding categorical variables and scaling numerical features. The ANN model learned the relationship between applicant details and loan approval status, achieving good classification performance on the test data.
