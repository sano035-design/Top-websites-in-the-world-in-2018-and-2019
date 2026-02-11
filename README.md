Top websites in 2018 and 2019 .jpg

# 📊 Top Websites Global Ranking Analysis (2018-2019)

This project provides a comprehensive Power BI analysis of the world's most visited websites between 2018 and 2019. 
It examines geographic dominance, industry categorization, and ranking fluctuations across 68 unique web entities.

---

## 📁 Repository Structure

* **data/**: Contains the raw dataset `top websites.xlsx` (69 initial rows).
* **powerbi/**: Includes the final `Top websites.pbix`
* **screenshots/**: Dashboard preview images for documentation.
* **README.md**: Project overview and documentation.

---

## 🔍 Key Questions Answered

* **How many websites were analyzed?** After data cleaning, the final dashboard reflects **68 unique websites**.
* **Which country dominates the top websites?** The **USA** leads with 32 websites, followed by **China** with 14.
* **What types of websites are most common?** **E-commerce** and **Internet Services** represent the largest share of the top-ranked sites.
* **Who are the top-ranked entities?** **Google**, **YouTube**, and **Facebook** consistently occupy the top 3 positions.
* **What business models dominate?** Ad-based search engines and transaction-based E-commerce platforms are the primary drivers.

---

## 🛠️ Data Transformation & Notes

To ensure the accuracy of the ranking analysis, several **Power Query (M-Code)** transformations were applied:
1. **Deduplication**: Removed technical sub-domains (e.g., `login.tmall.com`) to maintain focus on 68 unique root domains.
2. **Dynamic Grouping**: Created a `Parents` column to consolidate regional domains (e.g., Google Italy, Google Spain) into a single brand entity: **Google**.
3. **Ranking Logic**: Utilized **Bottom N filters** and **Min Aggregation** to correctly visualize rankings where '1' represents the highest achievement.

---

## 🚀 How to Use

1. **Prerequisites**: Ensure you have [Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed.
2. **Open Project**: Load `powerbi/website_analysis.pbix`.
3. **Interactive Analysis**: Use the slicers to filter data by **Principal Country** or **Type Group**.


## 📊 Dashboard Preview

![Main Dashboard Preview](top-websites.jpg)

