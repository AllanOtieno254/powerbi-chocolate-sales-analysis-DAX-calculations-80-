# 🍫 Awesome Chocolate Sales Analysis - Power BI & DAX
![page3](https://github.com/user-attachments/assets/c62a38fc-eae4-45ee-b2f0-c613cffd3acc)

## 📌 Overview
This Power BI project analyzes **chocolate sales performance** using advanced **DAX calculations** and **interactive visualizations**. The report provides insights into **monthly revenue, top-selling products, sales trends**, and **market performance**.

## 🚀 Features
- 📊 **Dynamic Dashboard** – Interactive sales reports
- 📈 **DAX Measures** – Advanced calculations for sales analysis
- 🏆 **Top Products & Revenue Trends** – Identify the best-performing chocolates
- 📅 **Time Intelligence** – Monthly & yearly comparisons
- 🔍 **Customer & Market Insights** – Data-driven decision-making


## 🛠️ DAX Calculations Used
This project includes several **DAX functions**:
- **Total Sales:** `SUM(sales[Amount])`
- **YoY Growth:** `CALCULATE([Total Sales], SAMEPERIODLASTYEAR(calendar[Date]))`
- **Top 5 Products:** `TOPN(5, SUMMARIZE(sales, sales[Product], "Revenue", SUM(sales[Amount])))`

## 📸 Screenshots
![page 1](https://github.com/user-attachments/assets/9e8a716c-c9d9-44a5-ac5c-986f36768d73)
![page2](https://github.com/user-attachments/assets/43889ff8-4290-4f22-941c-830704633d37)


## 📊 Data Sources
- **Sales Transactions Dataset** (`sales_data.csv`)
- **Customer Information** (`customer_data.xlsx`)

## 🔥 How to Use
1. Open `aws-chocolate-DAX.pbix` in **Power BI Desktop**.
2. Refresh the dataset (ensure `data/` files are available).
3. Explore insights via **interactive dashboards**.

## ⚖️ License
This project is licensed under the **MIT License** – feel free to use, modify, and share!

## 🤝 Contributing
Want to improve the dashboard? Submit a pull request! 🚀

## 📩 Contact
For any queries, reach out to **[Your Email]** or visit my **GitHub profile**.

