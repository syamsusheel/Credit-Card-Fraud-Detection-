# Credit-Card-Fraud-Detection
Credit Card Fraud Detection A machine learning project that identifies fraudulent credit card transactions using various classification algorithms on a real-world imbalanced dataset.

🛠️ Technologies Used This project is implemented using the following tools and libraries:

Python

Jupyter Notebook

Pandas, NumPy – for data manipulation and analysis

Matplotlib, Seaborn – for data visualization

Scikit-learn – for model building, evaluation, and preprocessing

📥 Dataset Description The dataset used is the Credit Card Fraud Detection Dataset from Kaggle. It contains European cardholder transactions in September 2013.

Total records: 284,807

Fraudulent transactions: 492 (~0.17%)

Features:

Time and Amount

V1 to V28: PCA-transformed features for confidentiality

Class: Target variable (0 = Not Fraud, 1 = Fraud)

🔍 Exploratory Data Analysis (EDA) The EDA phase involved:

Checking for missing/null values (none found)

Analyzing the distribution of transaction amounts and times

Visualizing class imbalance (fraud vs. non-fraud)

Generating a correlation heatmap to study feature relationships

🔧 Data Preprocessing The following preprocessing steps were performed:

Feature Scaling: Applied StandardScaler on Time and Amount

Train-Test Split: Stratified 80-20 split to preserve class distribution

Class Imbalance: Investigated effects of imbalanced data on model performance (oversampling if applied)

🤖 Machine Learning Models Multiple classification models were implemented and compared:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM) – Linear & RBF Kernel

K-Nearest Neighbors (KNN)

📈 Model Evaluation The models were evaluated using:

Confusion Matrix

Accuracy, Precision, Recall, F1-Score

Special emphasis was placed on Recall due to the importance of catching fraudulent transactions.

✅ Results All models achieved varying degrees of success in detecting fraud.

Random Forest gave the best overall performance in terms of recall and F1-score (you can fill in exact metrics if needed).

Visualizations like ROC curves and confusion matrices were used for comparison.
