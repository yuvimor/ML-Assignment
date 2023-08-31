# Predicting Housing Prices

This repository contains the code for the machine learning assignment on predicting housing prices.

## Documentation

**Approach**

The approach I used to predict housing prices is as follows:
1. I loaded the housing price dataset and performed data exploration and cleaning. This involved inspecting the data, handling missing values, and encoding categorical features.
2. I chose three popular regression algorithm to predict housing prices: Linear Regression, Decision Tree and Random Forest.
3. I trained all three models on the training dataset and evaluated their performance on the testing dataset. I used the mean squared error (MSE) and R-squared metrics to evaluate the models' performance.

**Hyperparameter Choices**

The following hyperparameters were chosen for the decision tree algorithm to further improve its accuracy (although failed due to overfitting or noise in the dataset):

* Criterion: This is the criteria used to split the nodes in the decision tree. I chose the "squared_error" criterion, which minimizes the squared error between the predicted and actual values.
* Max depth: This is the maximum depth of the decision tree. I tried different values for this hyperparameter, including 5, 6, and 7.
* Min samples split: This is the minimum number of samples required to split a node. I tried different values for this hyperparameter, including 20, 30, and 40.
* Min samples leaf: This is the minimum number of samples required to be in a leaf node. I tried different values for this hyperparameter, including 10, 15, and 20.
* Max features: This is the number of features to consider when splitting a node. I tried different values for this hyperparameter, including "sqrt", "log2", and None.
* Random state: This is a random seed used to initialize the decision tree. I used the value 42 as it is a popular choice in machine learning. 

**Results**

The decision tree model was able to achieve a mean squared error of 4.7081 on the testing dataset. This means that the model was able to predict the housing prices within an average error of 4.7081. The model was also able to achieve a R-squared value of 0.80443. This means that the model was able to explain 80% of the variation in the housing prices.

**Strengths and Limitations**

The strengths of the model include its simplicity and its ability to explain a large amount of the variation in the housing prices. The limitations of the model include its sensitivity to overfitting and its inability to handle outliers.

Overall, the results of the model are promising. The model was able to achieve a reasonable degree of accuracy in predicting housing prices. However, the model has a few limitations and should be used with caution.

## Dependencies

The following dependencies are required to run the code:

* Python 3.7+
* NumPy
* Pandas
* Scikit-learn
* Matplotlib

## Instructions

To run the code, follow these steps:

1. Clone the repository to your local machine.
2. Open the `Predicting_Housing_Prices.ipynb` Jupyter Notebook.
3. Install the dependencies using the following command:
   pip install -r requirements.txt
4. Run the cells in the Jupyter Notebook in order.

## Output
The output of the code will be a machine learning model that can predict housing prices. The model will be saved as a pickle file.

## Author
This code was written by Yuvraj Mor.
