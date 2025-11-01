
# Fraud-Detection-Analysis
Fraud Detection Analysis Using Python
    The Fraud Transactions Dataset contains key details about user transactions, helping in identifying fraudulent activities and behavioral patterns.
1. Transaction_Amount: Higher transaction amounts may have a higher risk of fraud.
2. Transaction_Type: Some transaction types (like Online Purchases) might be more prone to fraud.
3. Time_of_Transaction: Fraudulent transactions may occur more frequently during odd hours.
4. Device_Used: Fraudsters might prefer mobile transactions over desktop or vice versa.
5. Previous_Fraudulent_Transactions: Users with prior fraud history are more likely to commit fraud again.
6. Account_Age: New accounts may have a higher likelihood of fraudulent activity.
7. Number_of_Transactions_Last_24H: A sudden spike in transaction volume might indicate fraudulent behavior.
8. Payment_Method: Certain payment methods (like UPI or Net Banking) might be more secure than others.
9. Fraudulent: The target variable used to train the fraud detection model.
# Data Insights
1. Approximately 4.92% of transactions are fraudulent.
Online Purchases (5.19%) and POS Payments (5.01%) have the highest fraud rates, while ATM Withdrawals (4.65%) have the lowest.
Bank Transfers and Bill Payments also show high fraud rates, making them potential targets for fraudulent activity.
2. Transaction Amount Analysis
The average transaction amount is 2,547.73
The minimum transaction is 5.03, while the maximum (after handling outliers) is 49997.8.
Fraudulent transactions occur across all price ranges, but the variation in fraud transactions is slightly higher than non-fraud transactions.
3. Time of Transaction & Device Usage
Most fraudulent transactions occur in the evening and night (16:00 - 23:00 hours), suggesting fraudsters exploit non-working hours.
Mobile devices account for a majority of fraud cases, followed by Tablets and Desktops.
4. Location-Based Fraud
Chicago reports higher fraud rates, possibly due to weak verification systems.
5. Account Age & User Behavior
New accounts (age < 30 days) have a significantly higher fraud rate.
Users with multiple past fraudulent transactions continue to exhibit fraud risk.
6. Transaction Frequency
Users making multiple transactions in a short period (within 24 hours) are more likely to be flagged as fraud.
Accounts with more than 10 transactions in the last 24 hours have a higher fraud probability.
7. Payment Method Impact
Credit Cards & UPI transactions have a slightly higher fraud occurrence compared to Debit Cards.
Prepaid cards & anonymous payment methods should be monitored closely for fraud detection.
