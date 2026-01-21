## Feature Encoding & Scaling (Adult Income Dataset)

---

## 📌 Project Overview
This repository contains **Task 4** of the AI & ML Internship, which focuses on **feature engineering** techniques.  
The main goal of this task is to preprocess the **Adult Income Dataset** by applying appropriate **feature encoding** and **feature scaling** methods to make the data ready for machine learning models.

---

## 🎯 Objective
- Identify categorical and numerical features
- Apply **Label Encoding** where order exists
- Apply **One-Hot Encoding** where no order exists
- Scale numerical features using **StandardScaler**
- Save the final preprocessed dataset
- Understand the impact of encoding and scaling on ML algorithms

---

## 📂 Dataset Used
**Adult Income Dataset**

The dataset contains demographic and employment-related attributes such as:
- Age
- Education
- Occupation
- Workclass
- Hours per week  

**Target Variable:**
- `income` → predicts whether income is `<=50K` or `>50K`

---

## 🛠 Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔍 Task Workflow

### 1️⃣ Feature Identification
- **Numerical Features:**  
  Age, education-num, capital-gain, capital-loss, hours-per-week  
- **Categorical Features:**  
  Workclass, education, marital-status, occupation, relationship, race, sex, native-country

---

### 2️⃣ Label Encoding
- Applied to **ordered or binary features**
- Used for the target variable `income`
- Converts categories into numeric values while preserving order

**Reason:**  
Machine learning models require numeric input.

---

### 3️⃣ One-Hot Encoding
- Applied to **unordered categorical features**
- Converts each category into a separate binary column

**Reason:**  
Prevents the model from assuming incorrect ordinal relationships between categories.

---

### 4️⃣ Feature Scaling
- Numerical features are scaled using **StandardScaler**
- Standardization ensures:
  - Mean = 0
  - Standard Deviation = 1

**Reason:**  
Improves model performance and is essential for distance-based algorithms.

---

### 5️⃣ Before vs After Scaling
- **Before scaling:** Numerical features had different ranges
- **After scaling:** All numerical features are on a similar scale, improving learning efficiency

---

### 6️⃣ Saving the Processed Dataset
- The final preprocessed dataset is saved as:
