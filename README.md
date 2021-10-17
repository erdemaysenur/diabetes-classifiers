# Diabetes Classification

In this notebook, I used 2 classifier model to classify diabetes. The dataset was obtained from [kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database).


## Dataset Description

**Context**

This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.


**Content**
The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.


**Acknowledgements**
Smith, J.W., Everhart, J.E., Dickson, W.C., Knowler, W.C., & Johannes, R.S. (1988). Using the ADAP learning algorithm to forecast the onset of diabetes mellitus. In Proceedings of the Symposium on Computer Applications and Medical Care (pp. 261--265). IEEE Computer Society Press.

**Inspiration**
Can you build a machine learning model to accurately predict whether or not the patients in the dataset have diabetes or not?


## Method

### Feature Engineering

- Created new features
- Dropped some

### Preprocessing

- Deleted outliers out the range of 75-25% quantile
- Scaled features

### Classifying

- Random Forest
- Neural Network

### Optimization

- GridSearchCV
- StratifiedKFold
