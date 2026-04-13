# Financial Market Intelligence Dashboard & Data Pipeline

## 📌 Project Overview
This project simulates a real-world financial data workflow. It features an end-to-end analytics pipeline that extracts, transforms, and visualizes market data to deliver actionable business insights.

🔗 **Live Dashboard:** [Insert Your Tableau Public Link Here]

## ⚙️ Data Architecture & Workflow
1. **Data Extraction (ETL):** Automated historical stock data retrieval (AAPL, MSFT, TSLA) using **Python (yfinance)**.
2. **Data Transformation:** Performed data cleaning, missing value handling, and feature engineering (Moving Averages, Daily Returns) using **Pandas**.
3. **SQL Analytics:** Stored transformed data into an **SQLite** database. Designed queries to aggregate KPIs, detect price volatility, and identify top-performing trading days.
4. **Visualization:** Developed an interactive **Tableau** dashboard to present key financial metrics clearly to stakeholders.

## 📈 Key Business Insights Extracted
- **Volatility Detection:** Identified high-risk trading periods using automated percentage return thresholds.
- **Trend Reversals:** Highlighted market shifts by comparing short-term (MA7) and long-term (MA30) moving averages.
- **KPI Tracking:** Centralized critical metrics (AVG, MAX, MIN prices) for rapid executive decision-making.

## 📷 Dashboard Preview
![Dashboard Preview](dashboard/spgi_dashboard_preview.png)

*Tech Stack: Python, SQL (SQLite), Tableau, Pandas, yfinance*
