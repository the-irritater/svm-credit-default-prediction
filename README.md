# Credit Card Default Prediction using SVM

## 📌 Project Overview
This project builds a machine learning model using **Support Vector Machine (SVM)** to predict whether a customer will default on their credit card payment. The project demonstrates a complete ML pipeline including data preprocessing, class balancing, feature encoding, model training, hyperparameter tuning, and dimensionality reduction using PCA.

---

## 📊 Dataset
Source: UCI Credit Card Default Dataset  
Target Variable: `DEFAULT`  
- 0 → Did Not Default  
- 1 → Defaulted  

---

## ⚙️ Workflow

### 1. Data Cleaning
- Removed invalid values from categorical columns
- Dropped non-informative `ID` column
- Renamed target variable

### 2. Exploratory Data Analysis
- Class imbalance visualization
- Distribution analysis

### 3. Data Balancing
- Downsampling to balance default and non-default classes

### 4. Feature Engineering
- One-Hot Encoding of categorical variables
- Feature scaling

### 5. Model Building
- Support Vector Machine (SVM)
- Baseline model training
- Accuracy evaluation

### 6. Model Optimization
- Hyperparameter tuning using GridSearchCV
- Optimized `C`, `gamma`, and kernel

### 7. Evaluation
- Confusion Matrix
- Accuracy score
- Performance interpretation

### 8. PCA (Dimensionality Reduction)
- Scree plot analysis
- Decision boundary visualization in 2D PCA space

---

## 🧪 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📈 Results
- Balanced dataset improves model learning
- SVM achieves stable classification performance
- PCA visualization helps interpret decision boundaries
- Model demonstrates strong separation between defaulters and non-defaulters
 
