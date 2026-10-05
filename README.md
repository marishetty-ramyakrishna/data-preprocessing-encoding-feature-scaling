# Data Preprocessing: Encoding & Feature Scaling

## 📌 Overview

Data preprocessing is an important step in the machine learning workflow. Raw datasets often contain categorical variables and features with different numerical ranges, which can affect how machine learning algorithms process the data.

This repository accompanies the article **"Data Preprocessing: Encoding & Feature Scaling"** and focuses on preparing data for machine learning through encoding and feature scaling techniques.

## 📚 Topics Covered

* Data preprocessing
* Categorical data
* Encoding categorical features
* Numerical feature transformation
* Feature scaling
* Preparing datasets for machine learning

## 🔤 Encoding Categorical Data

Machine learning algorithms generally require numerical input. When a dataset contains categorical values such as city names, these categories need to be transformed into numerical representations.

For example:

```text
City
Chennai
Delhi
Hyderabad
```

Categorical encoding converts these values into a numerical representation that can be processed by machine learning algorithms.

## 📏 Feature Scaling

Different numerical features can have very different ranges.

For example:

```text
Age       → 22, 25, 30, 35
Salary    → 25000, 40000, 60000, 59000
```

Feature scaling transforms numerical features into comparable ranges.

This can be particularly important for machine learning algorithms that are sensitive to the scale of input features.

## 🧩 Why Preprocessing Matters

A well-prepared dataset can help machine learning algorithms work more effectively.

The preprocessing workflow can include:

```text
Raw Data
   ↓
Data Preprocessing
   ↓
Categorical Encoding
   ↓
Feature Scaling
   ↓
Machine Learning Model
```

## 🛠️ Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Machine Learning


## 🎯 Learning Objective

The objective of this repository is to demonstrate how raw data can be prepared for machine learning by handling categorical variables and scaling numerical features.

## 📝 Article

This repository is based on the Medium article:

**Data Preprocessing: Encoding & Feature Scaling**

## 👩‍💻 Author

**Marishetty Ramyakrishna**

---

⭐ If you found this repository useful, consider giving it a star!
