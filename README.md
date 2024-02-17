# HR Analytics

## Project Overview

This is a public dataset on Kaggle Platform. A large company X has around 4000 employees at any given point of time. However, around 15% of its employee choose to leave and company have to find people to repalce with them from its talent pool. The management wish to improve attrition (retain employee) for the various reason:
*  project may get delayed so that timeline is not meet
*  a sizeable department needs to be maintained 
*  new employees needs training and time.

Thus, 1 HR team was contracted by firm to understand what they shall care more to retain employees. In other words, what could they have done to get most employees stayed. 

To solve such a problem, I have completed few analysis on its dataset to provide my insights. Data link is [Link](https://www.kaggle.com/datasets/vjchoudhary7/hr-analytics-case-study)

## Codes and Resources Used
* DataSpell, JupterNotebook, or any IDE could run Python 
* Python 3.8
* Python Packages Used：

    * Data Manipulation: pandas, numpy
    * Data Visualization: seaborn, matplotlib
    * Machine Learning Libraries: sklearn


###  Data Visualisation
HR Analytics Dashboard is generated by PowerBI. The following snapshot are page for Visualisation and Ingishts.
<img alt="Dashboard"  src="HR Dashboard.png" />


### Tasks & Results 
The most common classification algorithms: logistic regression, SVM, decision tree, navie bayes, random forests (bagging) are used to find out importance of features in the dataset so as to matintain good employees in the end.
All classification algorithms are evaulated by Confusion Matrix and ROC, AUC curve. Random Forests ranks the best due to bagging behind.


<img alt = "Confusion Matrix"  src="Confusion Matrix.png" width="280">

#### Feature Importance
<img src = 'Feature Importance.png' width = "280" height = "300">



## Versioning
Github/Git are used for versioning/sharing. 

## Authors

* **James Li** 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

