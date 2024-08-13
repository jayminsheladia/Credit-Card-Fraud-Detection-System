Name: JAYMIN SHELADIA

Company: CODTECH IT SOLUTIONS

ID: CT8ML1184

Domain: MACHINE LEARNING

Duration: June to August 2024

Mentor: NEELAM HARISH






# Credit-Card-Fraud-Detection-System


**Credit Card Fraud Detection using Support Vector Machine (SVM)**

**Overview**

This project focuses on detecting fraudulent transactions from a credit card dataset using a Support Vector Machine (SVM) classifier. Credit card fraud detection is a critical application of machine learning, where the goal is to identify fraudulent activities based on patterns and anomalies in the transaction data. In this project, the dataset is preprocessed, and an SVM model is trained to classify transactions as either fraudulent or legitimate, achieving a reliable level of accuracy.

**Technology Used**

Python: The core programming language used for implementing the project.

Pandas: Used for data manipulation and analysis, especially for reading and processing the dataset.

NumPy: Utilized for numerical operations and array handling.

scikit-learn: A machine learning library used for:

  Train-Test Split: Splitting the dataset into training and testing sets.

  StandardScaler: Scaling features to a standard range.

  SVM (Support Vector Machine): The classifier used to train and predict fraud in the dataset.

  Accuracy Score: Used to evaluate the performance of the model.

**Activities Performed**

Data Loading:

Loaded the credit card transaction dataset (creditcard.csv) into a Pandas DataFrame.

Feature Selection:

Selected relevant features (V1 to Amount) from the dataset as input variables (X).

Set the target variable (Class), which indicates whether a transaction is fraudulent (1) or legitimate (0).

Data Splitting:

Split the dataset into training and testing sets using an 80/20 split, ensuring that the model is trained on one portion of the data and tested on another for reliable performance evaluation.

Data Preprocessing:

Applied feature scaling using StandardScaler to normalize the data. This step is crucial for SVM as it improves the model's convergence and performance.

Model Training:

Trained an SVM classifier with an RBF kernel, which is effective for non-linear classification problems like fraud detection.

Model Evaluation:

Predicted the outcomes on the test dataset.

Evaluated the model's performance using accuracy as the metric.

**Results**

The SVM model achieved a good accuracy score on the test dataset, demonstrating its effectiveness in distinguishing between fraudulent and legitimate transactions. This result highlights the potential of SVM as a robust method for fraud detection in credit card transactions.

**Conclusion**

This project illustrates the application of SVM for credit card fraud detection, showcasing the process from data preprocessing to model evaluation. The achieved accuracy indicates that the model is capable of making reliable predictions, which is essential for preventing fraud in real-world scenarios.
