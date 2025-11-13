# 🏡 Bengaluru House Price Prediction

**Tools Used:** Python · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn  
**Skills Demonstrated:** Data Cleaning · Feature Engineering · Model Training · Regression Analysis · Price Prediction  

---

## 📌 Project Overview

This project focuses on predicting house prices in **Bengaluru** using **Machine Learning**.  
The goal is to build an accurate model that can estimate property prices based on various features such as location, area, number of bedrooms, and other attributes.

This project was part of my ML learning journey inspired by **Akarsh Vyas sir’s course**, where I practiced building end-to-end regression models on real-world datasets.

---

## 🧠 Project Workflow

### 1. 🧹 Data Cleaning & Preprocessing
- Removed duplicates and handled missing values  
- Standardized inconsistent entries (e.g., square feet formats, price ranges)  
- Removed outliers and unrealistic data points  
- Encoded categorical variables like `location` for model compatibility  

### 2. ⚙️ Feature Engineering
- Created new numerical features from text-based data  
- Normalized and standardized numerical columns  
- Reduced dimensionality by grouping rare locations  
- Improved data quality for model interpretability  

### 3. 🤖 Model Training & Evaluation
Trained multiple regression models and tuned hyperparameters using **GridSearchCV**.

| Model | Best R² Score | Best Parameters |
|:------|:--------------|:----------------|
| Linear Regression | **0.853** | `{}` |
| Lasso Regression | 0.728 | `{'alpha': 1, 'selection': 'random'}` |
| Decision Tree | 0.692 | `{'criterion': 'squared_error', 'splitter': 'best'}` |

✅ **Best Model:** *Linear Regression* achieved the highest R² score (0.85), showing strong generalization and stable predictions.

---

**Key Insights:**
- 📌 Location has the strongest influence on price.  
- 🏠 3 BHK properties show the most balanced value across regions.  
- 💰 Premium localities show high outliers, indicating luxury property clusters.  

---

## 💡 Skills Demonstrated

- **Data Cleaning:** Removed outliers, nulls, and inconsistent data entries.  
- **Feature Engineering:** Transformed text and categorical data into numeric features.  
- **Model Building:** Applied and compared multiple regression models.  
- **Hyperparameter Tuning:** Used GridSearchCV to find optimal model parameters.  
- **Visualization:** Created clear visual insights using Matplotlib and Seaborn.  

---

## 📬 Contact

Let’s connect!  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/tanujkumai/)  
[![Gmail Badge](https://img.shields.io/badge/Email-tanujkumai21%40gmail.com-red?logo=gmail&logoColor=white)](mailto:tanujkumai21@gmail.com)
