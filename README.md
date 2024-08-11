# LGMVIP-Datascience-Task1

## Iris Species Classification using KNN Classifier Algorithm
### Overview:
The objective of this project is to build a Decision Tree classifier to predict the species of iris flowers based on their physical characteristics. The dataset used for this project is the famous Iris dataset, which contains 150 samples of iris flowers with four features: sepal length, sepal width, petal length, and petal width. The target variable is the species of the iris flower, which can be one of three classes: Iris-setosa, Iris-versicolor, or Iris-virginica.

### Explanation of the Code:
### Step1: Import Libraries:
We import necessary libraries like Scikit-Learn for loading the dataset, splitting the data, scaling features, training the model, and evaluating performance.
### Step2: Load Data:
The Iris dataset is loaded using load_iris(), and we separate the features (X) and the target labels (y).
### Step3: Split Data:
We split the dataset into training and testing sets using train_test_split() with an 80-20 split.
### Step4: Feature Scaling:
We scale the features using StandardScaler() to improve the performance of the model (especially for distance-based algorithms like KNN).
### Step5: Train Model:
We initialize a K-Nearest Neighbors (KNN) classifier and train it on the training data.
### Step6: Make Predictions:
The trained model is used to make predictions on the test set.
### Step7: Evaluate Model:
We calculate and print the accuracy of the model on the test set using accuracy_score().
