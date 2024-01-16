# Manufacture Insight: Integrating ML and Neural Networks for Predictive Analytics:

• The provided project involves the application of Machine Learning (ML) and Neural Networks to conduct predictive analytics for a Risk Analytics Initiative in Strategic Financial Oversight within the manufacturing sector. The primary focus is on credit risk modeling, particularly predicting the Probability of Default using logistic regression. The project also emphasizes addressing imbalanced data, conducting thorough model validation, and comparing the results of traditional ML methods with Neural Networks.


• A detailed breakdown of the project:

1. Data Exploration and Preprocessing:

The project begins by loading a financial dataset related to manufacturing using the pandas library in Python.
Initial data exploration is performed, including checking the structure, data types, and summary statistics of the dataset.


2. Handling Missing Values:

Traditional approaches are employed to handle missing values. The dataset is modified by filling missing values with zeros.


3. Exploratory Data Analysis (EDA):

Exploratory Data Analysis is conducted to gain insights into the dataset.

Descriptive statistics, correlation analysis, and data visualization are performed to understand the relationships and patterns in the data.


4. Feature Engineering:

The time-related features are extracted from the 'Time' variable, including year, month, date, week day, start time, hour, and minutes.

Data distribution analysis based on different time components is visualized using seaborn.


5. Data Scaling and Imbalance Treatment:

Feature scaling is applied using StandardScaler to standardize the features.

Imbalance treatment is performed using Random OverSampling and SMOTE (Synthetic Minority Over-sampling Technique) to handle the class imbalance problem.


6. Dimensionality Reduction:

Principal Component Analysis (PCA) is utilized for dimensionality reduction, retaining 95% of the 
variance in the data.


7. Model Building (Traditional ML):

The dataset is split into independent (features) and dependent (target) variables.

Random Forest Classifier is chosen as the traditional ML algorithm for credit risk modeling.

Model evaluation metrics such as confusion matrix, classification report, and accuracy scores are 
calculated.

Cross-validation is applied to assess the model's performance on different subsets of the data.


8. Deep Neural Network (DNN) - Artificial Neural Network (ANN):

A DNN model is built using TensorFlow and Keras.

The neural network consists of one hidden layer with eight neurons and an output layer with a sigmoid activation function.

The model is compiled with binary crossentropy loss and accuracy metrics.

Training is conducted on the training set, and the model is evaluated on the test set.


9. Model Evaluation and Comparison:

Both the Random Forest Classifier and the DNN model are evaluated using various metrics.

Training and test accuracies are compared, providing insights into the models' performances.


This comprehensive project combines traditional ML techniques with advanced neural network methods to address credit risk modeling in the manufacturing sector. The utilization of exploratory data analysis, feature engineering, data preprocessing, and model evaluation techniques demonstrates a thorough and systematic approach to predictive analytics.
