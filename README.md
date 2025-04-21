# 📊 Chi-Square Test of Independence

## 🔍 Project Overview
This notebook demonstrates the application of the **Chi-Square Test of Independence** using a real-world marketing scenario. A dog food company has introduced new, unique packaging and wants to test whether the **perceived uniqueness** of the packaging is associated with the **purchase likelihood** among customers.

## 🧪 Statistical Objective
To test the **independence between two categorical variables**:
- **Uniqueness of Packaging** (as rated by customers)
- **Purchase Likelihood** (how likely customers are to buy the product)

The goal is to determine if there's a statistically significant relationship between the two variables using a **Chi-Square Test of Independence**.

## 📁 Dataset
The analysis uses a dataset named:

It contains survey data on customer perceptions of packaging uniqueness and purchase likelihood.

## 📌 Key Steps
- Data loading and preprocessing using `pandas`
- Cross-tabulation of categorical variables
- Sorting categorical values for better visual interpretation
- Performing the **Chi-Square Test** using `scipy.stats.chi2_contingency`
- Interpretation of results based on p-value

## 📚 Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `scipy`

## 📈 Output
The output includes:
- Contingency table of observed frequencies
- Expected frequencies under independence
- Chi-square statistic, degrees of freedom, and p-value
- Interpretation of statistical significance

## 🧠 Conclusion
Based on the p-value and the test statistic, we interpret whether the uniqueness of the packaging has a statistically significant association with purchase likelihood.
