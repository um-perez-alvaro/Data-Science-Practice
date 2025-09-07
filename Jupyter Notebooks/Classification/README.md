# Classification algorithms

## Jupyther notebooks

- [Training a Classification Model with scikit-learn](https://github.com/um-perez-alvaro/Data-Science-Practice/blob/master/Jupyter%20Notebooks/Classification/notebooks/Part%20I%20Classification%20with%20scikit%20learn.ipynb)
    * [k-Nearest-Neighbors](https://github.com/um-perez-alvaro/Data-Science-Practice/blob/master/Jupyter%20Notebooks/Classification/notebooks/k-nearest%20neighbors.ipynb)
    * [Logistic Regression](https://github.com/um-perez-alvaro/Data-Science-Practice/blob/master/Jupyter%20Notebooks/Classification/notebooks/Logistic%20Regression%20.ipynb) 
    * [Decision Trees](https://github.com/um-perez-alvaro/Data-Science-Practice/blob/master/Jupyter%20Notebooks/Classification/notebooks/Decision%20Trees.ipynb)
- [Cross Validation and Evaluation Metrics](https://github.com/um-perez-alvaro/Data-Science-Practice/blob/master/Jupyter%20Notebooks/Classification/notebooks/Part%20II%20-%20Classification%20Metrics%20and%20Cross%20Validation.ipynb)
- Searching for Optimal Hyperparameters
- Feature Engineering
- Pipelines
- Changing the Classification Threshold
- Classification Thresholds and Imbalanced datasets
 
## Practice Problems

**Set 0** (Due Sept 8)

Go to [drawdata.xyz](https://drawdata.xyz/) and select the Scatter Chart option (below the line chart). Use it to draw a dataset for a classification problem. You can place points with up to four different labels (A, B, C, D).

Next, take your dataset and train three classifiers: k-Nearest Neighbors (kNN), Logistic Regression, and a Decision Tree. Use DecisionBoundaryDisplay to plot the classification regions for each method.

Your goal is to create a dataset where at least one of the methods has trouble. Compare the plots and explain briefly which method struggles and why.

**Set 1** (Due Sept 10)

- [Problem 1: Wine Quality Prediction](https://github.com/um-perez-alvaro/Data-Science-Practice/blob/master/Jupyter%20Notebooks/Classification/practice%20problems/Problem%20I%20.ipynb)
- [Problem 2: Bank Note Authentication](https://github.com/um-perez-alvaro/Data-Science-Practice/blob/master/Jupyter%20Notebooks/Classification/practice%20problems/Problem%20II%20.ipynb)
  
**Set 2**

- Problem 3: The MNIST dataset - classification of handwritten digits
- Problem 4: The fashion MNIST dataset


**Set 3**

- Problem 1: Breast cancer diagnosis]
- Problem 2: The Palmer archipelago penguin data
- Problem 3: Bird baths in Australia

**Set 4**
- Problem 4: Chicago traffic crashes prediction


## Datasets

Filename | Description |  Source
--- | --- |  --- 
[good_or_evil_train](https://raw.githubusercontent.com/um-perez-alvaro/Data-Science-Practice/master/Data/good_or_evil_train) <br> [good_or_evil_test](https://raw.githubusercontent.com/um-perez-alvaro/Data-Science-Practice/master/Data/good_or_evil_test) | Characters in the Batman universe | 
[pima](https://raw.githubusercontent.com/um-perez-alvaro/Data-Science-Practice/master/Data/pima.csv) | Pima indians diabetes database | [Kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database) |
[LLCP2019.ASC](https://www.cdc.gov/brfss/annual_data/2019/files/LLCP2019ASC.zip) | The Behavioral Risk Factor Surveillance System Survey | [CDC](https://www.cdc.gov/brfss/annual_data/annual_2019.html)
[pima](https://raw.githubusercontent.com/um-perez-alvaro/Data-Science-Practice/master/Data/pima.csv) | Pima indians diabetes database | [Kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
[iris](https://raw.githubusercontent.com/um-perez-alvaro/Data-Science-Practice/master/Data/iris.csv) | 50 samples of 3 different species of iris | [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)
[streets](https://raw.githubusercontent.com/um-perez-alvaro/Data-Science-Practice/master/Data/streets.csv) | Singapore street names | [Michelle Fullwood](https://michelleful.github.io/code-blog/2015/04/24/sgmap/)
[digits](https://raw.githubusercontent.com/um-perez-alvaro/Data-Science-Practice/master/Data/digits.csv) | Subset of the MNIST dataset 
[digits_test](https://raw.githubusercontent.com/um-perez-alvaro/Data-Science-Practice/master/Data/digits_test.csv) | Subset of the MNIST dataset
[fashion-mnist_train](https://raw.githubusercontent.com/um-perez-alvaro/Data-Science-Theory/master/Data/fashion-mnist_train.csv) </br> [fashion-mnist_test](https://raw.githubusercontent.com/um-perez-alvaro/Data-Science-Theory/master/Data/fashion-mnist_test.csv) | Subsets of the Fashion MNIST dataset | [Kaggle](https://www.kaggle.com/c/insar-fashion-mnist-challenge)
[titanic](https://raw.githubusercontent.com/um-perez-alvaro/Data-Science-Practice/master/Data/titanic.csv) | Famous Titanic daseset from Kaggle | [Kaggle](https://www.kaggle.com/c/titanic)
[winequality-red](https://raw.githubusercontent.com/um-perez-alvaro/Data-Science-Practice/master/Data/winequality-red.csv) |  physiochemical properties of red variants of the Portuguese "Vinho Verde" wine. | [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality)
[BankNote_Authentication](https://raw.githubusercontent.com/um-perez-alvaro/Data-Science-Practice/master/Data/BankNote_Authentication.csv) | genuine and forged banknotes | [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/banknote+authentication)
[abalone](https://raw.githubusercontent.com/um-perez-alvaro/Data-Science-Practice/master/Data/abalone.csv) |  abalone age and physical measurements | [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/abalone)
[cancer](https://raw.githubusercontent.com/um-perez-alvaro/Data-Science-Practice/master/Data/cancer.csv) | Breast Cancer Wisconsin (Diagnostic) Data Set | [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
[penguins_size](https://raw.githubusercontent.com/um-perez-alvaro/Data-Science-Theory/master/Data/penguins_size.csv) | This dataset contains data for 344 penguins. There are 3 different species of penguins in this dataset, collected from 3 islands in the Palmer Archipelago, Antarctica | [Kaggle](https://www.kaggle.com/parulpandey/palmer-archipelago-antarctica-penguin-data) </br> [palmerpenguins](https://allisonhorst.github.io/palmerpenguins/)
[census income](https://raw.githubusercontent.com/um-perez-alvaro/Data-Science-Practice/master/Data/adult_census.csv) | The goal is to predict whether income exceeds $50K/yr based on census data. | [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/2/adult)
