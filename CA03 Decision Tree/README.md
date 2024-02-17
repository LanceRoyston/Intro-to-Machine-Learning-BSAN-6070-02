# CA-03
## Overview:
 
The objective of this project is to leverage the decision tree algorithm to predict the income category by analyzing demographic features.
 
We started with a basic data quality check and simple encoding of the categorical variables to prep them for use in the model. Then, we initialized our model based on the testing and training data and checked the performance. After some tuning, we were able to find our best tree and visualize. Finally, we used our best tree to predict an example case.
 
##Datasets
 
The dataset, sourced from the Census Bureau, entails individuals' salaries as well as 7 demographic variables. The dataset details are as follows:
- Target classes: 2 ('>50K' and '<=50K') [Labels: 1, 0]
- Attributes (Columns): 7
- Instances (Rows): 48,842
Dataset link is as below:
 
https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true (https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true)
 
## Requirements:
Please ensure the following libraries are installed in your environment:
 
    •    pandas
    •    numpy
    •    seaborn
    •    matplotlib.pyplot
 
    •    sklearn.compose
    •    sklearn.preprocessing -> OneHotEncoder
    •    sklearn.metrics -> accuracy_score
    •    sklearn.metrics ->precision_score
    •    sklearn.metrics -> recall_score
    •    sklearn.metrics -> f1_score
    •    sklearn.metrics -. confusion_matrix
    •    sklearn.model_selection -> train_test_split
    •    autoviz.AutoViz_Class -> AutoViz_Class
    •    sklearn.tree -> export_graphviz
    •    sklearn.tree -> DecisionTreeClassifier, plot_tree
    •    sklearn.datasets -> load_iris
 
    •    Graphviz
 
 
##Insights:
 
We used the Decision Tree classifier to achieve >80% accuracy in predicting income level based on the given demographics. 
 
## Acknowledgment:
This project follows t
he instructions provided by [ArinB](https://github.com/ArinB).

 

https://github.com/ArinB (https://github.com/ArinB)
