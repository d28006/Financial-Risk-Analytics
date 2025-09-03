![# Preview
](https://github.com/d28006/Financial-Risk-Analytics/blob/main/Snapshot%20of%20Dashboard.PNG)
1. Project Title / Headline

💳 Credit Card Fraud Risk Analysis Dashboard: Transaction Insights by Fraud Type, Risk Level, and Geography
An interactive Power BI dashboard designed to track fraudulent credit card transactions, fraud patterns, and risk severity across multiple dimensions (fraud type, state, category, and month). It empowers financial institutions and fraud analysts to detect emerging fraud trends, assess transaction risks, and strengthen fraud prevention strategies.

2. Short Description / Purpose

The Credit Card Fraud Risk Analysis Dashboard provides a comprehensive view of fraudulent transaction metrics including fraud rate, fraudulent transaction counts, critical risk incidents, transaction amounts, and top fraud types. It enables risk teams, compliance officers, and fraud investigators to monitor fraud hotspots, identify vulnerable categories, and support data-driven decisions for fraud mitigation and customer protection.

3. Tech Stack

The dashboard was built using the following tools and technologies:

📊 Power BI Desktop – Main platform for building and visualizing fraud analysis reports

🔄 Power Query (M) – For extracting, cleaning, and transforming transaction datasets

🧠 DAX (Data Analysis Expressions) – For fraud rate calculations, aggregation of transaction amounts, and risk segmentation measures

🧩 Data Modeling – Structured relationships between fraud transactions, merchant categories, geographies, and time dimensions

🗄 SQL Server / Database – Source of transaction-level data prior to ingestion in Power BI

💻 SQL (SELECT, GROUP BY, JOIN) – Used to query, aggregate, and segment transaction-level fraud records

📁 File Format – .pbix (Power BI project) with exported visuals for reporting

4. Data Source

Source: Credit card transaction dataset including fraudulent and non-fraudulent records.
The dataset includes:

Fraudulent transaction counts and amounts

Fraud rate and severity (Low, Medium, High, Critical)

Fraud types: Card Not Present, Card Skimming, Identity Theft, Account Takeover, Phishing

Merchant categories: Apparel, E-commerce, Electronics, Food Delivery, Groceries, Transportation

Fraud distribution by geography (state-level)

Monthly fraudulent transaction trends

5. Features / Highlights
• Business Problem

Financial institutions face growing threats from credit card fraud across digital and physical channels. Detecting fraud patterns by geography, time, and category is critical to reducing financial losses, ensuring compliance, and protecting customers.

• Goal of the Dashboard

To provide fraud analysts and financial institutions with:

A consolidated overview of fraudulent transaction amounts and risk severity

Insights into the most common fraud types and high-risk merchant categories

Geographic fraud distribution (state-level risk exposure)

Monthly fraud trends to detect seasonal spikes and anomalies

Actionable insights for designing proactive fraud prevention strategies

6. Walkthrough of Key Visuals

Top KPI Cards – Display Fraud Rate (28.6%), Fraudulent Transactions (286), Critical Risk Transactions (11), Fraudulent Transaction Amount ($3M), and Top Fraud Type (“Card Not Present”).

Fraud by Type & Category (Heatmap) – Shows fraud distribution across categories like e-commerce, electronics, groceries, etc., segmented by fraud type (Card Not Present, Identity Theft, etc.).

Fraud Risk Severity (Donut Chart) – Breaks down fraudulent amounts by risk level: Low (42.4%), Medium (27.9%), High (18.8%), Critical (10.8%).

Fraudulent Transactions by State (Bar Chart) – Identifies high-risk states such as Maharashtra (36), Karnataka (34), and Rajasthan (34).

Fraudulent Transactions by Month (Line Chart) – Highlights monthly fluctuations, with December (34) and August (29) as peak months.

7. Business Impact & Insights

🔎 Top Fraud Type – “Card Not Present” fraud dominates, requiring stronger digital authentication and verification measures.

📍 Geographic Hotspots – Maharashtra and Karnataka show highest fraud volumes, indicating priority zones for fraud monitoring.

📊 Risk Distribution – While 42.4% of fraud is low risk, the 10.8% critical-risk transactions represent severe financial exposure.

📈 Seasonal Trends – Fraud peaks in December, suggesting higher fraud risk during holiday shopping seasons.

💳 Actionable Outcome – Enables banks to tailor fraud-prevention strategies by fraud type, merchant category, and location to minimize losses and protect customers.)
