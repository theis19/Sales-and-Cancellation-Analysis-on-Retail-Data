# Online Retail II – Sales & Cancellation Analysis  
 
The analysis explores the **Online Retail II (UCI)** dataset, focusing on **order cancellations** and their impact on sales.

Dataset taken from [Online Retail II Dataset (Kaggle)](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci/data)

## 📊 Project Overview  
E-commerce transactions often contain cancellations, which represent **lost sales**.  
Rather than removing these records, this project analyzes them to uncover patterns by **country, product, customer, and time**.  

The main steps:  
1. **Data Understanding & Cleaning** – Handling duplicates, invalid records, and separating sales from cancellations.  
2. **Exploratory Data Analysis (EDA)** – Overview of transactions, sales revenue, and cancellations.  
3. **Cancellation Analysis** – Identifying the countries, products, and customers most affected.  
4. **Time Trends** – Exploring seasonality of sales and cancellations.  
5. **Insights & Recommendations** – Business takeaways to reduce cancellations.  

## 📂 Files in this Repo  
- `sales_cancel_analysis.ipynb` → Jupyter Notebook with full analysis and code.  
- `report.pdf` → Business-friendly report with summary, insights, and recommendations.  

## 🔑 Key Insights  
- The **UK** has the largest cancellations in absolute value, but this reflects its high sales volume.  
- Some products (e.g., *Paper Craft, Little Birdie* and *Ceramic Storage Jar*) cause disproportionate losses.  
- Certain customers repeatedly cancel orders, showing behavioral patterns.  
- Cancellations rise in November–December, but mainly because sales peak in these months.  

## 💡 Recommendations  
- Focus on **countries with smaller sales but high cancellations** (e.g., Germany, EIRE).  
- Investigate and improve **problematic products** through quality control or clearer descriptions.  
- Monitor **high-cancellation customers** more closely.  
- Prepare better for **seasonal peaks** with stronger logistics and communication.  

## 🚀 Reflection  
This project chose cancellations as the focus, since they are often ignored in typical analyses (e.g., RFM).  
The approach is simple and clear, but future work could involve:  
- Building ML models to **predict cancellations**.  
- Combining with customer segmentation for a **wider business view**.  
- Creating dashboards for **real-time monitoring**.  
