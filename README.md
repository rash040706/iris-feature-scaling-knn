# Iris Feature Scaling with k-NN

## Project Objective

The objective of this project is to improve the performance of a k-Nearest Neighbors (k-NN) classifier by applying Feature Scaling to the Iris dataset.

## Technologies Used

* Python
* Scikit-learn

## Dataset

The Iris dataset contains 150 flower samples belonging to three species:

* Setosa
* Versicolor
* Virginica

Each sample contains:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

## Task 6: Feature Scaling and Evaluation

### Steps Performed

1. Loaded the Iris dataset.
2. Split the dataset into training and testing sets.
3. Applied MinMaxScaler to normalize feature values between 0 and 1.
4. Trained a k-NN classifier with k = 5.
5. Predicted flower species on the test dataset.
6. Evaluated performance using Accuracy, Classification Report, and Confusion Matrix.

## Results

* Accuracy: 100.00%
* All flower species were correctly classified.
* No misclassifications were observed in the confusion matrix.

## Conclusion

Feature Scaling helps k-NN perform more effectively because all features contribute equally to distance calculations. After scaling, the model achieved excellent classification performance on the Iris dataset.
