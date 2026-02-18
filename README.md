#  Logistic Regression from Scratch – Deep Learning Lab 3

This project implements **Logistic Regression from scratch using Python and NumPy** as part of Deep Learning Lab 3.

The goal of this lab is to understand how a model makes **soft decisions (probabilities)** instead of only YES/NO decisions like a perceptron.

---

## Objective

* Implement logistic regression without using ML libraries
* Understand probability-based prediction
* Train model on Glass dataset
* Convert multi-class dataset into binary classification
* Learn how weights update during training

---

##  Dataset

Dataset used: **Glass Identification Dataset**
Download from Kaggle:
https://www.kaggle.com/datasets/uciml/glass

Place the file `glass.csv` in the same folder as the notebook/script.

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn (only for train-test split & scaling)

No machine learning model from sklearn is used.
Logistic regression is implemented manually.

---

## Steps Performed

1. Load dataset using pandas
2. Inspect columns and data
3. Convert multi-class output into binary classification
4. Split dataset into training and testing sets
5. Scale features using StandardScaler
6. Implement sigmoid function
7. Implement prediction function
8. Implement binary cross-entropy loss
9. Update weights using gradient descent
10. Train model for multiple epochs
11. Evaluate accuracy on test data
12. Test with different decision thresholds

---

## How the Model Works

Logistic regression calculates:

* Weighted sum of inputs
* Applies sigmoid function
* Produces probability between 0 and 1
* Converts probability into class label

Model learns by reducing error using gradient descent and updating:

* Weights
* Bias



##  How to Run the Project

1. Install required libraries:

pip install numpy pandas scikit-learn


2. Download dataset and place `glass.csv` in project folder.

3. Run the Python file or Jupyter notebook:

python logistic_regression.py


4. Output will show:

* Training loss
* Final weights and bias
* Test accuracy

---

## Expected Output

* Decreasing loss during training
* Final learned weights
* Prediction accuracy on test data
* Comparison using different thresholds (0.5 vs 0.7)

---

##  Learning Outcome

After completing this lab, you will understand:

* Difference between perceptron and logistic regression
* Why sigmoid function is important
* How probability-based models work
* How weights update during learning
* Limitation of linear models


