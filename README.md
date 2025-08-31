extend this only and add in this

# 🏦 Bank Card Fraud Detection Using Machine Learning

A Python-based interactive application that detects fraudulent credit card transactions. The project uses Logistic Regression, Naive Bayes, and Decision Tree classifiers and provides an interactive Streamlit interface for visualization and manual transaction verification.

## ✨ Key Features

### Exploratory Data Analysis (EDA)

- Understand the dataset and check for missing or duplicate values.
- Univariate, bivariate, and multivariate analysis of features.

### Data Preprocessing

- Feature scaling using StandardScaler.
- Skewness mitigation with PowerTransformer.
- Handling imbalanced datasets using undersampling techniques.

### Machine Learning Models

- Logistic Regression
- Naive Bayes
- Decision Tree
- Model comparison with accuracy, recall, precision, F1-score, and AUC.

### Interactive Streamlit Dashboard

- Visualize dataset statistics and distributions.
- Compare model performance with ROC curves and confusion matrices.
- Manual transaction verification: predict if a transaction is legitimate or fraudulent.

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Vashu252003/Fraud-Detection-Using-Machin-Learning.git
cd Fraud-Detection-Using-Machin-Learning
```

### 2. Create Virtual Environment

Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

macOS/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
streamlit run app.py
```

## 📦 Requirements

pandas

numpy

matplotlib

seaborn

scikit-learn

streamlit

## 🌍 Use Cases

Bank fraud detection

Transaction monitoring

Financial anomaly detection

## 📜 License

This project is licensed under the MIT License.
