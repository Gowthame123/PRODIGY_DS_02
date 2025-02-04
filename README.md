# PRODIGY_DS_02

# Titanic Data Cleaning & Exploratory Data Analysis (EDA) 🚢

## 📌 Project Overview
This project performs **data cleaning and exploratory data analysis (EDA)** on the **Titanic dataset** to understand survival patterns based on different factors like age, gender, class, and fare. The analysis includes data preprocessing, visualizations, and statistical tests to uncover insights.

## 📂 Dataset
The dataset used in this project is from the Titanic Kaggle competition:  
🔗 [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)

### Files Used:
- `train.csv` → Training dataset containing passenger details and survival status.
- `test.csv` → Test dataset for predictions (not used in EDA).
- `gender_submission.csv` → Example submission file for predictions (optional).

## 🔍 Steps Performed
### 1️⃣ Data Cleaning & Preprocessing
- Checked for **missing values** and handled them:
  - Filled `Age` with median.
  - Filled `Embarked` with mode.
  - Dropped `Cabin` due to excessive missing values.
- Converted categorical variables into numerical where necessary.

### 2️⃣ Exploratory Data Analysis (EDA)
- **Visualizations:**
  - Countplot of survival distribution.
  - Survival rate based on **Gender**, **Passenger Class**, **Family Size**, and **Title**.
  - Age & Fare distribution.
  - Correlation heatmap of numerical features.

- **Statistical Tests:**
  - **Chi-Square Test** to check relationships between categorical variables and survival.
  - **T-Test** to compare age distributions of survivors vs. non-survivors.

## 📊 Key Insights
✔ **Women had a higher survival rate** compared to men.
✔ **First-class passengers survived more** than lower classes.
✔ **People with families** had different survival chances.
✔ **Younger passengers had slightly better survival rates.**
✔ **Fare amount influenced survival chances.**

## 🚀 How to Run the Code
### Prerequisites:
Ensure you have Python installed along with the required libraries:
```bash
pip install pandas numpy matplotlib seaborn scipy
```

### Run the Script:
1. Clone this repository:
```bash
git clone https://github.com/your-repo/titanic-eda.git
cd titanic-eda
```
2. Run the Python script:
```bash
python titanic_analysis.py
```

## 🛠 Technologies Used
- **Python** 🐍
- **Pandas & NumPy** (Data manipulation)
- **Matplotlib & Seaborn** (Data visualization)
- **Scipy** (Statistical analysis)

## 📢 Future Work
- Feature Engineering (e.g., combining `SibSp` & `Parch` into `FamilySize`)
- Building a **Machine Learning Model** for survival prediction.
- Deploying a Titanic Survival Predictor using **Streamlit**.

## 📜 License
This project is open-source under the MIT License.

---

**Star ⭐ this repository if you found it useful!** 🚀

