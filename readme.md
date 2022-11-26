# neural network dimensionality reduction for image recognition<br>
Xi Liu<br>
This project is done for machine learning course at New York University in 2022 fall.<br>
<br>
Dimensionality reduction part contains a numpy implementation of principal compoenent analysis, k-means clustering, and k-nearest neighbor from scratch. For the principal compoenent analysis part, mean is subtracted from each sample, then use centered matrix to calculate the covariance matrix whose entries are covariances, and compute eigenvectors of the covariance matrix to identify the direction of maximum vairance. Then, principal component analysis is used on the train dataset to reduce data dimension from 784 to 100. There is a step to reverse the reduced principal components by taking the dot product of x reduced and eigenvectors and add the mean, then it creates a visualization of reconstructed images which look similar with original input images. The k-means clustering algorithm is a centroid based approach in which the distance between each data point and a centroid is computed using Euclidean distance function and choose the cluster from each point with the minimum distance between data point and centroid, and then identify the k number of groups in dataset. the algorithms are applied on the mnist dataset.<br>
<br>
Decision tree part contains an application of decision tree and random forest. For decision tree, DecisionTreeClassifier from sklearn.tree is used, classifier.fit(x_train, y_train) is to fit the model, classifier.predict(x_test) method has input parameter of unlabeled observations x_test, and the return value is predicted labels y. standard scaler is used to normalize the data, a for loop is used to generate and use n different seeds for each classifier. For random forest, RandomForestClassifier from sklearn.ensemble is used, an estimator_array is used to store the number of trees in each forest. classifier.fit(x_train, y_train) is to fit the model, classifier.predict(x_test) method has input parameter of observations x_test, and the return value is predicted labels y. standard scaler is used to normalize the data, a for loop is used to generate and use n different seeds for each classifier.
![1](png/1.png)
![2](png/2.png)
![3](png/3.png)
![4](png/4.png)
![5](png/5.png)
