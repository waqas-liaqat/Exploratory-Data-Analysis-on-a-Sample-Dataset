# Exploratory Data Analysis (EDA) on the Titanic Dataset

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Titanic dataset**, a well-known dataset used for data science and machine learning. The goal is to analyze the dataset to uncover patterns, distributions, and relationships between different features. This analysis includes handling missing values, visualizing key insights, and identifying trends in survival rates based on various factors.

## 📂 Dataset Information
- The dataset contains information about **passengers aboard the Titanic**, including age, gender, ticket class, fare, and whether they survived or not.
- **Source**: The dataset is publicly available on [Kaggle](https://www.kaggle.com/competitions/titanic/data) and other repositories.

## 🛠️ Technologies Used
- **Python** (pandas, numpy, matplotlib, seaborn)
- **Jupyter Notebook** (for analysis and visualization)
- **GitHub** (for project version control)

## 📊 Analysis & Findings
### 1️⃣ Data Cleaning & Preprocessing
- Identified **missing values** in 'Age', 'Cabin', and 'Embarked' columns.
- Replaced missing **'Age'** values with the **median age**.
- Dropped the **'Cabin'** column due to excessive missing values.
- Dropped rows with missing **'Embarked'** values.

### 2️⃣ Data Exploration
- Summary statistics and data types were explored using `df.describe()` and `df.info()`.
- Checked for missing values and handled them appropriately.

### 3️⃣ Data Visualization & Insights
- **Survival Rate**: Only **38%** of passengers survived.
- **Gender Analysis**: **Females had a significantly higher survival rate** compared to males.
- **Class Influence**: **First-class passengers had a much higher survival rate** than those in second and third class.
- **Age Factor**: **Children (younger passengers) had higher survival rates**.
- **Fare Relationship**: **Higher fare-paying passengers had a better chance of survival**.
- **Embarkation Point**: **Passengers from Cherbourg had a higher survival rate**.

## 📌 Visualizations Included
- **Histogram of Age & Fare distribution**
- **Passenger count by class & survival count**
- **Correlation heatmap**
- **Survival rate by gender, class, and embarkation point**
- **Boxplot of Fare by Survival**

## 🔥 Next Steps & Enhancements
- Perform **feature engineering** to create new insights.

- Build a **predictive model** (Logistic Regression or Decision Trees) for survival prediction.

- Deploy results using **Tableau or Power BI dashboards**.

## 📜 How to Use This Repository
1. Clone the repository:
   ```bash
   git clone https://github.com/waqas-liaqat/Exploratory-Data-Analysis-on-a-Sample-Dataset.git
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Titanic_EDA.ipynb
   ```

## 📌 Author
- **Muhammad Waqas**  
- 📧 Contact: [waqasliaqat630@gmail.com](mailto:waqasliaqat630@gmail.com)
- 🌐 [LinkedIn](https://www.linkedin.com/in/muhammad-waqas-liaqat/)  

---

Feel free to contribute to this project or reach out with any suggestions! 🚀