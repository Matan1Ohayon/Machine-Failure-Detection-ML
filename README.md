### 🤖 Machine Failure Prediction - ML Classification Project
A full machine learning project designed to predict machine failures using operational and sensor data.  
The project includes data exploration, feature analysis, model training, hyperparameter tuning, and a full written evaluation report summarizing all results.

---

### ✨ Features
- 📊 Comprehensive EDA - class distribution, correlations, feature behavior  
- 🔧 Preprocessing - scaling, encoding, cleaning  
- 🤖 Multiple ML Models - Logistic Regression, KNN, Decision Tree  
- ⚙️ Hyperparameter Tuning - neighbors (KNN) and tree depths (DT)  
- 🧠 Feature Importance Analysis - identifying critical parameters  
- 📝 Detailed Report - coefficients, confusion matrices, performance tables, and insights  
- 📉 Impact Study - model performance before/after removing key features  
- 🏆 Model Ranking - selection of best models based on recall (failure detection priority)

---

### 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-Learn  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

### ▶️ How to Run
1. Install dependencies:  
```bash
pip install numpy pandas scikit-learn matplotlib seaborn  
```

2. Open the notebook:  
```bash
jupyter notebook Machine_Failure_Prediction_Matan_Ohayon_Itay_Nov.ipynb  
```

Run all cells to reproduce the full workflow:  
EDA → preprocessing → models → metrics → analysis.

---

### 📊 Key Findings (Based on the Evaluation Document)
- The dataset is highly imbalanced:  
  - Class 0 (no failure): 134,281 samples  
  - Class 1 (failure): 2,148 samples  
- Logistic Regression coefficients and intercepts were documented for two configurations.  
- Removing critical features caused recall to drop from ~0.767 to **0.022**, proving their importance.  
- KNN and Decision Tree were tested with four hyperparameter configurations each.  
- Detailed accuracy, precision, recall, and train/test performance tables were documented in the report.  
- The top-performing models were chosen specifically for delivering the **highest recall**, ensuring failures are not missed.  
- The feature with the strongest impact on prediction was identified as **Torque [Nm]**.  
  Removing it caused major drops in recall and precision across most models.

---

### 📁 Project Structure
- Machine_Failure_Prediction_Matan_Ohayon_Itay_Nov.ipynb — full ML workflow  
- Evaluation Document.docx — complete written analysis, metrics, coefficients, tables, and conclusions  

---

### 🚀 What This Project Demonstrates
- Building complete machine learning classification pipelines  
- Handling imbalanced datasets and evaluating the right metrics  
- Comparing ML models with structured documentation  
- Understanding the relationship between features and prediction power  
- Selecting models based on operational needs (recall-first strategy)  
- Combining notebook experimentation with a formal written analysis  

---

### 📬 Contact
🌐 Portfolio: https://matans-portfolio.vercel.app/  
💼 LinkedIn: www.linkedin.com/in/matan-ohayon-4101b6276  
📧 Email: matan1ohayon@gmail.com
