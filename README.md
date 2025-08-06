 AtLiq Hardware Sales Insight Dashboard 🚀

A real-time **Sales Insight Dashboard** built using **Power BI** and **SQL** for **AtLiq Hardware**, a computer hardware company navigating a competitive and rapidly changing market landscape.

🔗 **Check out the live project here:**[https://www.linkedin.com/in/souvik-haldar/details/projects/]

---

## 📊 Project Overview

AtLiq Hardware faced challenges in adapting to volatile market trends and shifting customer behaviors, impacting sales performance. This project delivers a dynamic sales insight dashboard designed to provide **real-time analytics** and empower the **sales leadership team** with data-driven decision-making tools.

### 🎯 Objectives

- Deliver real-time visibility into sales performance
- Analyze product categories, customer segments, and regional trends
- Identify top-performing salespersons and high-revenue products
- Support strategic planning through actionable data

---

## 🛠️ Tools & Technologies

| Tool         | Purpose                                  |
|--------------|-------------------------------------------|
| Power BI     | Dashboard creation & data visualization  |
| SQL Server   | Data extraction and transformation        |
| DAX          | Custom measures and calculated columns    |
| Excel/CSV    | Data cleaning and import (if applicable)  |

---

## 📈 Key Features

- **Real-time Sales Overview**: Track KPIs like Total Revenue, Gross Margin, Quantity Sold
- **Product Performance Analysis**: Compare sales across categories and products
- **Customer Insights**: Analyze purchase frequency, segments, and behavior
- **Geographical Trends**: Region-wise and city-wise performance breakdown
- **Time Intelligence**: Monthly/quarterly/yearly trends with dynamic filters

---

## 📁 Project Structure

AtLiq-Sales-Dashboard/
├── data/
│ ├── sales_data.sql # SQL scripts for data extraction
│ └── cleaned_data.csv # (if used) cleaned dataset
├── dashboard/
│ └── AtLiq_Sales_Dashboard.pbix
├── assets/
│ └── dashboard_screenshots/
├── README.md
└── requirements.txt # (optional) tools or packages

---

## 🚀 Insights Delivered

- Identified top 5 products contributing to 60% of revenue
- Regional performance gaps helped refocus marketing strategy
- Optimized inventory through sales trend forecasts
- Boosted team performance with salesperson-level tracking

---

## 🧠 Learnings & Challenges

- Implemented complex **DAX formulas** for time-based calculations
- Ensured **data integrity** with SQL joins and transformations
- Enhanced report **interactivity** using slicers and bookmarks
- Learned performance optimization techniques in Power BI

---

## 📌 How to Use

1. Clone or download this repository
2. Open the `.pbix` file using Power BI Desktop
3. Connect your own dataset or use provided sample data
4. Customize filters, visuals, or KPIs as per business needs

---

## 🙌 Acknowledgements

Special thanks to AtLiq Hardware's mock business case and all open datasets used for building this project.

---

## 📬 Connect with Me

📧 Email: [souvikptech@gmail.com]  
💼 LinkedIn: (https://www.linkedin.com/in/souvik-haldar/)

---

**#PowerBI #SQL #Dashboard #DataAnalytics #SalesInsights #AtLiqHardware**

`= Table.AddColumn(#"Filtered Rows", "norm_amount", each if [currency] = "USD" or [currency] ="USD#(cr)" then [sales_amount]*75 else [sales_amount], type any)`



