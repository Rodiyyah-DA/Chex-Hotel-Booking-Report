# Chex-Hotel-Booking-Report

## Table of Contents

- [Introduction](#introduction)
- [Data Sources](#data-sources)
- [Problem Statement](#problem-statement)
- [Power BI and Analytics technical skills](#power-bi-and-analytics-technical-skills)
- [Data Modeling](#data-modeling)
- [Report Design and Visualization](#report-design-and-visualization)
- [Analytics and Insights](#analytics-and-insights)
- [Conclusions and Recommendations](#conclusions-and-recommendations)

### Introduction
---

The Chex Hotel Yearly Report is a comprehensive business intelligence dashboard built in Power BI to monitor hotel performance metrics such as bookings, revenue, lead time, and customer distribution. This report provides management with actionable insights into operational trends, enabling data-driven decision-making to optimize sales channels, target profitable markets, and improve occupancy rates.

<img width="754" height="422" alt="RODIYYAH'S PROJECT 2" src="https://github.com/user-attachments/assets/ca9f5698-0c66-447b-8b45-b2c62b8a424e" />

### Data Sources

---

The report uses hotel booking transactional data stored in a structured table format. Key data fields include:
- Bookings Information (distribution channel, country, deposit type, assigned room type)
- Revenue Data (charge amounts, lead times)
- Customer Behavior (is_canceled, is_repeated_guest)
- Calendar Table (date and year for time-based analysis). Here is the link to the data [Download here](https://drive.google.com/file/d/16WveT0gXbJAOdhZTqVWui8P_prbX0mC5/view?usp=drivesdk)
  
The dataset was cleaned and transformed within Power BI using Power Query Editor, ensuring data integrity and proper relationships for accurate analytics.

<img width="917" height="554" alt="Power Query Capture" src="https://github.com/user-attachments/assets/9164f10e-e719-4822-9818-96b3a4872464" />

### Problem Statement
---

The hotel management needs a centralized, interactive dashboard to answer key business questions:
- Which distribution channels generate the most bookings and revenue?
- Which countries contribute most to revenue and bookings?
- How does average revenue change across years?
- What is the average lead time for bookings?
- Where can operational strategies be adjusted to increase revenue and occupancy?

### Power BI and Analytics Technical Skills
---

The report leverages several Power BI capabilities:
- Data Transformation using Power Query (cleaning nulls, formatting columns, data type changes)
- DAX Measures for calculations (total revenue, average lead time, year-over-year analysis)
- Data Modeling for relationships between tables
- Visualization Design (bar charts, pie charts, KPIs)
- Filtering and Slicers for year-based dynamic reporting
- Deployment to Power BI Service for sharing and collaboration

### Data Modeling
---

The model follows a star schema approach:
- Fact Table: Contains bookings and revenue metrics (Charge, lead time, distribution channel, country, etc.).
- Dimension Table: Calendar table with Date and Year for time intelligence functions.
- Relationship: One-to-many relationship between Calendar[Date] and Table[Date], ensuring proper filtering in time-based visuals.

<img width="652" height="426" alt="Data modeling Project 2" src="https://github.com/user-attachments/assets/4029fccc-c83a-4770-bc05-4b2df50ae8fd" />

### Report Design and Visualization
---

The dashboard is divided into multiple sections for clarity:

- KPIs:
  - Average Lead Time: 88.15 days
  - Total Revenue: 204.87M
- Distribution Channel Analysis:
  - Bookings by Distribution Channel (TATO dominating)
  - Revenue by Distribution Channel (TATO highest contributor)
- Geographical Analysis:
  - Bookings by Country (highest from PRT)
  - Revenue by Country (highest from PRT)
- Yearly Revenue Trends:
  - Donut chart showing average revenue distribution by year (2014–2017)
 
### Analytics and insights
---

From the report:
1. TATO (Travel Agent/Tour Operator) generates the majority of bookings and revenue.
2. Portugal (PRT) is the leading market in both bookings and revenue.
3. Average lead time is quite high (88 days), indicating customers plan well ahead.
4. Revenue has remained relatively stable across the years, with slight variations.
5. Other distribution channels (Direct, Corporate) show potential for growth but are currently underperforming.

### Conclusions and Recommendations
---

Conclusions:
- Heavy dependency on a single distribution channel (TATO) poses business risk.
- Concentrated revenue sources from limited geographies (mainly Portugal).
- Advance booking trend provides forecasting opportunities.

Recommendations:
- Diversify sales strategies to increase Direct and Corporate bookings.
- Expand marketing efforts to underrepresented countries.
- Implement targeted promotions for short-lead-time bookings to fill gaps.
- Use historical booking lead times for better staffing and resource allocation.

### Deployment to Power BI Service
---

- The report was published to the Power BI Service for secure cloud access.
- Access Control: Role-based permissions set for management and marketing teams.
- Scheduled Refresh: Automated daily refresh to keep data up to date.
- Sharing: Dashboard shared via Power BI App for executive summaries.
- Mobile View: Optimized layout for mobile access.



