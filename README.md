# Credit Card Fraud Detection using AI/ML

## 📖 Overview
Credit card fraud is a major challenge in the financial industry. This project leverages machine learning and AI to detect fraudulent transactions accurately. By analyzing transaction patterns, the model identifies anomalies that are likely to be fraudulent.

## 🚀 Features
- **Data Preprocessing:** Handles missing values, scales numerical data, and encodes categorical features.
- **Exploratory Data Analysis (EDA):** Visualizes trends, correlations, and anomalies.
- **Model Training:** Includes Logistic Regression, Random Forest, Gradient Boosting, and Neural Networks.
- **Model Evaluation:** Measures performance using metrics like precision, recall, F1-score, and AUC-ROC.
- **Real-time Prediction API:** A REST API for predicting transaction fraud in real time.
- **Deployment:** Deployed using Flask/FastAPI and Docker for scalability.

---

## 📂 Project Structure
```plaintext
.
├── data/                  # Dataset files
├── notebooks/             # Jupyter notebooks for EDA and model training
├── src/                   # Source code
│   ├── preprocessing.py   # Data preprocessing scripts
│   ├── model.py           # Model training and evaluation
│   ├── api.py             # Flask/FastAPI for deployment
├── tests/                 # Unit tests for the project
├── Dockerfile             # Docker configuration
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
