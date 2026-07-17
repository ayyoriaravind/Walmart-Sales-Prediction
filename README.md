# 🛒 Walmart Sales Prediction using Machine Learning

Predicting Walmart weekly sales using multiple machine learning regression models and comparing their performance.

---

## 📌 Project Overview

This project aims to predict **Walmart Weekly Sales** using historical sales data and machine learning techniques.

The project covers the complete machine learning workflow:
- Data Loading
- Data Cleaning
- Feature Engineering
- Data Visualization
- Model Training
- Model Evaluation
- Model Comparison

---

## 📂 Dataset

- **Dataset:** Walmart Sales Dataset
- **Source:** Kaggle
- **Target Variable:** `Weekly_Sales`

### Features

| Feature | Description |
|----------|-------------|
| Store | Store ID |
| Date | Sales Date |
| Holiday_Flag | Holiday Indicator |
| Temperature | Temperature |
| Fuel_Price | Fuel Price |
| CPI | Consumer Price Index |
| Unemployment | Unemployment Rate |

---

## 🛠️ Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Git & GitHub

---

## ⚙️ Machine Learning Workflow

```
Load Dataset
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
Train-Test Split
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Model Comparison
```

---

## 🤖 Models Trained

✅ Linear Regression

✅ Random Forest Regressor

✅ XGBoost Regressor

---

## 📊 Model Performance

| Model | MAE | RMSE | R² Score |
|------|---------:|---------:|---------:|
| Linear Regression | 432293.59 | 521321.81 | 0.1564 |
| Random Forest | 72529.55 | 139618.27 | 0.9395 |
| ⭐ XGBoost | **67515.64** | **118437.00** | **0.9565** |

---

## 🏆 Best Model

**XGBoost Regressor** achieved the best performance.

- ✅ Highest R² Score
- ✅ Lowest MAE
- ✅ Lowest RMSE

**Final R² Score:** **0.9565**

---

## 📁 Repository Structure

```
Walmart-Sales-Prediction/
│
├── Walmart_Sales.csv
├── Walmart_Sales_Prediction.ipynb
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/Walmart-Sales-Prediction.git
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Open the Notebook

Open `Walmart_Sales_Prediction.ipynb` using:

- Google Colab
- Jupyter Notebook

Run all cells.

---

## 📈 Future Improvements

- Hyperparameter Tuning
- Streamlit Web Application
- Model Deployment
- Real-time Sales Prediction
- Model Saving using Joblib

---

## 👨‍💻 Author

**Aravind**

---

⭐ If you found this project useful, consider giving it a star!
