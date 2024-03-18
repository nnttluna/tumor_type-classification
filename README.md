# Models for Tumor Type Diagnosis
The project aims to develop a computer model to detect tumor type in using one model from each section, linear, non-linear and trees classification to assist in diagnosis. Two classes will be used in this project: Maglinent or Benign.
# Breast Cancer Dataset
The Dataset for health and it is for Social Good: Women Coders' Bootcamp organized by Artificial Intelligence for Development in collaboration with UNDP Nepal.
This database is also available through the UW CS ftp server:ftp ftp.cs.wisc.educd math-prog/cpo-dataset/machine-learn/WDBC/
# Discussion and Results
With the classification model applied on data of breast cancer to recognize the category of the tumor, one model from each section, linear, non-linear and trees classification, has been picked to generally present the performance of each class. Theoretically, in term of complexity, the models would be arranged from linear, non-linear and trees as the argument behind the algorithm are increasing, which can translate to the order of complexity to be Logistic Regression, Naïve Bayes and Basic Trees. Relatively, higher complexity models are expected to give a better result, proven by accuracy and false negatives. 

Logistic regression is a linear model for classification which will provide the probabilities describing the possible outcomes of a single trial are modeled using a logistic function. Naive Bayes methods are a set of supervised learning algorithms based on applying Bayes’ theorem with the initial assumption of conditional independence between every pair of features given the value of the class variable. Basic decision trees are constructed via an algorithmic approach that identifies ways to split a data set based on different conditions, create a model that predicts the value of a target variable by learning simple decision rules interpreted from the data features. 

When the models are actually implemented, the highest-accuracy performance appears to be **Naïve Bayes model**.

![image](https://github.com/nnttluna/tumor_type-classification/assets/103468427/96d14959-6935-4456-87d9-df61118ea423)


**Basic Decision Trees** happened to be the lowest accuracy as well as the highest number of false negatives predicted, which indicated the least stable performance among all.

![image](https://github.com/nnttluna/tumor_type-classification/assets/103468427/3f0f1f49-2306-4d66-a13d-d84fe5f73304)


With the observation on the characteristics of the data set and the binary categorization, **Logistic Regression** is overall performing with a relatively considerable accuracy of 93% and zero false negatives reported which is the lowest number of false negatives. Since we are predicting if the tumor is benign or malignant and we would not want the model to justify the tumor is benign while it is actually malignant, number of false negatives is extremely crucial while evaluating the performance of the models. 

![image](https://github.com/nnttluna/tumor_type-classification/assets/103468427/a0ba6873-5f73-466c-ab80-0d6f5c050176)


