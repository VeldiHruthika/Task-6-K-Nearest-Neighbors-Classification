Task 6: K-Nearest Neighbors (KNN) Classification

About this Task:

-Hey! This is my sixth task, where I worked with the K-Nearest Neighbors (KNN) algorithm for classification problems.

-For this, I used the famous Iris dataset from Scikit-learn.

What I did in this task:

1.Loaded the Iris dataset using Scikit-learn’s built-in function.

2.Explored the dataset:

i.Checked shape and class names (Setosa, Versicolor, Virginica).

ii.Features included Sepal Length, Sepal Width, Petal Length, Petal Width.

3.Normalized (standardized) the features using StandardScaler, because KNN is distance-based and works better with scaled data.

4.Split the dataset into training and testing sets (80-20 split).

5.Trained KNN models for different values of K (1, 3, 5, 7):

i.Calculated test accuracy for each K.

ii.Found that K=3, 5, 7 gave 100% accuracy, while K=1 gave 96.7%.

iii.So I picked K=3 as my final model for further evaluation.

6.Evaluated the final KNN model (K=3) using:

i.Classification report:
It showed perfect precision, recall, and f1-score (all 1.0) on the test set.

ii.Confusion matrix:
Gave a perfect diagonal matrix (no misclassifications).

7.Plotted the Decision Boundary:

i.Used only the first two features (Sepal Length & Sepal Width) to make a 2D visualization.

ii.Used matplotlib and ListedColormap for nice color regions.

iii.Plotted points for each class with different colors.
