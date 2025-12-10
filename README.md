# Tap-Savvy-Network-Data-Quality-Dashboard
Built a Power BI Data Quality Dashboard to analyze profile completeness, missing fields, and active vs inactive customer profiles for Tap Savvy Network. Developed KPIs and visual insights to highlight major data gaps such as missing profile pictures, incomplete company details, and outdated information. 

# Tap Savvy Network — Data Quality Dashboard

##  Project Overview
The **Tap Savvy Network Data Quality Dashboard** is a Power BI-based analytics solution designed to evaluate and monitor the completeness and quality of user profile data for Tap Savvy Network.  
It helps to quickly identify missing information across customer profiles (e.g., missing profile pictures, incomplete company details, absent contact info), as well as track active vs inactive profiles by company — enabling data-driven decisions to improve data quality and CRM effectiveness.

##  Why This Matters
- Ensures customer data completeness for accurate business operations and communication.  
- Highlights data gaps (missing fields, incomplete profiles) so they can be prioritized for update.  
- Helps visualize company-wise distribution of active/inactive users — useful for outreach, cleanup, or verification campaigns.  
- Provides insights into data hygiene which supports better marketing, user engagement, and compliance.

## 🧰 Dashboard Features

| Feature | Description |
|--------|-------------|
| **KPI Overview** | Displays total number of profiles, count of active vs inactive profiles, number of profiles missing pictures, and total missing values across all data fields. |
| **Missing Fields by Category** | Bar chart showing which fields (e.g., profile picture, company info, contact details) have most missing values — useful to prioritize data cleaning. |
| **Active / Inactive Profiles by Company** | Shows, for each company, how many profiles are active vs inactive — helps identify companies needing attention. |
| **Total Customers by Company & Missing Data** | Visualizes overall profile counts per company along with counts of missing data — enabling company-wise data completeness checks. |
| **Missing Field Summary (Pie Chart)** | Gives a high-level breakdown (percentages) of missing profiles, missing pictures, missing company names, and proportion of active/inactive profiles. |
| **Interactive Filters / Slicers** | Allows filtering the data by **location**, **company name**, and **designation** to explore subsets of interest. |

##  What the Dashboard Shows (Sample Numbers)
- **753** total profiles  
- **431** active profiles  
- **322** inactive profiles  
- **197** profiles missing profile pictures  
- **1,034** total missing values across all fields  

Top fields with missing data: profile pictures, company info (“about company”), website, designation, contact fields — showing where data completeness is weakest.  

Top companies by profile counts include `Bajaj Capital`, `Urban Sports Zone`, and others — helping you focus on organizations with the most data issues.

##  Tools & Technologies
- **Power BI Desktop** — for data modeling, visualizations, and interactive dashboard creation  
- **DAX (Data Analysis Expressions)** — used for computing measures like counts of missing fields, active/inactive profile counts, percentage metrics  
- **Interactive Slicers & Filters** — for dynamic exploration (by company, location, designation)  
- **Custom Theming / Dark UI** — for better readability and presentation  

##  How to Use / View the Dashboard
1. Clone or download the repository.  
2. Open the Power BI `.pbix` file (or equivalent dashboard file) in Power BI Desktop.  
3. Navigate through the KPI cards, charts, and filters to explore data completeness and profile distribution.  
4. Use filters on the left sidebar to drill down by **company**, **location**, or **designation**.  
5. Identify data gaps (e.g., missing pictures, missing company info) and plan cleanup or verification efforts accordingly.  

##  Potential Use Cases
- Customer data cleanup campaigns  
- Pre-marketing data verification before outreach  
- Internal audits of data completeness and hygiene  
- Monitoring data quality over time after maintenance or verification cycles  

##  About This Repository
This repository contains:  
- The Power BI dashboard file (or exported visuals)  
- Any supporting data (e.g., spreadsheets or CSVs used)  
- Documentation (this README)  


---

