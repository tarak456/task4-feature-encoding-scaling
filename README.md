# Task 4: Feature Encoding and Scaling

## 📌 Overview
This project demonstrates **data preprocessing techniques** used in machine learning, focusing on **feature encoding** and **feature scaling** using the **Adult Income Dataset**.

The goal is to convert categorical and numerical features into a machine-learning-ready format using **scikit-learn** tools.


## 📂 Dataset
- **Dataset Name:** Adult Income Dataset  
- **Source:** UCI Machine Learning Repository  
- **File Used:** `adult.data`

The dataset contains demographic information used to predict whether a person earns more than $50K per year.


## ⚙️ Techniques Used

### 🔹 Feature Encoding
- **OneHotEncoder**  
  Used to convert categorical variables into numerical format.

### 🔹 Feature Scaling
- **StandardScaler**  
  Used to normalize numerical features so they have zero mean and unit variance.

### 🔹 ColumnTransformer
- Applies different transformations to numerical and categorical columns in a single pipeline.


## 🛠 Libraries Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab


## 📊 Workflow
1. Load the Adult dataset
2. Assign column names
3. Separate numerical and categorical features
4. Apply:
   - OneHotEncoding to categorical columns
   - Standard Scaling to numerical columns
5. Combine transformations using ColumnTransformer
6. Generate processed feature matrix


## 🚀 Output
- Successfully transformed dataset ready for machine learning models
- Categorical features encoded
- Numerical features scaled

