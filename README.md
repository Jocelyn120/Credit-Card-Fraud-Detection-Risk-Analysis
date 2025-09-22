# Credit-Card-Fraud-Detection-Risk-Analysis
This project analyzes credit card transactions to detect fraudulent activity using SQL and Tableau. Through data exploration and interactive dashboards, it uncovers key transaction patterns, compares fraud vs. non-fraud behavior, and highlights fraud risk with KPIs and insights that help financial institutions reduce losses and protect customers.

## Dataset used
<a href= "https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud">Dataset</a>
- The dataset contains 284,807 transactions over 2 days (September 2013)
- The variable is Class → 0 = Non-fraud, 1 = Fraud

## Key Insight
<img width="1499" height="1199" alt="Dashboard 1 (1)" src="https://github.com/user-attachments/assets/7c94ac28-5013-4db8-9d81-7dc42fb95533" />

- Overall Fraud Risk
Fraud is rare (0.17%) but critical , even though the percentage is small, the potential financial loss per fraud case is high than regular transactions.
- Top 10 Fraud Cases
High-value fraud cases are spread across the timeline, suggesting attempts at different times instead of clustering at one point.
- Fraud vs. Non-Fraud Transaction Amounts
Average fraudulent transactions are significantly higher in amount than non-fraudulent ones,
Fraud = high-value spending, while most genuine users transact in lower amounts.
- Fraud Over Time
1. Hour Ranges 10–12: Sharp Spike in Fraud Count
• Fraud Count jumps up to 40+ in Hour Range 11 (potentially on 11:00–11:59 midday)
•	But the total transactions are not the highest here.
•	Insight: High fraud density despite average transaction volume = red flag.
2. Hour Ranges 25–27: Another Sudden Fraud Increase
•	Another spike in fraudulent activity, around Hour 26 (after midnight)
• Total transaction volume is moderate, but fraud spikes.
•	Insight: These hours may be targeted times for attacks, possibly due to less monitoring or human oversight.
3. Fraud Doesn’t Follow Volume
•	High transaction volume (around ranges 20–23 and 35–39) doesn’t always mean high fraud.
•	Fraudsters may exploit “quiet times” where total volume is low-to-average.




