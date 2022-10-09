# KNN-Regressor-Cardekho
Implemented K Nearest Neighbor Regressor. Both using Mean and Median of K NN. Compared the performance of each. Also have implemented cross validation to choose optimal k value.
# K Nearest Neighbors Regression on Cardekho Dataset
<ol>
<li> Instance Based Algorithm (Lazy Learner).</li>
<li> Supervised Learning Algorithms which works for both Classification and Regression. </li>
<li> It works based on Mode of KNN for Classification and Mean for Regression.</li>
<li> It works for both Categorical and Numerical Independet Features. </li>
</ol>

<b> Algorithm: </b>
<ol>
<li> Find Distance of each xtest point to xtrain points. </li>
<li> Choose K nearest neigbours of xtest </li>
<li> Classification -> mode(y1,y2....yk) --> yhat, 
<br> Regression -> mean(y1,y2,..yk) ---> yhat </li>
<li> Check Performance metrics </li>
</ol>

<b>Note: </b>
<ul>
<li> k is the hyperparameter can be choosen using cross validation. </li>
<li> Higher the k more the chance for underfitting </li>
<li> Lower the k value more is the chance for overfitting. </li>
<li> There is impact of outliers depending upon k value </li>
<li> Greaty affected by class imbalance. </li>

</ul>

<b> Basic Preprocessing Steps: </b>
<ul>
<li> As KNN works based on Distace so it is better to standardize or normalize before model building. </li>
<li> Handling Outliers. </li>
<li> Handling Imbalanced Datasets by upsampling and downsampling. </li>
</ul>
