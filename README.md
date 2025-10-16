**Customer & Sales Analysis Dashboards**
Overview:
This Power BI project provides an in-depth analysis of company sales performance and customer behavior through two interactive dashboards — Sales Overview and Customer Analysis. The goal is to help business teams understand key revenue drivers, top-performing products, and customer engagement patterns for better strategic decisions.

Key Highlights:
Sales Overview: Tracks total revenue (8.3M), 398K transactions, and 4.4K customers. Identifies top markets (Netherlands, EIRE, Germany, France, UK) and best-selling products like 85099B, 84879, and 85123A.

Customer Analysis: Examines demographics, customer lifetime value (avg. CLV: 1.9K), and purchase frequency trends. Highlights top customers and seasonal growth patterns in Q4.

Features: Dynamic KPIs, country & product filters, and interactive visuals (bar, line, and table charts) with a clean, user-friendly design.

Tools Used:
Power BI


**PhonePe Dashboard – Business Performance Analysis**
 Overview:
This Power BI dashboard provides a comprehensive analysis of PhonePe’s overall business performance, revenue segmentation, regional growth, and customer insights. It highlights key drivers of profitability and opportunities for strategic expansion.

Key Insights:

💰 Overall Performance: ₹2.30M total revenue, ₹286.4K profit, 38K transactions, and 793 customers — strong monetization with ₹2,900 revenue per customer.

🏠 Revenue Segmentation: Home Office segment leads with ₹429.65K profit, showing high-margin potential from home-based professionals.

🌍 Regional Performance: South Region contributes ~30% of revenue; East Region underperforms, indicating expansion potential.

💹 Profit Distribution: South Central region delivers 37% of total profit — ideal zone for higher marketing ROI.

📊 Category Growth (YoY): Tech-related products (Phones, Machines, Chairs) show consistent growth, while Office Supplies face stagnation.

🪑 Top Sub-Categories: Phones (₹320K) and Chairs (₹289.4K) dominate sales — bundling offers can boost profit.

🗺️ State Performance: California, New York, and Texas drive major revenue; expansion can focus on these markets.

🎯 Target Achievement: 66% of the ₹3.5M goal achieved — strong trajectory but room for improvement.

📈 Trend Analysis: Upward growth in both revenue and profit from 2016–2018, signaling sustainable business expansion.

👥 Customer Insights: Top customers (Adrian Barton, Raymond Rich, Sean Miller, Tamara Chand, Tom Ashbrook) contribute significantly — loyalty programs can enhance retention.

Key Takeaway:
Top 30% of customers and regions generate over 70% of total revenue — applying the Pareto 80/20 rule can optimize marketing and resource allocation.

Tools Used:
Power BI

 **Electric Vehicle Analysis Dashboard**

Overview:
This Power BI dashboard provides a comprehensive analysis of the Electric Vehicle (EV) market from 2011–2024, highlighting growth trends, manufacturer performance, regional adoption, and policy eligibility. The goal is to understand EV market dynamics, brand dominance, and expansion opportunities.

Key Insights:

🚗 Market Overview: 150.42K total EVs — 78% BEVs and 22% PHEVs — showing a clear shift toward fully electric mobility.

🔋 Average Range: 67.83 km per charge, suitable for urban use but signals need for improved battery efficiency.

🚀 Tesla Dominance: Tesla leads with 68.94K vehicles (~46% market share), setting benchmarks in innovation and performance.

🏭 Top Manufacturers: Nissan (13K) and Chevrolet (12K) follow Tesla, indicating strong top-3 concentration in the market.

📈 Yearly Growth: Exponential rise after 2017, peaking at 37K EVs in 2022 — boosted by incentives and awareness.

🏙️ City Distribution: Seattle (26K) leads, followed by Bellevue (8K) and Redmond (5K) — urban centers driving adoption.

♻️ CAFV Eligibility: 41.81% of vehicles are CAFV-eligible, while 46.33% are not — revealing room for policy improvements.

🚘 Top Models: Model Y (29K) and Model 3 (28K) dominate, jointly covering ~38% of the total market.

🌐 Brand Penetration: Tesla leads, while Kia, Toyota, and Volkswagen show steady emerging growth.

