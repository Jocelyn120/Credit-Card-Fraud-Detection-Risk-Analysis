# Credit-Card-Fraud-Detection-Risk-Analysis
This project analyzes credit card transactions to detect fraudulent activity using SQL and Tableau. Through data exploration and interactive dashboards, it uncovers key transaction patterns, compares fraud vs. non-fraud behavior, and highlights fraud risk with KPIs and insights that help financial institutions reduce losses and protect customers.

## Dataset used
<a href= "https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud">Dataset</a>
- The dataset contains 284,807 transactions over 2 days (September 2013)
- The variable is Class → 0 = Non-fraud, 1 = Fraud

## Key Insight
<img width="1499" height="1199" alt="Dashboard 1 (1)" src="https://github.com/user-attachments/assets/7c94ac28-5013-4db8-9d81-7dc42fb95533" />

- Fraud is rare (0.17%) but critical ,  the potential financial loss per fraud case is high
- High-value fraud cases are spread across the timeline, suggesting attempts at different times instead of clustering at one point
- Average fraudulent transactions are significantly higher in amount than non-fraudulent ones
- High fraud density despite average transaction volume = red flag
- Hour 26 (after midnight) may be targeted times for attacks, possibly due to less monitoring or human oversight
- High transaction volume (around ranges 20–23 and 35–39) doesn’t always mean high fraud, Fraudsters may exploit “quiet times” where total volume is low-to-average




