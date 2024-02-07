# Module-17
Practical Application Assignment 17.1: Comparing Classifiers

The goal of this project is to develop a classification model on a dataset related to a porteguese bank. The dataset consists of 10 categorical data and 10 numerical data with one output/response variable of boolean type. The data is related to direct marketing campaigns, primarily through phone calls, of a Portuguese banking institution. The classification goal is to predict if the client will subscribe to a term deposit (variable y). The data represents a collection of 17 marketing campaigns.
The dataset was checked for null values and duplicates. After cleaning the data, a baseline model that predicted every outcome to be the majority value was computed. Then 4 models, namely Logistic Regression, KNN classifiers, Decision Trees and SVM, with default parameters were computed to check against the baseline performance. In terms of accuracy, none of them performed better than the baseline model. But within the 4 models, the KNN model seemed to perform the best

Model	Train Time	Train Accuracy	Test Accuracy
0	Logistic Regression	0.400065	0.887395	0.887395
1	KNN	0.144535	0.888688	0.875502
2	Decision Tree	0.883198	0.919577	0.862909
3	SVM	43.661089	0.887395	0.887395

The models were then fine tuned for their parameters. But still, they could not outperform the baseline model.

https://github.com/bijjulak/Module-17/blob/main/Module17_KB.ipynb
