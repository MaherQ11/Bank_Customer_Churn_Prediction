# Bank Customer Churn Analysis 🏦

## Project Overview
SQL-based analysis of 10,000 bank customers to identify churn patterns and high-risk segments. Built using Python and SQLite, with findings that directly support customer retention strategies.

## Dataset
- **Source:** Kaggle — Bank Customer Churn Prediction
- **Size:** 10,000 customers, 12 features
- **Key columns:** credit_score, country, gender, age, balance, products_number, churn

## Tools Used
- Python (Pandas, SQLite3)
- SQL (SQLite)
- Jupyter Notebook

## Key Findings

| Insight | Finding |
|---|---|
| Overall churn rate | 20.37% |
| Highest churn by country | Germany (32.44%) |
| Highest churn by gender | Female (25.07%) |
| Safest product segment | 2 products (7.58% churn) |
| Riskiest product segment | 4 products (100% churn) |
| Highest risk age group | 51-60 years (56.21%) |
| High-value customers churned | 1,426 (avg balance: $125K) |

## Business Recommendations
1. **Focus retention efforts on Germany** — churn rate double France and Spain
2. **Target female customers** with loyalty programs — 25% churn vs 16% for males
3. **Flag customers with 3-4 products** — extremely high churn risk
4. **Prioritize age group 51-60** — over half leave the bank
5. **High-balance customers need attention** — 1,426 high-value customers churned

## Project Structure
```
bank-churn-analysis/
│
├── Bank_Customer_Churn_Prediction.csv
├── bank_churn.db
├── bank_churn_analysis.ipynb
├── findings.md
└── README.md
```

## How to Run
```python
# Install dependencies
pip install pandas jupyter

# Open notebook
jupyter notebook bank_churn_analysis.ipynb
```

## Author
**Maher Al-Qurashi**  
github.com/MaherQ11 | linkedin.com/in/maher-al-qurashi-69a163351

## Dashboard Preview
![Bank Customer Churn Dashboard](<img width="1150" height="643" alt="BankDashBoard" src="https://github.com/user-attachments/assets/c889fab9-18b2-4f64-a585-ddd734943513" />
)
