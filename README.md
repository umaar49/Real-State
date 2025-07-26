# 🏠 Real Estate Price Prediction

This project focuses on predicting house prices based on multiple property features such as area, number of bedrooms, furnishing status, and more. The analysis includes data preprocessing, exploratory data analysis (EDA), and model training using linear regression with Ridge regularization.

---

## 📂 Project Structure

- `main_notebook.ipynb` – Full Jupyter Notebook with code, EDA, and model
- `dataset.csv` – Dataset used for training the model 
- `README.md` – Project overview and guide

---

## 📊 Dataset Overview

- Size: 545 entries × 13 columns
- Features include:
- Numerical: price, area, bedrooms, bathrooms, stories, parking
  Categorical: mainroad, guestroom, basement, hotwaterheating, airconditioning, prefarea, furnishingstatus

---

##  Data Cleaning & Preprocessing

- Verified no missing or duplicate values
- Identified 7 categorical and 6 numerical features
- Handled outliers using percentile limits (1%–99%) on price and area
- Applied log transformation to normalize price
- Converted yes/no columns to binary (1/0)
- Applied one-hot encoding to furnishingstatus
- Standardized numerical features using StandardScaler

---
## 📊 Exploratory Data Analysis (EDA)

- 🏷️ Visualized distribution of price and log(price)
- 📈 Boxplots to detect outliers in all numerical features
- 🧮 Count plots for all categorical features with frequency labels
- 📊 Scatter plots for features vs. log(price)
- 📦 Box plots comparing categorical variables with house price

---

## 🧠 Model Used

- **Model:** Ridge
- **Target:** Loan Status
- **Accuracy:** ~72% on test set

---

## 🛠️ Tools & Technologies

- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook
- Scikit-learn
- Random Forest Classifier

## 📌 Key Learning Outcomes

- Cleaning and preparing real-world tabular data
- Handling categorical and numerical features effectively
- Outlier detection and log transformation
- Building and evaluating a regression model
- Understanding the impact of home features on price

---

## 📫 Contact

**Muhammad Umar Saleem**  
Electrical Engineering Graduate (June 2025)  
Aspiring Data Scientist | ML Enthusiast  
