UPI FRAUD STATISTICAL SIGNALS

Problem Statement
Digital payment platforms process a large number of transactions every day. Statistical analysis can help identify unusual transaction patterns that may indicate fraudulent activity.

Objective
The objective of this project is to analyze UPI transaction data using statistical methods and identify suspicious patterns that may indicate fraud.
Dataset Description
The dataset contains 1,000 UPI transaction records.

The main features used for analysis are:

Transaction_ID
Amount
Transaction_Frequency
Device_Changes
Account_Age_Days
Fraud
Fraud = 0 represents a normal transaction. Fraud = 1 represents a fraudulent transaction.
Statistical Analysis
Descriptive statistical methods were used to understand the transaction data.

Key findings:

Total transactions: 1,000
Fraud transactions: 95
Fraud percentage: 9.5%
Average transaction amount: ₹24,592
Average amount for normal transactions: ₹24,371
Average amount for fraudulent transactions: ₹26,702
The analysis also used mean, frequency comparison, distribution analysis, and IQR-based outlier detection.
Outlier Detection
The Interquartile Range (IQR) method was used to detect unusual transaction amounts.

The calculated limits were:

Lower Limit: -28,230.625 Upper Limit: 77,664.375

The analysis found 0 outliers in the transaction amount column.

This indicates that no transaction amount was identified as an outlier using the IQR method.
Fraud Signal Findings
The statistical analysis identified the following potential fraud signals:

High transaction amount combined with high transaction frequency.
Fraudulent transactions had a slightly higher average transaction amount.
Fraudulent transactions showed a slightly higher average transaction frequency.
37 transactions were identified as suspicious based on high amount and high frequency.
Among the 37 suspicious transactions, 6 were fraudulent.
Device changes and account age did not show strong differences between normal and fraudulent transactions.
These signals can help in identifying transactions that require further monitoring.
Visual Analysis
Graphs and charts were used to understand the relationship between transaction features and fraud.

The visual analysis included:

Normal vs Fraud Transactions
Transaction Amount Distribution
Average Transaction Amount by Fraud
Average Transaction Frequency by Fraud
Average Device Changes by Fraud
Average Account Age by Fraud
These visualizations helped to identify differences and unusual patterns between normal and fraudulent transactions.
Business Recommendations
Based on the statistical analysis, the following recommendations are suggested:

Monitor high-value and high-frequency transactions carefully.
Use multiple fraud signals together instead of relying on transaction amount alone.
Flag unusual transaction patterns for additional verification.
Continuously monitor suspicious user activity.
Use statistical analysis as an early warning system for possible fraud.
Future Scope
The project can be improved by using larger real-world UPI transaction datasets.

Future analysis can include machine learning models, real-time fraud detection, and advanced anomaly detection techniques.
Conclusion
Statistical analysis helped identify suspicious transaction patterns in the UPI dataset.
