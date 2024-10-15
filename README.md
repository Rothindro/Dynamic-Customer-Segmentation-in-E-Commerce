# Dynamic Customer Segmentation in E-Commerce: A Comprehensive RFM Analysis of E-Commerce Retail Transactional Data
---
### Overview:
This project analyses customer's buying pattern to come up with a plan to segment customers into different categories using RFM score. Used a dumy retail dataset from [kaggle](https://www.kaggle.com/datasets/ulrikthygepedersen/online-retail-dataset), which contains some transactions made by customers at an e-commerce platform.
- __Recency (R):__ Measures how recently a customer has made a purchase. Customers who bought recently are often more likely to respond to new marketing efforts
- __Frequency (F):__ Counts how often a customer makes a purchase within a certain timeframe. Frequent buyers are usually more valuable and more likely to engage with promotions
- __Monetary (M):__ Assesses how much money a customer spends during a given period. Higher spenders are often prioritized for special offers or loyalty programs

This will help an organization to Understand customer behavior and preferences more deeply, focus resources on high-value customers and tailor campaigns accordingly and Identify at-risk customers and engage them effectively to improve retention rates.

- __InvoiceNo:__ Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation
- __StockCode:__ Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product
- __Description:__ Product (item) name. Nominal
- __Quantity:__ The quantities of each product (item) per transaction. Numeric
- __nvoiceDate:__ Invice Date and time. Numeric, the day and time when each transaction was generated
- __UnitPrice:__ Unit price. Numeric, Product price per unit in sterling
- __CustomerID:__ Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer
- __Country:__ Country name. Nominal, the name of the country where each customer resides

Basic python libraries like Numpy and Pandas has been used to perform this RFM analysis utilizing the dumy retail dataset. The analysis will help with Strategic recommendations include prioritizing loyalty programs, targeted marketing to enhance retention, and win-back campaigns for low value customers.
