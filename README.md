# 🏥 Medical Appointment No-Show Prediction

## 📌 Overview

Missed medical appointments reduce healthcare efficiency and lead to wasted resources.
This project aims to predict whether a patient will miss their appointment and provide actionable insights to reduce no-show rates.

---

## 🎯 Objectives

* Identify factors associated with missed appointments
* Build a predictive model to detect high-risk patients
* Design a data-driven intervention strategy

---

## 📊 Dataset

The dataset contains patient appointment records, including:

* Demographics (Age, Gender)
* Health conditions (Diabetes, Hypertension, etc.)
* Appointment details (Scheduled date, Appointment date)
* SMS reminder information

---

## 🔍 Key Steps

### 1. Data Preparation

* Handled missing and inconsistent values
* Converted date columns to proper format

### 2. Feature Engineering

* Created **waiting_days** (time between scheduling and appointment)
* Extracted appointment day of week
* Generated weekend indicator

### 3. Modeling

* Applied **Logistic Regression**
* Addressed class imbalance using class weighting

### 4. Evaluation

* Used confusion matrix, precision, recall, and F1-score
* Focused on **recall for no-show cases**

---

## 📈 Key Results

* Recall for no-show prediction improved to **~57%**
* Model successfully identifies a majority of missed appointments
* Trade-off: increased false positives (acceptable for this problem)

---

## 🧠 Insights

* Longer waiting times increase the likelihood of no-shows
* SMS reminders are associated with improved attendance
* Scheduling and behavioral factors are stronger predictors than medical conditions

---

## 🚀 Business Impact

* Enables targeted interventions for high-risk patients
* Reduces missed appointments
* Improves resource utilization in healthcare systems

---

## ⚙️ How to Run

```bash
git clone https://github.com/your-username/no-show-prediction.git
cd no-show-prediction
pip install -r requirements.txt
```

Run the notebook to reproduce results.

---

## 💼 Skills Demonstrated

* Data Cleaning & Preprocessing
* Feature Engineering
* Handling Imbalanced Data
* Logistic Regression Modeling
* Model Evaluation
* Data Visualization
* Business-Oriented Analysis

---

## 📌 Conclusion
This project demonstrates how predictive modeling can be applied to a real-world healthcare problem, enabling data-driven decisions that improve operational efficiency.


