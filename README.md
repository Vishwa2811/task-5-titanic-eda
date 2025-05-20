# Task 5: Titanic Exploratory Data Analysis (EDA)

## 🔍 Objective
Perform Exploratory Data Analysis (EDA) on the Titanic dataset to uncover hidden patterns, understand relationships between variables, and extract useful insights that could influence passenger survival outcomes.

## 🛠 Tools Used
- Python
- Jupyter Notebook
- Libraries: Pandas, Matplotlib, Seaborn

## 📂 Files Included
- Titanic_EDA.ipynb – Complete analysis in Jupyter Notebook format

## 📊 Key Steps Performed

- Loaded the Titanic dataset using Pandas and performed initial inspection using functions like .head(), .info(), .describe(), and .value_counts().
- Cleaned the dataset by handling missing values in columns like Age and Embarked. Dropped the Cabin column due to too many nulls.
- Conducted univariate analysis to understand the distribution of variables like Age, Fare, and Pclass using histograms and boxplots.
- Performed bivariate and multivariate analysis to understand how features interact with each other and with the target variable (Survived).
- Used visual tools like:
  - Countplots to analyze survival by gender and class
  - Boxplots to check age distribution across classes and survival
  - Heatmap to visualize correlations between variables
  - Pairplot for multivariate relationships
- Highlighted key patterns and conclusions at the end of the analysis.

## 📈 Observations & Insights

- Female passengers had a much higher survival rate compared to male passengers.
- Passengers in 1st class had better chances of survival than those in 2nd or 3rd class.
- Children and younger passengers had higher chances of survival compared to older individuals.
- Embarked location showed a slight influence on survival, with passengers boarding from Cherbourg having a better survival rate.
- Fare and class were positively correlated with survival.

## ✅ Outcome

- Practiced data cleaning and preprocessing techniques.
- Applied various types of visualizations to understand and communicate findings.
- Learned how to interpret relationships in real-world datasets.
- Gained better understanding of EDA and its importance before applying ML models.

## 📎 Dataset Used
- Titanic Dataset from Kaggle  
  [Link to Dataset](https://www.kaggle.com/c/titanic/data)

## 📚 References

- Kaggle Titanic Dataset: https://www.kaggle.com/c/titanic/data  
- Seaborn Documentation: https://seaborn.pydata.org/  
- Matplotlib Documentation: https://matplotlib.org/  
- ChatGPT: Used to debug and improve parts of the notebook during analysis

---

📌 Note: This task helped improve my understanding of exploratory data analysis using Python. The insights gained here can be useful for building machine learning models in later stages.
