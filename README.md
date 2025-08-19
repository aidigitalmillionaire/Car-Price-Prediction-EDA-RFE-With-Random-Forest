# Car-Price-Prediction-EDA-RFE-With-Random-Forest

# 🚗 Car Price Prediction (EDA + RFE + Random Forest)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1xkUT8uhnoUIIaM_FNUZIoJDumygeQaXE?usp=sharing)

This project builds a **Car Price Prediction model** using **Exploratory Data Analysis (EDA)**, **Recursive Feature Elimination (RFE)**, and **Random Forest Regression**.  
It is fully developed and deployed in **Google Colab** for reproducibility.

👉 **Project Description:** See [docs/DESCRIPTION.md](docs/DESCRIPTION.md)

---

## 📊 Features
- Clean and documented Colab notebook
- Exploratory Data Analysis (EDA) with insights and visualizations
- Feature selection with **RFE** to identify important predictors
- Model training using **Random Forest Regressor**
- Evaluation with R², MAE, MSE, and RMSE
- Ready-to-run in Google Colab (no setup needed)

---

## 📂 Project Structure

car-price-prediction/

├─ notebook/

│ └─ car_price_prediction.ipynb

├─ docs/

│ └─ DESCRIPTION.md

├─ README.md

├─ requirements.txt

└─ .gitignore


---

## 📊 Dataset
- The dataset contains **car attributes** such as `year`, `mileage`, `engine size`, `fuel type`, etc.  
- Target variable: **Price** of the car.  
- Data should be uploaded to Colab or linked from a dataset repository (e.g., Kaggle).  
- Example dataset: [Kaggle - Car Price Prediction]([(https://drive.google.com/drive/folders/1Cp70OsspMBAPGrgnF-m4AsRGvmkKetwy?usp=sharing)])

---

## ⚡ How to Run

1. Open the notebook in Colab:  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1xkUT8uhnoUIIaM_FNUZIoJDumygeQaXE?usp=sharing)

2. Install dependencies (if running locally):
   ```bash
   pip install -r requirements.txt
