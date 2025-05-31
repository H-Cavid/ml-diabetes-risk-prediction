# 🧠 Diabetes Risk Prediction – TƏBİB Monitoring Initiative

This project presents a machine learning pipeline for predicting diabetes risk based on clinical and demographic data. Developed as part of a machine learning module at FH Kiel, the project simulates a real-world healthcare initiative (TƏBİB Diabetes Monitoring) and applies predictive modeling techniques such as Decision Trees and K-Nearest Neighbors. The aim is to support early detection and efficient screening in public health systems. The project demonstrates end-to-end skills including data cleaning, exploratory data analysis (EDA), feature engineering, model selection, hyperparameter tuning, and interpretability via feature importance.

---

## 🔍 Objectives

- Predict diabetes risk using clinical data  
- Analyze feature importance (HbA1c, glucose, age, etc.)  
- Evaluate classification models using nested cross-validation  
- Support early detection and healthcare resource allocation for TƏBİB

---

## 📊 Dataset

- Source: [Kaggle – Diabetes Prediction Dataset](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset)  
- 100,000 rows, 9 clinical features  
- Target: `diabetes` (1 = diabetic, 0 = non-diabetic)

---

## 🛠️ Technologies Used

- Python , Jupyter Notebook  
- `pandas`, `numpy` – data handling  
- `matplotlib`, `seaborn`, `plotly` – visualization  
- `scikit-learn` – ML models (Decision Tree, KNN), preprocessing, evaluation  
- **GridSearchCV**, **Nested Cross-Validation** – model tuning & validation  
- **Permutation Importance** – model interpretability  
- **StandardScaler**, one-hot encoding – feature scaling & engineering

---

## 🔧 Techniques Used

- Exploratory Data Analysis (EDA)  
- Outlier detection and data cleaning  
- One-hot encoding and feature engineering  
- Decision Tree, KNN, Dummy Classifier  
- GridSearchCV and Nested Cross-Validation  
- Permutation Importance  
- Confusion Matrix & Classification Reports

---

## 🗂️ Project Structure

```
ml-diabetes-risk-prediction/
├── data/ # (optional) input data files
├── notebooks/ # Jupyter notebook: experiments.ipynb
├── requirements.txt # Python dependencies
├── README.md # Project overview and instructions
├── .gitignore # Ignored files
└── env/ # Virtual environment (not pushed)
```


---

## 📈 Visualizations

- Histograms and boxplots of age, BMI, HbA1c, glucose  
- 3D scatter plot of Age vs BMI vs HbA1c  
- Feature-target relationship plots (bar, line, density)  
- Correlation heatmap  
- Permutation-based feature importance  
- Confusion matrix heatmap

---

## 📄 Results

- Final model: **Decision Tree**, tuned with GridSearchCV  
- Validated with nested cross-validation  
- Most predictive features: `HbA1c_level`, `blood_glucose_level`

| Metric       | Score     |
|--------------|-----------|
| Accuracy     | 97.08%    |
| Precision    | 97.08%    |
| Recall       | 97.08%    |
| F1 Score     | 96.86%    |

---

## ▶️ How to Run

```bash
# Clone the repo
git clone https://github.com/your-username/ml-diabetes-risk-prediction.git
cd ml-diabetes-risk-prediction

# Create virtual environment
python -m venv env
source env/bin/activate  # Or use `env\Scripts\activate` on Windows

# Install required libraries
pip install -r requirements.txt

# Open the notebook
jupyter notebook notebooks/experiments.ipynb
```
---

## 📜 License

This project is licensed under **CC BY-NC-ND 4.0**.

- You **can** view and share the project with proper credit.  
- You **cannot** use it for commercial purposes or modify/reuse it as your own.

---

## 👤 Author

**Javid Hasanov**  
Master's student in Data Science at FH Kiel
  
[LinkedIn](https://www.linkedin.com/in/javidhasanov-tech/) • [GitHub](https://github.com/H-Cavid)

