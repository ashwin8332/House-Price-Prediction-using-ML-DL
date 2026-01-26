# 🏡 SCT_WD_1 – House Price Prediction using ML & DL

This project implements a **Machine Learning and Deep Learning based house price prediction system** using the **Kaggle House Prices: Advanced Regression Techniques** dataset.  
The goal is to predict the final **SalePrice** of houses based on multiple numerical and categorical features.

🔗 Kaggle Profile: https://www.kaggle.com/ashwin832  
🔗 Competition Link: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

---

## 📌 Project Overview

House price prediction is a classic **regression problem** in machine learning.  
In this project, various preprocessing, feature engineering, and regression techniques are applied to build a robust predictive model.  
The trained model is saved and later used to generate predictions on unseen test data.

---

## 📂 Repository Structure

```text
SCT_WD_1-house_prediction_BY-ML-DL/
│
├── House_prediction_trainig.ipynb    # Data preprocessing & model training
├── House_prediction_test.ipynb       # Model loading & prediction
├── finalized_model.pkl               # Trained ML model
│
├── train.csv                         # Training dataset
├── test.csv                          # Test dataset
├── formulatedtest.csv                # Processed test data
├── sample_submission.csv             # Kaggle submission format
│
└── README.md                         # Project documentation
```
---

## 📊 Dataset Description

The dataset is provided by Kaggle and contains **residential housing data from Ames, Iowa**.

- **Train data (`train.csv`)**
  - Contains input features and the target variable `SalePrice`
- **Test data (`test.csv`)**
  - Contains input features only (used for prediction)

### Example Features:
- `OverallQual` – Overall material and finish quality
- `GrLivArea` – Above ground living area (sq ft)
- `YearBuilt` – Original construction year
- `TotalBsmtSF` – Total basement area
- `Neighborhood` – Physical location within the city

---

## ⚙️ Technologies & Libraries Used

- **Programming Language:** Python  
- **Environment:** Jupyter Notebook  

### Libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- pickle

---

## 🔄 Project Workflow

1. **Data Loading**
   - Load training and testing datasets
2. **Exploratory Data Analysis (EDA)**
   - Understand feature distributions and correlations
3. **Data Preprocessing**
   - Handle missing values
   - Encode categorical variables
   - Feature scaling
4. **Model Training**
   - Train regression models using ML algorithms
5. **Model Saving**
   - Save the trained model as `finalized_model.pkl`
6. **Prediction**
   - Load the trained model and generate predictions on test data
7. **Submission Preparation**
   - Create prediction file in Kaggle submission format

---

## 📈 Model Output

- The trained model predicts house prices with minimized error.
- Predictions are saved in a CSV file compatible with Kaggle submission guidelines.

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/SCT_WD_1-house_prediction_BY-ML-DL.git
Open Jupyter Notebook:

bash
Copy code
jupyter notebook
Run:

House_prediction_trainig.ipynb to train the model

House_prediction_test.ipynb to generate predictions

🎯 Results & Evaluation
Model performance is evaluated using regression metrics such as:

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

Feature engineering and preprocessing significantly improve prediction accuracy.

📌 Future Improvements
Apply advanced ensemble models (XGBoost, LightGBM)

Hyperparameter tuning

Deep learning regression using neural networks

Feature importance visualization

**🙌 Acknowledgements**
Kaggle for providing the dataset and competition

**Scikit-learn documentation and open-source community**
