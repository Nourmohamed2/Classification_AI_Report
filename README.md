# 🚗 USA Cars Price Prediction Using Machine Learning

This project uses various machine learning models to predict car prices based on features like brand, year, mileage, and condition from the `USA_Cars.csv` dataset.

---

## 📁 Dataset

- **Source:** [USA_Cars.csv](./USA_Cars.csv)
- Contains details such as:
  - Brand
  - Model
  - Year
  - Mileage
  - Condition
  - Location
  - Color
  - And more...

---

## 🧠 Models Used

| Model                | Description                            |
|---------------------|----------------------------------------|
| Linear Regression    | Baseline interpretable model           |
| Decision Tree        | Non-linear, interpretable model        |
| K-Nearest Neighbors  | Instance-based simple model            |
| Support Vector Machine | High-dimensional performance         |
| Random Forest        | Ensemble of trees, best performing     |

---

## 🛠️ Tools & Libraries

- Python 🐍
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- SHAP (Model Explainability)

---

## ⚙️ How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/your-username/usa-cars-price-prediction.git
   cd usa-cars-price-prediction
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt

Run the notebook or script:

Jupyter Notebook: USA_Cars_Classification.ipynb

Or use Python scripts (if you have them split).

📊 Features
Preprocessing: Label encoding, scaling, feature selection

GridSearchCV for Random Forest hyperparameter tuning

Model evaluation using:

R² Score

MAE / RMSE

Scatter Plot: Actual vs Predicted

Feature Importance visualization

SHAP Explainability

🏆 Best Model Performance (Random Forest + GridSearch)
Metric	Score
R² Score	0.75
MAE	~4500
RMSE	~6000

🔍 Model Explainability
Using SHAP for:

Feature Importance

Global explanations (summary plot)

Local prediction insights (optional)

📌 Folder Structure
Copy
Edit
├── USA_Cars.csv
├── USA_Cars_Price_Prediction.ipynb
├── README.md
└── requirements.txt
📬 Contact
For any questions or suggestions, feel free to reach out:



### ✅ Optional: `requirements.txt`

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
shap
