# Machine_project
I'm Intrducing my first machine learning model after completing the machine learning course from SHAI for AI 
## Project Overview
The goal of this project is to predict the type of forest cover based on various environmental features.
The dataset includes multiple features such as elevation, aspect, slope, and soil type, which are used to classify the forest cover type into one of seven categories.
## Dataset
The dataset used for this project is the Forest Cover Type dataset from Kaggle. It contains 581,012 rows and 54 columns, including both features and the target variable.

## Preprocessing Steps
The data preprocessing involved the following steps:
 1.Data Cleaning:Like removing outliers, making sure there is no duplicates or missing values.
 2.Exploratory Data Analysis (EDA): Used charts and visualizations to understand the data distribution and relationships between features.
 3.Feature Scaling: Applied standardization techniques to ensure that features are on a similar scale for models like Logisitic regression and KNN that are sensitive to the scale of input features.
 
## Models Used
Four different machine learning models were implemented and trained on the dataset:

Logistic Regression
Decision Tree
Random Forest
K-Nearest Neighbors (KNN)

## Hyper paramter tuning
Used the RandmoizedSearchCV from Sickit-learn for hyper Parameter tuning step

## Scores
Comparing before and after hyper parameter tuning and seeing who performed the best using four metrics scores and seeing who performed the best:
Accuracy score
Precision score
Recall score
F1 score

## Results
The performance of the models was evaluated using a confusion matrix.
The true positives (TP) and true negatives (TN) values indicate that the models performed well in classifying the forest cover types accurately
![Screenshot 2024-11-08 182219](https://github.com/user-attachments/assets/9c290439-5222-4eff-80bc-0dd15c561187)

## Contributing
If you would like to contribute to this project, feel free to fork the repository and submit a pull request.
Any improvements or suggestions are welcome!

## Thank you message
Thank you for checking out my project! I hope you find it useful and informative. 
If you have any questions or feedback, feel free to reach out.
