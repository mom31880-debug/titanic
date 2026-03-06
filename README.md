# 🚢 Titanic EDA

Exploratory Data Analysis on the Titanic dataset to understand what factors influenced passenger survival.

---

## 📁 Dataset
- **Source:** [Kaggle - Titanic Competition](https://www.kaggle.com/c/titanic)
- **Size:** 891 rows × 12 columns

---

## 🛠️ Tools Used
- `Python`
- `Pandas` — data manipulation
- `Matplotlib` / `Seaborn` — visualization

---

## 🧹 Data Cleaning
- **Age** → filled missing values with median
- **Embarked** → filled missing values with mode
- **Cabin** → dropped (77% missing)
- Dropped irrelevant columns: `PassengerId`, `Name`, `Ticket`

---

## 📊 Visualizations
- Overall Survival Rate
- Survival by Gender
- Survival by Class
- Age Distribution by Survival
- Fare Distribution by Survival
- Correlation Heatmap

---

## 🔍 Key Findings
- Overall survival rate: **38.4%**
- **Females** had a much higher survival rate than males
- **1st class** passengers survived more than 2nd and 3rd class
- **Children** had a higher survival rate than adults
- Gender and Class were the strongest survival factors

---

## 🚀 How to Run
```bash
pip install pandas matplotlib seaborn
jupyter notebook Task_2.ipynb
```
