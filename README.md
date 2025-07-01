# KNN_Clasification
# Task 6: K-Nearest Neighbors (KNN) Classification

Objective
Understand and implement the K-Nearest Neighbors algorithm for classification problems using the Iris dataset.

Tools Used
- Python
- Scikit-learn
- Pandas
- Matplotlib

Dataset
I used the Iris dataset available from `sklearn.datasets`. It contains 150 records of iris flowers, each described by 4 features:
- Sepal length
- Sepal width
- Petal length
- Petal width

Target: Classifying the flower species (Setosa, Versicolour, Virginica)

Steps Followed
1. Load the dataset using `load_iris()` from `sklearn.datasets`.
2. Convert to DataFrame for easier analysis using `pandas`.
3. Preprocess the data:
   - Checked for null values.
   - Scaled the features using `StandardScaler` for better distance computation.
4. Train-test split*:
   - Split the dataset into 80% training and 20% testing.
5. Train the KNN model:
   - Used `KNeighborsClassifier` from `sklearn.neighbors`.
   - Tested multiple values of `k` from 1 to 20.
6. Evaluate the model:
   - Used accuracy score and confusion matrix.
   - Plotted error rate vs `k` to choose the best value.

 Visualizations
- Confusion Matrix Heatmap
- Accuracy Score
- Error Rate vs K plot

 What I Learn
- How KNN works in classification.
- Importance of feature scaling.
- Visualizing performance for different values of K.



