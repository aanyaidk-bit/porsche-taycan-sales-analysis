# porsche-taycan-sales-analysis
Data analytics portfolio project — Porsche Taycan EV sales trend analysis (2021–2024) using Python, SQL, and Excel
# Porsche Taycan Sales Trend Analysis (2021–2024)

## Project Question
How has the introduction of the Taycan affected Porsche's EV market position in the luxury EV segment?

## Background
This project extends an IB Business Management research paper into a hands-on data analytics case study. It analyzes Porsche's strategic 
shift toward electric vehicles and the Taycan's impact on revenue and market position.

## Tools Used
- **Python** (pandas, Plotly, SQLite) — data analysis & visualization
- **SQL** — 7 queries using window functions (LAG, RANK, PARTITION BY)
- **Excel** — structured data workbook with 3 sheets and live formulas

## Files
| File | Description |
|------|-------------|
| `porsche_taycan_analysis.ipynb` | Main Colab notebook — all queries and charts |
| `porsche_taycan_queries.sql` | Standalone SQL queries with comments |
| `porsche_taycan_analysis.xlsx` | Excel workbook — Annual Data, Quarterly Sales, KPI Summary |
| `porsche_master_summary.csv` | 

## Key Findings
- Taycan deliveries peaked at 41,296 units in 2021, outselling the iconic 911
- Revenue grew from €26.1B (2021) to €40.5B (2023) — a 55% increase
- Taycan held the #1 position in the luxury EV segment every year vs. Tesla Model S and Lucid Air
- 2024 saw a -39% delivery drop — structural slowdown, not seasonal
- Weak correlation (~0.3) between Taycan volume and revenue suggests broader product mix matters

## Data Sources
- Porsche AG Annual Reports (2021–2024)
- InsideEVs — Taycan quarterly delivery data
- Tesla & Lucid Motors Investor Relations
- U.S. Department of Energy — EV sales data
