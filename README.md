# 🧠 Support Vector Machines (SVM) - Breast Cancer Classification

## 📌 Project Overview
This project implements **Support Vector Machines (SVM)** for **binary classification** using the **Breast Cancer dataset**.  
The notebook trains both **Linear** and **RBF kernel** SVMs, visualizes decision boundaries (2D), tunes hyperparameters, and evaluates performance.

---

## 🚀 Features
- 📂 Automatic dataset upload (CSV or ZIP)
- 🔍 Automatic target column detection
- 📊 SVM with **Linear** and **RBF** kernels
- 🎨 Decision boundary visualization (first 2 features)
- ⚙ Hyperparameter tuning using **GridSearchCV**
- 📈 Cross-validation score calculation

---

## 📂 Dataset
We use the **Breast Cancer dataset**:

| Feature Example       | Description                    |
|-----------------------|--------------------------------|
| radius_mean           | Mean radius of tumor cells     |
| texture_mean          | Mean texture value             |
| ...                   | ...                            |
| diagnosis (Target)    | Malignant (1) / Benign (0)      |

Dataset file: **`breast-cancer.csv`** (can also be uploaded as ZIP)

---

## 🛠 Installation & Requirements
Make sure you have Python 3 and the following libraries:

```bash
pip install pandas numpy matplotlib scikit-learn
