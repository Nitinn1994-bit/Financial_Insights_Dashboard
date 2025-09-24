# Financial_Insights_Dashboard
Executive-ready dashboards to track company financials across Revenue, COGS, OpEx, Net Income, Current Assets, Current Liabilities, and Debt to Equity, with interactive breakdowns by year, month, legal entity, and cost center.

🔎 Overview
KPIs: Revenue, COGS, OpEx, Net Income, Current Assets, Current Liabilities, Debt to Equity Ratio
Breakdowns: Year, Month, Legal Entity, Cost Center, Time Calculation (YoY, TTM, etc.)
Goal: Provide clear visibility into profitability, liquidity, and solvency to support strategic decision-making.

📊 Pages

Home
One-page KPI cards for revenue, costs, net income, assets/liabilities, plus quick slicers (year, month, entity).

Income Statement
Combo/line charts for Revenue, COGS, OpEx, Net Income. Pivot table view for drill-down. Filters allow slicing by Year, Month, Legal Entity, and Cost Center.

Balance Sheet
Focus on liquidity: Current Assets, Current Liabilities, and solvency metrics like Debt-to-Equity. Trend visuals highlight changes across time and entities.

Summary
High-level view combining IS & BS KPIs, trend visuals, and slicers. A snapshot page designed for executives.

🛠️ Tech & Skills

Power BI: DAX measures, Power Query transforms, slicer interactions

Data Modeling: Star schema with FactFinancial, DimDate, LegalEntity, CostCenter, TimeCal

Key Measures: Total Revenues, Total COGS, OpEx, Net Income, Current Assets, Current Liabilities, Debt to Equity Ratio

Design: Clean KPI cards, combo charts, pivot tables, slicers, custom theme (BaseThemes/CY19SU12.json), and custom visual (Advance Card)