📊 Regional Expansion: Tier-2 cities like Olympia and Tacoma show promising potential for future EV growth.

Key Takeaway:
The EV market is rapidly expanding, led by Tesla and concentrated in urban areas like Seattle. However, nearly half of EVs remain ineligible for clean-fuel incentives — highlighting opportunities for policy enhancement and infrastructure development to drive broader adoption.

Tools Used:
Power BI


**AI Jobs & Salary Insights Dashboard**

Overview:
This Power BI dashboard provides an analytical overview of the global AI job market, highlighting salary trends, job distribution, experience requirements, and geographic variations. It offers data-driven insights into how AI roles are evolving across industries and regions.

Key Insights:

🧠 Machine Learning Dominance: Machine Learning Researchers lead with 808 positions — confirming ML as the core of AI job demand.

💵 High Global Salaries: The average salary across AI roles is $115.35K, reflecting strong global demand for AI expertise.

🇨🇭 Top-Paying Countries: Switzerland ($171K), Denmark ($166K), and Norway ($159K) lead — positioning Europe as the hub for premium AI opportunities.

🧑‍💼 Leadership Roles Pay the Most: Titles like Head of AI and Machine Learning Researcher command top-tier salaries.

⚖️ Balanced Employment Types: Nearly equal distribution among full-time, contract, freelance, and part-time roles — showcasing industry flexibility.

📈 Experience Matters: Senior professionals (~$190K) earn nearly double mid-level salaries (~$100K), proving the impact of expertise.

🌍 Industry Diversity: AI professionals work across 15+ industries — including tech, healthcare, finance, and manufacturing.

💱 Currency Comparison: Salaries vary by currency — GBP ($129K), EUR ($121K), and USD ($113K) — influenced by regional cost structures.

⏳ Experience Requirement: Average of 6.25 years of experience highlights the skill depth expected in AI jobs.

📊 Data Scientists Remain Core: Despite new titles, Data Scientist roles (720) continue to be the backbone of AI-driven insights.

Key Takeaway:
AI job markets are thriving globally, led by Machine Learning and Data Science roles. Europe offers the highest pay scales, while experience and specialization remain key factors in salary growth and career advancement.

Tools Used:
Power BI | DAX 


Comprehensive HR Analytics & Workforce DashboardData  

This repository contains the **raw data, calculations, and supporting components** for a robust **Human Resources (HR) Analytics Dashboard**. The purpose of this project is to provide a clear, data-driven view of key workforce metrics, enabling strategic decision-making in HR and managemKey Data & Metrics Included:

The files provide a structured view of various HR areas, typically spanning quarterly or monthly periods:

* **Workforce Planning:** FTE counts, staff headcounts, consultant numbers, and open positions. (See `Staff.csv`)
* **Talent Acquisition:** Metrics related to **new hires**, terminations, and potentially **Spend Per Hire**.
* **Compensation & Benefits:** Average salary, average bonus, average overtime, and average leave balances. (See `HR.csv`)
* **Employee Performance & Engagement:** Quarterly data for **employee satisfaction surveys**, training completion rates, average staff ratings, and gender diversity percentages. (See `HR.csv` and `Calcs.csv`)
* **Operational Health:** Overtime hours logged and FTE vs. Contractor percentages.
* **Model Calculations:** Dedicated sheets (`Calcs.csv`, `Chart.csv`) house the formulas and intermediate steps used to transform the raw data into key performance indicators (KPIs) and visualize them, including targets for metrics like **Speed to Hire** and **Promotion Rate**.

 Structure and Components:

The repository is organized by the functional components of the original spreadsheet model, including:

* `HR.csv` & `Staff.csv`: Primary **Input Sheets** containing the core monthly/quarterly data.
* `Calcs.csv` & `Chart.csv`: **Calculation Sheets** for processing data and preparing output for visualization.
* `Summary.csv`: The **Output Sheet** containing the final, summarized results and KPI dashboard view.
* `Check.csv`: Data integrity and **Error Trapping** logic to ensure accuracy.
* `Lists.csv` & `Model.csv`: Sheets defining key assumptions, lists (regions, departments), and the overall model structure.

This project is ideal for exploring data modeling, HR metric definitions, and dashboard development using real-world workforce data.
