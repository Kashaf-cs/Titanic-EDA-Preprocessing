<div align="center">

# 🚢 Titanic Dataset — Data Preprocessing & EDA

### Exploratory Data Analysis, Cleaning, and Feature Engineering on the Titanic Passenger Dataset

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)](https://seaborn.pydata.org)

</div>

---

## 📌 Overview

This project is a complete **Data Preprocessing and Exploratory Data
Analysis (EDA)** workflow on the classic **Titanic dataset**.

The goal wasn't to build a model — it was to understand the data first:
clean it, explore it, and prepare it so any model trained on it would
actually learn something meaningful.

> **"Before the model, there's the mess."**

---

## 🎯 Key Steps & Workflow

* **Data Inspection:** Inspecting dataset structure, summary statistics, data types, and missing values.
* **Missing Value Treatment:** Handling missing values in `Age` using the median and `Embarked` using the mode, while evaluating columns with a high percentage of missing values such as `Cabin`.
* **Exploratory Data Analysis (EDA):** Analyzing survival patterns across `Sex` and `Pclass`, along with the distributions of `Age` and `Fare`.
* **Categorical Encoding:** Converting categorical features such as `Sex` and `Embarked` into numerical representations for machine learning.
* **Feature Engineering:** Creating derived features such as `FamilySize` by combining `SibSp` and `Parch`.

## 📂 Project Structure

```text
EDA and Data Preprocessing in Titanic Dataset/
│
├── .gitignore
├── EDA and Data Preprocessing.ipynb
├── README.md
└── requirements.txt



## 🛠️ Tech Stack

* **Language:** Python 3.10+
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* **Environment:** Visual Studio Code / Jupyter Notebook
* **Version Control:** Git & GitHub

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Kashaf-cs/Titanic-EDA-Preprocessing.git
cd Titanic-EDA-Preprocessing
```

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

Open `EDA and Data Preprocessing.ipynb` in VS Code or Jupyter Notebook and run the cells sequentially.

## 📜 License

This project is distributed under the MIT License.

## 👩‍💻 Connect With Me

<div align="center">

**Kashaf Rasheed** — BS Computer Science, LCWU '28

[![GitHub](https://img.shields.io/badge/GitHub-Kashaf--cs-181717?style=for-the-badge&logo=github)](https://github.com/Kashaf-cs)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/kashaf-rasheed-694a11416/)

⭐ **If you found this useful, drop a star!**

</div>