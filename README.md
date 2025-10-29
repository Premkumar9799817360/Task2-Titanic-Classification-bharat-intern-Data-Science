# 🚢 Titanic Survival Classification (Bharat Intern)

## 🧠 Project Overview
**Task 2 – Titanic Classification (Bharat Intern - Data Science)**  
The goal of this project is to **predict whether a passenger survived** the Titanic disaster based on various socio-economic and personal features such as **age, gender, and class**.  

This project helped me understand **data preprocessing, feature engineering, model training, and evaluation** in a real-world dataset scenario.

---

## 🕵️‍♂️ Problem Statement
Build a system that determines **whether a person would survive the Titanic sinking** using machine learning models.  
Key factors influencing survival include:
- Socio-economic status (Pclass)
- Age and Gender
- Family relations (SibSp, Parch)
- Fare and Embarked port

---

## ⚙️ Project Workflow

### 🔹 1. Data Preprocessing
- Handled missing values and outliers.  
- Encoded categorical features (like Gender, Embarked).  
- Normalized numerical features using **StandardScaler** for uniform scaling.  

### 🔹 2. Feature Engineering
- Created meaningful features such as **Family Size** and **Title Extraction** from names using regex.  
- Improved prediction quality through data transformation.

### 🔹 3. Model Building
Used multiple machine learning models to classify survival outcomes:
- **Logistic Regression** – baseline model for binary classification.  
- **Decision Tree Classifier** – achieved **77% accuracy**.  
- **Random Forest Classifier** – achieved **81% accuracy**, selected as the **final model** for deployment.  

### 🔹 4. Model Evaluation
- Evaluated performance using **accuracy score** and **ROC-AUC score**.  
- Compared models to determine the most robust and generalizable one.

---

## 🧩 Technologies & Libraries
| Category | Tools / Libraries |
|-----------|-------------------|
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib |
| Modeling | Logistic Regression, Decision Tree, Random Forest |
| Scaling | StandardScaler |
| Evaluation | Accuracy Score, ROC-AUC Score |
| Persistence | Joblib (for saving model and scaler) |

---

## 🎯 Results
| Model | Accuracy |
|--------|-----------|
| Decision Tree | 77% |
| Random Forest | **81%** ✅ |

The **Random Forest Classifier** proved to be the most effective, providing the best balance of performance and reliability for survival prediction.

---

![lIVE DEMO click](https://github.com/Premkumar9799817360/Task2-Titanic-Classification-bharat-intern-Data-Science/assets/83695512/a19d3b94-5822-4205-b529-c8f55a1e60f4)


## 🧾 Conclusion
This project provided hands-on experience in:
- Data preprocessing & feature engineering  
- Training and evaluating ML models  
- Selecting the best-performing model based on accuracy  

The final **Titanic Survival Prediction Model** demonstrates how **machine learning** can uncover real-world insights from historical datasets.

---

## 🎥 Demo (Optional)
If you have a video demo, you can embed it here:

```html






