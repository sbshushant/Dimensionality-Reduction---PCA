# Dimensionality-Reduction---PCA

Introduction
This project focuses on applying Principal Component Analysis (PCA) for dimensionality reduction on the Iris dataset. The goal is to compare the performance of a classifier before and after applying PCA.

Table of Contents
Introduction About the Dataset Data Preprocessing Classifier Before PCA Applying PCA for Dimensionality Reduction Classifier with PCA Evaluation Conclusion

About the Dataset
The Iris dataset is a well-known dataset in the field of machine learning. It contains measurements of various features of iris flowers from three different species. The key features include:

SepalLengthCm: Sepal length in centimeters SepalWidthCm: Sepal width in centimeters PetalLengthCm: Petal length in centimeters PetalWidthCm: Petal width in centimeters Species: Species of the iris flower

Data Preprocessing
Loading Data:
The dataset was loaded into a pandas DataFrame for inspection. Basic information about the dataset, such as the first few rows, was reviewed. Classifier Before PCA

Splitting the Data:
The dataset was split into training and testing sets using an 80-20 split.

Training the Classifier:
A Decision Tree classifier was trained on the original features (without PCA). The classifier's performance was evaluated using accuracy score. Applying PCA for Dimensionality Reduction

Implementing PCA:
PCA was applied to reduce the dimensions of the dataset to 2 principal components. The training and testing sets were transformed using the fitted PCA model.

Classifier with PCA
Training the Classifier with Reduced Dimensions:
A Decision Tree classifier was trained on the reduced feature set obtained from PCA. The classifier's performance was evaluated using accuracy score.

Evaluation
The performance of the classifier before and after applying PCA was compared. Accuracy scores were used to determine the effectiveness of dimensionality reduction on the classification task.

Conclusion
The analysis demonstrated the application of PCA for dimensionality reduction and its impact on classifier performance. Key findings include:

PCA effectively reduced the dimensionality of the dataset while retaining important information. The classifier's performance was compared before and after applying PCA to understand the trade-offs involved in dimensionality reduction. These insights highlight the utility of PCA in simplifying datasets and potentially improving classifier performance by removing redundant features.
