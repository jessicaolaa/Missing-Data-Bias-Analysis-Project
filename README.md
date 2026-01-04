# Missing-Data-Bias-Analysis-Project
Missing Data & Bias in Healthcare Data

📌 Project Overview

This project explores missing data patterns in a healthcare dataset and assesses whether missingness is associated with clinical outcomes. The aim is to demonstrate how non-random missing data can introduce bias into healthcare analytics and machine learning models if not properly addressed.

🏥 Why This Matters

In real-world healthcare and pharmaceutical research, datasets often contain missing values due to incomplete records, variations in clinical practice, or patient follow-up. If missing data is ignored or handled incorrectly, it can bias conclusions related to disease outcomes, treatment effectiveness, and patient safety.

Understanding missing data mechanisms is therefore essential for responsible and ethical data science.

📊 Dataset

Breast Cancer Wisconsin (Diagnostic) dataset (via scikit-learn)

Contains clinical features derived from tumour measurements

Binary outcome: malignant vs benign

Missing values were intentionally introduced in a controlled manner to simulate real-world healthcare data challenges

🔍 Analysis Performed

Quantified missing data at feature level

Visualised missingness patterns

Created a missingness indicator variable

Compared clinical outcomes between patients with and without missing data

Performed a simple statistical test to assess whether missingness was associated with outcomes

🧠 Key Findings

Missing data was not randomly distributed

Patients with missing values showed different outcome patterns

Removing missing data without investigation could bias downstream analyses or models

⚠️ Implications for Data Science & AI

Missing data should be assessed before applying machine learning models

Non-random missingness can introduce bias into predictions

Responsible data science in healthcare requires transparency, validation, and mitigation strategies such as imputation or sensitivity analysis
