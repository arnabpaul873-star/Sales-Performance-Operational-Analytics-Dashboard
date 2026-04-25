📊 Sales & Operational Performance Dashboard

🚀 Overview

This project analyzes multi-year sales data to uncover critical issues in revenue generation, payment behavior, and operational efficiency. 

Instead of just visualizing data, this dashboard highlights hidden business risks and performance bottlenecks that directly impact profitability.

📁 Project Structure
├── data/
│   ├── raw_dataset.xlsx        # Original dataset (unaltered)
│   ├── cleaned_dataset.xlsx    # Processed/cleaned data (if applicable)
│
├── dashboard/
│   ├── sales_dashboard.xlsx    # Final interactive dashboard
│
├── README.md

📁 Dataset

The dataset includes transaction-level sales data with:

1. Order details (ID, date, product)
2. Revenue (₹ value)
3. Payment status (Paid, Pending, Failed)
4. Delivery status (Delivered, Cancelled, In Transit)
5. Customer location (city-level)


🛠️ Tools Used

1. Microsoft Excel
2. Pivot Tables
3. Slicers & Interactive Dashboarding
4. Data Cleaning & Structuring

📊 Dashboard Features

1. KPI panel (Revenue, Orders, AOV, Payment & Delivery Success)
2. Time-series trends (Revenue & Orders)
3. Payment & Delivery distribution analysis
4. Product-level performance breakdown
5. City-level performance insights
6. Interactive slicers (Year-wise filtering)

🔍 Key Insights (Actual Business Findings)

1. Payment System is the Biggest Risk
Only 41% payment success rate
Majority of transactions are either pending or failing
Revenue leakage is not due to sales — it’s due to collection failure

👉 This is not a sales problem. It’s a payment infrastructure problem.

2. “Pending” Payments Are Misleading
59% of transactions are marked as pending
This inflates perceived performance
Realistically, a large portion of these may convert into failures

👉 Revenue numbers are overstated.

3. Delivery Performance is Declining
Delivery success (~43%) is low and trending downward
Increasing cancellations and in-transit delays

👉 Operational inefficiency is getting worse over time, not improving.

4. AOV is Flat → No Growth Strategy
Average Order Value shows no meaningful increase
Indicates lack of:
Upselling
Pricing strategy
Product bundling

👉 Business is running, not scaling.

5. Revenue is Concentrated
Smartwatches are the top-performing product
Bangalore is the strongest city

👉 Growth depends heavily on a few segments, which is risky.

⚠️ Core Problem Summary

This business is not failing because of low demand.

It is failing because of:

1. Poor payment conversion
2. Weak operational execution
3. Lack of revenue optimization strategy

💡 Future Improvements

1. Add SQL-based data pipeline
2. Build Power BI version for scalability
3. Implement forecasting (sales & failure prediction)
4. Deep-dive into payment failure causes
