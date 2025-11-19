# 📞 Telecom Customer Churn Prediction

This project predicts whether a customer will **churn** based on their usage behavior, contract type, payment method, and service-related parameters.

The goal is to build a supervised Machine Learning model that can help telecom companies identify customers who are likely to leave and take preventive actions.

---

## 📘 Project Notebook
All analysis, visualizations, preprocessing, and model training are done in this Jupyter notebook:

📄 `notebooks/Telecom Data Churn Prediction No.2.ipynb`

---

## 📂 Dataset
The dataset used for this project is stored here:

📄 `data/Telecom data github project 2.csv`

**Common columns include:**
- CustomerID  
- Gender  
- SeniorCitizen  
- Partner / Dependents  
- Tenure  
- Contract type  
- Payment method  
- Monthly & Total charges  
- Internet & phone services  
- Target: **Churn (Yes/No)**  

---

## 🚀 Project Workflow

### **1️⃣ Import & Understand Data**
- Load CSV  
- Convert column types  
- Handle missing values  
- Explore categorical & numerical features  

### **2️⃣ Exploratory Data Analysis**
- Churn distribution  
- Contract vs. Churn  
- Tenure vs. Churn  
- Payment methods  
- Services affecting churn (InternetService, TechSupport, etc.)  
- Correlation heatmaps & countplots  

### **3️⃣ Preprocessing**
- Encoding categorical features  
- Scaling numerical features  
- Train-test split  

### **4️⃣ Model Training**
You may have used models like:
- Random Forest Classifier (RFC)  
- Decision Tree
- KNN


### **5️⃣ Evaluation**
Metrics used:
- Accuracy  
- Precision / Recall  
- F1-score  
- Confusion matrix  
- ROC-AUC curve  

### **6️⃣ Prediction**
The final model predicts:
```
Churn = Yes / No
```
based on input customer features.

---

## 📦 Requirements
This project uses the following Python libraries:

```
pandas
numpy
scikit-learn
matplotlib
seaborn
jupyterlab
```



## 🖥️ How to Run This Project Locally

### 1. Clone the repo
```bash
git clone https://github.com/udiits/Telecom-Churn-Prediction.git
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook
```bash
jupyter notebook
```

### 4. Open the notebook
```
notebooks/Telecom Data Churn Prediction No.2.ipynb
```

---

## 📁 Project Structure
```
Telecom-Churn-Prediction/
├── data/
│   └── <dataset>.csv
├── notebooks/
│   └── Telecom Data Churn Prediction No.2.ipynb
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 📝 Results
- Successfully predicts churn based on customer profile  
- Identifies important features affecting churn such as:  
  - Contract type  
  - Tenure  
  - Payment method  
  - Internet service  
  - Tech support  
- Helps telecom companies reduce churn using targeted retention strategies

---

## ✨ Future Improvements
- Deploy model using Streamlit  
- Build a FastAPI endpoint  
- Improve accuracy with hyperparameter tuning  
- Try ensemble models like LightGBM / CatBoost  

---

## 👤 Author
**Udit Sharma**  
GitHub: https://github.com/udiits
Special thanks to https://github.com/SUKHMAN-SINGH-1612

