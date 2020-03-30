# MC_REPORT
Sklearn is Simple and efficient tools for predictive data analysis, Accessible to everybody, and reusable in various contexts and Built on NumPy, SciPy, and matplotlib .

We use methods to learn models and they are :
1- Classification 
2- Regression 
3- clustering
4- Dimensionality reduction
5- Preprocessing 

I use =>

Decision Trees:
are a non-parametric supervised learning method used for classification and regression. The goal is to create a model that predicts the value of a target variable by learning simple decision rules inferred from the data features.


RandomForestClassifier : 
is a meta estimator that fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting. The sub-sample size is always the same as the original input sample size but the samples are drawn with replacement if bootstrap=True (default).

Neural network models (supervised):
is a supervised learning algorithm that learns a function by training on a dataset, where m 
is the number of dimensions for input and o is the number of dimensions for output and a target y , it can learn a non-linear function approximator for either classification or regression. It is different from logistic regression, in that between the input and the output layer, there can be one or more non-linear layers, called hidden layers

Support Vector Machines:
are a set of supervised learning methods used for classification, regression and outliers detection.

The advantages of support vector machines are:
	•	Effective in high dimensional spaces.
	•	Still effective in cases where number of dimensions is greater than the number of samples.
	•	Uses a subset of training points in the decision function (called support vectors), so it is also memory efficient.
	•	Versatile: different Kernel functions can be specified for the decision function. Common kernels are provided, but it is also possible to specify custom kernels.
The disadvantages of support vector machines include:
	•	If the number of features is much greater than the number of samples, avoid over-fitting in choosing Kernel functions and regularization term is crucial.
	•	SVMs do not directly provide probability estimates, these are calculated using an expensive five-fold cross-validation (see Scores and probabilities, below).
