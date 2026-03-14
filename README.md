# App Insights Unlocked: Google Play Store Analytics

**Developed by:** Adarsh Dwivedi  
**Role:** Data and Business Analyst  

This repository contains a deep-dive **Power BI Analysis** of the Google Play Store ecosystem.  
Using a dataset of **9,367+ apps**, this project identifies the factors that drive app success, user engagement, and revenue generation.

---

##  Technology Stack & Tools Used
To build this project end-to-end, the following tools were used:

- **Microsoft Power BI Desktop:** Interactive dashboards and data visualization.  
- **Power Query (M Language):** Data cleaning, transformation, and handling missing values.  
- **DAX (Data Analysis Expressions):** Custom measures and complex calculations.  
- **Microsoft Excel / CSV:** Raw dataset handling and initial data audit.  
- **Looker Studio:** Supplementary charts and high-level summary reporting.  

---

## Technical Workflow
- **Data Extraction:** Raw dataset fetched from Kaggle (Google Play Store Apps).  
- **Data Transformation (Power Query):**  
  - Removed null values from Rating column.  
  - Standardized App Size into MB/KB units.  
  - Dropped redundant columns to improve model speed.  
- **Data Modeling:** Built relationships between Categories and Ratings.  
- **Visualization:** Used bar charts, pie charts, and treemaps to show distribution and insights.  

---

##  Key Dashboard Insights
- **Category Dominance:** Family category has the highest number of apps, but **Games and Communication** categories lead in total reach (**167.6 Billion installs**).  
- **Monetization Strategy:** 92.6% of apps are free, highlighting the dominance of ad-revenue and freemium models.  
- **Quality Benchmark:** Average market rating is **4.19**. Apps below 4.0 show a significant drop in installs.  
- **Top Performance:** Leaders like **Subway Surfers, 8 Ball Pool, and ESPN** identified through comparative benchmarking.  

---

##  Key DAX Measures Developed
- **Average App Rating:** `AVERAGE('Apps'[Rating])`  
- **Total Market Installs:** `SUM('Apps'[Installs])`  
- **Review-to-Install Ratio:** Custom logic to measure user engagement levels.  

---

##  Strategic Recommendations
- **Focus on Engagement:** Developers should target high-install categories (Social, Productivity).  
- **Performance Maintenance:** Maintain ratings above **4.2** for organic growth.  
- **Monetization:** Free-to-play model with in-app purchases is the most successful strategy.  

---

##  Project Structure
- `project_power_bi.pbix` → Interactive Power BI dashboard.  
- `EDA01 - App Insights Analysis.docx` → Project documentation and problem statement.  

---

##  Data Source
Google Play Store Dataset (Kaggle) analyzed using **Power BI**.  
