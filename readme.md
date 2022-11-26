# neural network dimensionality reduction for image recognition
This project is done for machine learning course at New York University in 2022 fall.<br>
<br>
Dimensionality reduction part contains a numpy implementation of principal compoenent analysis, k-means clustering, and k-nearest neighbor from scratch. Then, the algorithms are applied on the mnist dataset.<br>
<br>
Decision tree part contains an application of decision tree and random forest. For decision tree, DecisionTreeClassifier from sklearn.tree is used, classifier.fit(x_train, y_train) is to fit the model, classifier.predict(x_test) method has input parameter of unlabeled observations x_test, and the return value is predicted labels y. standard scaler is used to normalize the data, a for loop is used to generate and use n different seeds for each classifier. For random forest, RandomForestClassifier from sklearn.ensemble is used, an estimator_array is used to store the number of trees in each forest. classifier.fit(x_train, y_train) is to fit the model, classifier.predict(x_test) method has input parameter of observations x_test, and the return value is predicted labels y. standard scaler is used to normalize the data, a for loop is used to generate and use n different seeds for each classifier.
![1](png/1.png)
![2](png/2.png)
![3](png/3.png)
![4](png/4.png)
![5](png/5.png)
