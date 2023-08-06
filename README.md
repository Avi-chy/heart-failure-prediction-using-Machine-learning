# heart-failure-prediction-using-Machine-learning

Objectives.

The main objective of this research is to create a classification filter (Using Logistics Regression & KNN
Classification Algorithm) to predict Heart Failure. Compare the performance of the filters. The system
can discover and extract hidden knowledge associated with diseases from a Heart-Failure-Prediction
Data Set.

                              Scope and Limitation.

 Scope: 
 
Here the scope of the project is that integration of clinical decision support with
computerbased patient records could reduce medical errors, enhance patient safety, decrease
unwanted practice variation, and improve patient outcome. This suggestion is promising as data
modelling and analysis tools, e.g., data mining, have the potential to generate a knowledge-rich
environment which can help to significantly improve the quality of clinical decisions.

 Limitations:

Medical diagnosis is considered as a significant yet intricate task that needs to be carried out
precisely and efficiently. The automation of the same would be highly beneficial. Clinical decisions
are often made based on doctor’s intuition and experience rather than on the knowledge rich data
hidden in the database. This practice leads to unwanted biases, errors and excessive medical costs
which affects the quality of service provided to patients. Data mining have the potential to generate a
knowledge-rich environment which can help to significantly improve the quality of clinical
decisions.

                             Logistic Regression Model

Logistic regression is a one of the machine learning classification algorithm for analysing a dataset in
which there are one or more independent variables (IVs) that determine an outcome and also
categorical dependent variable (DV) Linear regression uses output in continuous numeric whereas
logistic regression transforms its output using the logistic sigmoid function to return a probability
value which can then be mapped to two or more discrete classes .The logistics regression forms
three types as below.

a) Binary logistics regression (two possible outcomes in a DV)
b) Multinomial logistics regression (three or more categories in DV without ordering)
c) Ordinal logistics regression (three or more categories in DV with ordering)
Furthermore, logistic regression model uses more complex cost function (known as sigmoid
function or logistic function) instead of linear function. Logistic regression limits the cost function
between 0 and1.

Y = 1 / 1+e –z

According to the given data set, 1 indicates the high risk of 10-year future coronary heart disease
and 0 indicates non or no heart risks. The independent variables n in the logistic model as x1, x2,
x3......., xn
Log (P/1-P) = B0+B1*x1+B2*x2...
Logistic regression achieves this by taking the log odds of the event ln(P/1−P), where, P is the
probability of event which is risk of CHD. Therefore, P always lies between 0 and1.


                              K-Nearest Neighbour (KNN)

K-Nearest Neighbour classifier is one of the introductory supervised classifiers, which every data
science learner should be aware of. This algorithm was first used for a pattern classification task
which was first used by Fix & Hodges in 1951. To be similar the name was given as KNN classifier.
KNN aims for pattern recognition tasks.
K-Nearest Neighbour also known as KNN is a supervised learning algorithm that can be used for
regression as well as classification problems. Generally, it is used for classification problems in
machine learning.
KNN works on a principle assuming every data point falling in near to each other is falling in the
same class. In other words, it classifies a new data point based on similarity. Let us understand the
concept by taking an example:
Classification is a process of sorting a given set of data into each different class. Classification can be
implemented on both kinds of data structured as well as unstructured. Classes are often referred to
as labels or targets which hold different classes. For example, classifying different fruits.
Regression is a problem in which our target holds continuous values or real values. Like prediction
of salary or age of a person.
