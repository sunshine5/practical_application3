## Business Objective of the task:

For the given marketing bank products [data](https://archive.ics.uci.edu/dataset/222/bank+marketing), create K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines classifiers. Measure and compare the performance of each classifier.

## The baseline score:
The baseline score for Dummy classifier (baseline model) was established in the beginning and is as captured below.
*  0.8865015780529255

## Performance results:
The following tables captures the results.  Models covered are, K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines.

  <img width="812" height="461" alt="Results_comparision" src="https://github.com/user-attachments/assets/7b70a223-d6ef-4ada-ad6e-9594cd1821c2" />


## Insights:
### The results for first run for all model with default parameters is captured in the first table.
The highlights of the results analysis is captured below.
* The train time is lowest for kNN and highest for SVM
* Decision Tree has highest Train accuracy 
* Logistic Regression has highest Test accuracy 

### The results for the runs with GridSearchCV best params are captured in the second table.
The observations from the comparison with the first run with default parameters are captured below.
* Decision Tree default parameter run was below the established baseline score.
* The Test accuracy was improved with GridSearchCV best params run for following models.
    * kNN and
    * Decision Tree
* The Train accuracy was lower with GridSearchCV best params run when compared with default parameter run.

## Jupyter Notebook:
* https://github.com/sunshine5/practical_application3/blob/main/prompt_III.ipynb

