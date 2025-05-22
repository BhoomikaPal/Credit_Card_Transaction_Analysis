# Credit_Card_Transaction_Analysis
Analyzing transactional data from a credit card company for the years 2022 and 2023. 

## Dataset Schema
- `date`: Timestamp of transaction  
- `user_id`: Unique user identifier  
- `transaction_id`: Unique transaction identifier  
- `transaction_amount`: Amount of the transaction

## Tasks

-**`Create a SQL and Python code to`**:
- a) Calculate: total_transactions, unique_users and total_transaction_amount for every date and hour combination.
- b) Calculate hour with highest transaction_amount for every date

## How to Navigate

- **`README.md`**: You're here! Start here to understand the purpose, tasks, and Insights.
- **`sample_transactions_data.csv`** *(optional)*: Contains sample transaction data (date, user, transaction ID, amount).
- **`SQL_queries.sql`**: SQL code to compute metrics per hour and identify peak transaction hours per day.
- **`transaction_analysis.py`**: Python script to perform the same analysis programmatically.

## Output

![Metrics_per_Date_hour](https://github.com/user-attachments/assets/6a92fe42-af7a-4ce1-9f17-5d5f90fe0104)
![Highest_transaction](https://github.com/user-attachments/assets/2d2706af-5e37-4701-bf7e-eecba2700d1b)

## Insights (As per Sample Data)

- **Peak Usage Hours:** 3 PM – 5 PM consistently had the highest transaction amounts, indicating strong afternoon engagement.
- **Spending Spikes:** Notable high-activity days (e.g., July 5, Dec 20) likely align with sales or festive periods.
- **Widespread Usage:** Multiple unique users transacting at peak times suggests broad engagement, not just high-value users.
- **Stable Patterns:** Hourly behavior trends remained consistent across both years.

## Insight through graphs:

![Metrics](https://github.com/user-attachments/assets/0488b127-0762-46ca-be1f-5fcccfbfc266)
![Highest_transaction_by_hour](https://github.com/user-attachments/assets/00fd889f-eeef-47bd-a37e-5f5e85c1bc1a)
![Highest_transaction_by_hour_line_graph](https://github.com/user-attachments/assets/37bb8f44-3c6f-480d-9945-35f9efe79be3)

## Future Scope 
- Customer Segmentation: To personalize marketing, increase card usage, and improve retention based on behavior.
- Cross-Sell/Upsell Campaigns: To promote relevant credit card products based on usage behavior.
- Behavior-Based Personalization: To increase engagement by sending reminders or offers when a user typically transacts.
- Dashboard for Business Leaders: To help decision-makers track performance.
- Spend Forecasting (Hourly/Daily): To anticipate high-volume periods and optimize campaign timing.
