# Customer Churn Prediction

## Description
This project aims to predict **customer churn** for a telecommunications company using historical data. Five supervised models were implemented:

- Logistic Regression
- Random Forest
- XGBoost
- LightGBM
- Simple Neural Network

The workflow includes **data preprocessing**, **feature engineering**, **categorical encoding**, and **class balancing** to optimize model performance.

---

## Project Structure
customer-churn-prediction/

|

├─ README.md

├─ customer_churn_prediction.ipynb

├─ data/

├─ requirements.txt

└─ .gitignore

---

## Dataset
The data comes from a fictional telecommunications customer dataset, including:

- Personal customer information
- Contract and subscribed services
- Churn history

---

## Usage

1. Clone the repository:
git clone https://github.com/JoshuaDC21/customer-churn-prediction

2. Create a virtual environment and install dependencies:
python -m venv env
source env/bin/activate # Linux/Mac
env\Scripts\activate # Windows
pip install -r requirements.txt


3. Run the main notebook:
jupyter notebook customer_churn_prediction.ipynb


---

## Results
- **Best performance:** XGBoost (AUC-ROC = 0.8916)
- **Fastest model:** Logistic Regression (0.014s)
- **Balanced performance/time:** LightGBM

The results include metric tables (AUC-ROC, Accuracy) and feature importance visualizations.

---

## License
MIT License
