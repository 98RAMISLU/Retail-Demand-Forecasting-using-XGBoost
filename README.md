# 📦 Retail Demand Forecasting using XGBoost

Built a retail demand forecasting model using XGBoost with hyperparameter tuning. Includes EDA, preprocessing, model training, evaluation, and an interactive Streamlit app for real-time demand prediction.

---

## 🚀 Demo

Run the app locally:

```bash
streamlit run app.py
```

---

## 📁 Project Structure

```
├── app.py                  # Streamlit web application
├── demand_forecasting.ipynb # Jupyter notebook (EDA + Model Training)
├── xgboost_demand.pkl      # Saved XGBoost model
├── label_encoders.pkl      # Saved label encoders
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation
```

---

## 📊 Dataset Features

| Feature | Description |
|---|---|
| Price | Original product price |
| Discount | Discount percentage applied |
| Inventory Level | Current stock available |
| Promotion | Whether product is on promotion (0/1) |
| Competitor Pricing | Competitor product price |
| Category | Product category |
| Demand | Target variable — units demanded |

---

## ⚙️ Project Workflow

```
Data Loading
     ↓
Exploratory Data Analysis (EDA)
     ↓
Feature Engineering (Discounted Price, Stock Through Rate)
     ↓
Label Encoding (Category)
     ↓
Train Test Split (80/20)
     ↓
XGBoost Model Training
     ↓
Hyperparameter Tuning (RandomizedSearchCV)
     ↓
Model Evaluation (MAE, MSE, RMSE, R²)
     ↓
Save Model (Pickle)
     ↓
Streamlit App Deployment
```

---

## 🛠️ Built With

- **Python** — Core programming language
- **Pandas & NumPy** — Data manipulation and analysis
- **Matplotlib & Seaborn** — Data visualization
- **Scikit-learn** — Preprocessing and model evaluation
- **XGBoost** — Demand prediction model
- **Streamlit** — Interactive web application
- **Pickle** — Model serialization

---

## 📈 Model Performance

| Metric | Value |
|---|---|
| RMSE | 35.58 |

---

## 🔧 Installation

**2. Install dependencies:**
```bash
pip install -r requirements.txt
```

**3. Run the app:**
```bash
streamlit run app.py
```

---

## 📦 Requirements

```
pandas
numpy
scikit-learn
xgboost
streamlit
matplotlib
seaborn
pickle
```

---

## 🎯 Key Features

- Exploratory data analysis with statistical insights
- Feature engineering — Discounted Price and Stock Through Rate
- Hyperparameter tuning using RandomizedSearchCV
- Feature importance visualization
- Interactive web app for real time demand prediction
- Trained model saved for instant deployment

---

## 📌 How to Use the App

1. Enter **Price** of the product
2. Enter **Discount** percentage
3. Enter current **Inventory Level**
4. Select whether **Promotion** is active
5. Enter **Competitor Price**
6. Select **Product Category**
7. Click **Predict Demand** button
8. Get instant demand prediction! ✅

---
