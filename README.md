# Predictive Analysis of Productivity Loss using Machine Learning

This project uses **Machine Learning** to analyze and predict productivity loss based on common workplace time wasters. It aims to help organizations identify which factors contribute most to productivity decline by training and evaluating predictive models on real-world behavioral data.

---

## Objective

To build a machine learning model that predicts productivity loss using features like time spent on social media, number of meetings, break time, etc., while demonstrating:

- ✅ Feature selection techniques
- ✅ Model training and validation
- ✅ Performance evaluation

---

## Tools & Technologies

- Python 3.x
- Pandas & NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## Dataset Overview

**File:** `TimeWasters.csv`  
This dataset contains behavioral and environmental factors that may influence productivity at work.

### Sample Features:
- `social_media_time` – Time spent on social media (minutes)
- `meetings_count` – Number of meetings attended
- `break_time` – Total break time (minutes)
- `multitasking` – Boolean indicating multitasking during work
- `noise_level` – Self-reported noise in the environment
- `ProductivityLoss` – Target variable (e.g., hours lost or productivity score)

---

## 🔍 Project Workflow

### 1️⃣ Data Preprocessing
- Missing value handling
- Encoding categorical variables
- Feature scaling (if needed)

### 2️⃣ Feature Selection
- Correlation heatmap
- Feature importance from models (e.g., Random Forest)

### 3️⃣ Model Training
- Classification or regression models (e.g., RandomForest, LinearRegression)
- Train-test split for evaluation

### 4️⃣ Model Evaluation
- For classification: Accuracy, confusion matrix, precision/recall
- For regression: RMSE, R² score

### 5️⃣ Insights & Interpretation
- Identified most impactful features
- Discussed model performance and practical usage
