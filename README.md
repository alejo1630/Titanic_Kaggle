# Titanic - Kaggle Competition

This Python Notebook is a proposal to analyse the Titanic dataset for the [Kaggle Competition](https://www.kaggle.com/competitions/titanic), using several data science techniques and concepts.

## 🔰 What was done?

The analysis of the Titanic case is divided into three main steps: **Pre-Processing**, **Processing** and **Post-Processing**

### Pre-Processing

This step involves qualitative and quantitative analysis of the dataset, which includes

* Plot of the data 
* Pairwise plot and correlation matrix
* Relationships between the input variables and the output
* Missing values analysis
* Imputation Techniques
* Feature Engineering 
* Data scaling

### Processing

In this step a comparison of classification models was carried out, based on their performance taking into account the confussion matrix, cross validation and the f1-macro score. The following models were evaluated:

1. Logistic Regression
2. K-Nearest-Neighbor
3. Naive Bayes Gaussian
4. Naive Bayes Bernoulli
5. Decision Tree Classifier
6. Random Forest Classifier
7. Extra Trees Classifier
8. Support Vector Classifier
9. XGBoost Classifier
10.Multilayer Perceptron Classifier

### Post-Processing

In the last step, the best 4 models obtained in the previous step were tuning with several hyperparamets using **Optuna** library. Finally, a performance comparison was carried out using a balanced data obtained with **SMOTE** library. 


## ⚜ Results 

*Best classification model based on f1-macro score:*  **XGBoost Classifier**

*Original classification score:* **82.96**

*Score after hyperparameter tuning:* **83.41**

*Score after data balancing:* **86.55**

    
## 🔶 What is next?

- Implement more feature engineering ideas with several variables
- Perform tuning process with more hyperparameters and range of values for them
- Try other imputations and data balancing techniques
