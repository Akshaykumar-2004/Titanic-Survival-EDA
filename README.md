# Titanic Disaster Exploratory Data Analysis (EDA)

## 📌 Overview

This project explores the **Titanic - Machine Learning from Disaster** dataset to uncover survival patterns. By applying Exploratory Data Analysis (EDA) techniques, we aim to identify factors that influenced survival during the Titanic tragedy.

## 🎯 Goals

* Load and inspect the dataset
* Clean missing and inconsistent data
* Perform feature engineering
* Visualize survival patterns
* Summarize insights with clear evidence

## 🛠️ Tools & Libraries

* **Python** (programming language)
* **Pandas** (data manipulation)
* **NumPy** (numerical operations)
* **Matplotlib** (data visualization)

## 📂 Dataset

Dataset: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)
Format: CSV file (`titanic.csv`)

## 🚀 Steps Performed

1. **Data Loading** – Imported dataset into Pandas DataFrame.
2. **Initial Exploration** – Used `.head()`, `.info()`, `.describe()`, `.shape()` to understand structure.
3. **Data Cleaning** –

   * Filled missing ages with median.
   * Dropped Cabin column (too many missing values).
   * Filled missing Embarked values with mode.
4. **Feature Engineering** – Created `FamilySize` from SibSp and Parch.
5. **Data Visualization** –

   * Survival counts overall
   * Survival by gender
   * Survival by passenger class
   * Survival by age distribution

## 📊 Key Findings

* **Passenger Class:** First-class passengers had higher survival chances.
* **Gender:** Females survived at much higher rates than males.
* **Age:** Very young children had higher survival rates.
* **Overall:** Survival was not random; social and demographic factors played a major role.

## 📜 Conclusion

This project shows the full workflow of EDA: from raw dataset → cleaning → feature engineering → visualization → insights. It demonstrates how data analysis can uncover hidden stories within datasets.

## 🖥️ How to Run

1. Clone this repository or download project files.
2. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib
   ```
3. Run the Jupyter Notebook / Google Colab file.
4. Upload `titanic.csv` dataset into your working environment.

---
