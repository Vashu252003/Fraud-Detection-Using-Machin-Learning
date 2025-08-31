🏦 Bank Card Fraud Detection Using
Machine Learning

A Python-based interactive application that detects fraudulent credit card transactions.
The project uses Logistic Regression, Naive Bayes, and Decision Tree classifiers and provides
an interactive Streamlit interface for visualization and manual transaction verification.

✨ Key Features

●

●

●

●

Understand the dataset and check for missing or duplicate values.
Univariate, bivariate, and multivariate analysis of features.

Feature scaling using StandardScaler.
Skewness mitigation with PowerTransformer.
Handling imbalanced datasets using undersampling techniques.

Exploratory Data Analysis (EDA)
○
○
Data Preprocessing
○
○
○
Machine Learning Models
○
Logistic Regression
○
Naive Bayes
○
Decision Tree
○
Model comparison with accuracy, recall, precision, F1-score, and AUC.
Interactive Streamlit Dashboard
○
○
○

Visualize dataset statistics and distributions.
Compare model performance with ROC curves and confusion matrices.
Manual transaction verification: predict if a transaction is legitimate or fraudulent.

🛠 Installation

1.  Clone the Repository

git clone
[https://github.com/Vashu252003/Fraud-Detection-Using-Machin-Learning.git](https://github
.com/Vashu252003/Fraud-Detection-Using-Machin-Learning.git)
cd Fraud-Detection-Using-Machin-Learning

2.  (Optional) Create a Virtual Environment

⚠ Note: This is highly recommended to avoid dependency conflicts.

●

Windows :
python -m venv .venv
.\.venv\Scripts\activate

●

macOS / Linux :
python3 -m venv .venv
source .venv/bin/activate

3.  Install Dependencies

pip install -r requirements.txt

🚀 Usage

Start the Streamlit App

streamlit run app.py

Use Sidebar Options

●

●
●
●

●

Show the initial dataset – View dataset shape, description, missing values, and
duplicates.
Show the analysis – Visualize univariate, bivariate, and multivariate relationships.
Model building on imbalanced data – Train and preprocess the dataset.
Compare algorithms – Train and evaluate Logistic Regression, Naive Bayes, and
Decision Tree classifiers.
Manual transaction verification – Input features to predict if a transaction is
fraudulent.

📊 Example Outputs

●
●
●

Confusion Matrices and ROC Curves for each model.
Comparative bar chart showing model accuracy.
Interactive feature visualization and manual transaction prediction.

📦 Requirements

●
●
●
●
●
●

pandas
numpy
matplotlib
seaborn
scikit-learn
streamlit

📜 License

This project is licensed under the MIT License.

🌍 Use Cases

●
●
●

Bank fraud detection
Transaction monitoring
Financial anomaly detection
