# Titanic Dataset Exploratory Data Analysis (EDA)

This project performs an **Exploratory Data Analysis (EDA)** on the Titanic dataset from Kaggle.  
The goal is to explore the dataset, understand relationships between features, and identify patterns that may influence survival outcomes.  

---

## 📊 Steps Performed

1. **Summary Statistics**
   - Checked dataset shape, data types, and missing values.
   - Generated descriptive statistics for numerical and categorical features.

2. **Data Visualization**
   - **Histograms** to understand feature distributions.
   - **Boxplots** to detect outliers in numerical features.

3. **Feature Relationships**
   - **Correlation matrix heatmap** to examine relationships among numeric features.
   - **Pairplot** to visualize interactions between Age, Fare, Pclass, and Survived.

4. **Patterns & Trends**
   - Analyzed survival rate by **Sex** and **Pclass**.
   - Observed distribution of Age and Fare in relation to survival.

5. **Key Inferences**
   - Females had a much higher survival rate compared to males.
   - Passengers in **1st Class** had significantly better survival chances than those in **3rd Class**.
   - **Fare** is right-skewed (a few passengers paid very high fares).
   - **Pclass** is negatively correlated with Fare and Survived.

---

## 📂 Files in this Repository

-  `titanic_eda.ipynb` → upyter Notebook script for analysis.  
- `train.csv` → Titanic dataset from [Kaggle Titanic Challenge](https://www.kaggle.com/c/titanic/data).  
- `README.md` → This documentation.  

---

## ⚙️ Requirements

Install the following Python libraries before running the script:

```bash
pip install pandas numpy matplotlib seaborn
