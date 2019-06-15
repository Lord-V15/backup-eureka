# All my files for the KNN Classifers project

More Details below : 

Not to be confused with k-means clustering.

In pattern recognition, the k-nearest neighbors algorithm (k-NN) is a non-parametric method used for classification and regression. 

In both cases, the input consists of the k closest training examples in the feature space. The output depends on whether k-NN is used for classification or regression: 
      In k-NN classification, the output is a class membership. An object is classified by a plurality vote of its neighbors, with the             object being assigned to the class most common among its k nearest neighbors (k is a positive integer, typically small). If k = 1,         then the object is simply assigned to the class of that single nearest neighbor.
      In k-NN regression, the output is the property value for the object. This value is the average of the values of k nearest neighbors.

k-NN is a type of instance-based learning, or lazy learning, where the function is only approximated locally and all computation is deferred until classification. The k-NN algorithm is among the simplest of all machine learning algorithms. 
Both for classification and regression, a useful technique can be used to assign weight to the contributions of the neighbors, so that the nearer neighbors contribute more to the average than the more distant ones. For example, a common weighting scheme consists in giving each neighbor a weight of 1/d, where d is the distance to the neighbor.

NOTE : I have made all the codes from scratch for my personal understanding. Other methods like importing classifier functions from sklearn library may also be used. 
