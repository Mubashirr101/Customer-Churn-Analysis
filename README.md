# 🧠 Churn Prediction System

A machine learning project designed to predict customer churn . This project showcases the full data science lifecycle from data exploration to deployment & demonstrates how ML can help businesses identify customers at risk of leaving.

---

## 📅 Project Phases

1. **Project Setup & Planning**
2. **Exploratory Data Analysis (EDA)**
3. **Data Preprocessing**
4. **Model Building**
5. **Model Evaluation**
6. **Model Tuning**
7. **Deployment (Streamlit App)**
8. **Finalization & Documentation**

---

## 📁 Directory Structure

```

churn-prediction-system/
├── data/               # Raw and cleaned datasets
├── notebooks/          # Jupyter notebooks for EDA and modeling
├── models/             # Trained models (joblib/pickle)
├── scripts/            # Python scripts for preprocessing, training, etc.
├── app/                # Streamlit app for deployment
├── README.md           # Project overview and instructions
└── requirements.txt    # Required libraries

````

---

## 📊 Dataset

- **Source:** [Kaggle - Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Features:** Customer demographics, account information, service usage, and churn status.

---

## ⚙️ Technologies Used

- Python
- Pandas, NumPy, Scikit-learn
- XGBoost / LightGBM
- Matplotlib, Seaborn
- Streamlit


---

## 📈 Model Evaluation Metrics

- Accuracy
- Precision, Recall, F1-Score
- ROC-AUC
- Confusion Matrix

---

## 🌐 Streamlit App Features

- Predict whether a customer is likely to churn
- Probability score of churn
- Interactive input form
- Visualizations & feature importance

---

## 💡 Bonus Features (Planned)

- SHAP/LIME for interpretability
- SMOTE for handling class imbalance
- Dockerized deployment
- Database integration
- API wrapper

---

## 🛠️ Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/churn-prediction-system.git
   cd churn-prediction-system
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run notebooks and Streamlit app**

   * Open and run EDA & modeling notebooks from `notebooks/`
   * Run Streamlit app:

     ```bash
     streamlit run app/app.py
     ```

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

* Dataset provided by Kaggle user [Blastchar](https://www.kaggle.com/blastchar)
* Inspired by real-world churn use cases in the telecom industry.

---
