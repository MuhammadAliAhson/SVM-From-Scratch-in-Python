# Support Vector Machine (SVM) Classifier for Iris Dataset

This repository contains a Python script that implements a Support Vector Machine (SVM) classifier for the famous Iris dataset. The SVM classifier is built from scratch using Python and NumPy.

## Prerequisites
Make sure you have the following libraries installed:
- Pandas
- NumPy
- Scikit-learn
- Seaborn

You can install these libraries using pip:
```
pip install pandas numpy scikit-learn seaborn
```

## Dataset
The Iris dataset is loaded directly from the provided CSV file `Iris.csv`. The dataset contains 150 samples of iris flowers, each with four features: sepal length, sepal width, petal length, and petal width. The target variable is the species of iris, which has three classes: Iris-setosa, Iris-versicolor, and Iris-virginica.

## Pairplot Visualization
Before training the classifier, a pairplot visualization is created using Seaborn. This visualization helps to understand the relationships between different features and how they can be used for classification.

## Training SVM Classifier
The SVM classifier is implemented as a Python class `SVM`. The class contains methods for fitting the model and making predictions. The hyperparameters like learning rate, regularization parameter, and number of iterations can be adjusted during initialization.

## Model Training and Testing
The dataset is split into training and testing sets using the `train_test_split` function from scikit-learn. The SVM classifier is then trained on the training set and tested on the testing set.

## Usage
You can use this script by simply running it in your Python environment. Make sure the `Iris.csv` file is in the same directory as the script or provide the correct path to the file.

## Example Usage
```python
python svm_classifier.py
```

## Output
The script outputs the predictions made by the SVM classifier and the actual labels from the testing set. It also prints the accuracy of the classification.

## Medium Article
- [[Link to Medium article](https://medium.com/dev-genius/exploring-svms-potential-with-the-iris-dataset-359fc2de8962)](#) - Share your Medium article discussing this project and your insights.

## Author
This script is authored by [Muhammad Ali Ahson].

Feel free to reach out with any questions or suggestions!
