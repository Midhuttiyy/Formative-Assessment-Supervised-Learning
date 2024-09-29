Formative Assessment : Supervised Learning



# Dataset:
* Use the breast cancer dataset available in the sklearn library.


# Question ......


## Key components to be fulfilled :

#  1. Loading and Preprocessing  
  

•  Load the breast cancer dataset from sklearn.
  
•  Preprocess the data to handle any missing values and perform necessary feature scaling.
  
•  Explain the preprocessing steps you performed and justify why they are necessary for this dataset.

# 2. Classification Algorithm Implementation 
  

•  Implement the following five classification algorithms:
     1. Logistic Regression
     2. Decision Tree Classifier
     3. Random Forest Classifier
     4. Support Vector Machine (SVM)
     5. k-Nearest Neighbors (k-NN)
  
•  For each algorithm, provide a brief description of how it works and why it might be suitable for this dataset.

# 3. Model Comparison 
  

•  Compare the performance of the five classification algorithms.
  
•  Which algorithm performed the best and which one performed the worst? 





## Explanation : ......

# Preprocessing steps explanation:
* StandardScaler is used to scale the features to have zero mean and unit variance.
* This is necessary to prevent features with large ranges from dominating the model.

# Algorithm descriptions:
* 1. Logistic Regression: A linear model that predicts probabilities.
* 2. Decision Tree: A tree-based model that splits data into regions.
* 3. Random Forest: An ensemble of decision trees that reduces overfitting.
* 4. SVM: A linear or nonlinear model that finds the best hyperplane.
* 5. k-NN: A model that predicts based on nearest neighbors.

# Best and worst performing algorithms:
* Best: Random Forest (accuracy: 0.97)
* Worst: Decision Tree (accuracy: 0.91)

