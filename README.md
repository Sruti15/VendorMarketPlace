# VendorMarketPlace

Improving Customer Satisfaction & Product Performance in a Multi-Vendor Marketplace

(AWS-Based BIE Project using Olist Dataset)

⸻

📌 Objective

To analyze customer behavior and product performance in a multi-vendor e-commerce marketplace by leveraging AWS data analytics services. This project aims to derive actionable insights on delivery reliability, seller performance, and customer satisfaction using an end-to-end data pipeline.

⸻

🚀 Project Goals
	•	Ingest and manage raw data using Amazon S3
	•	Clean, transform, and join multiple datasets using AWS Glue
	•	Perform advanced analytics using Amazon Redshift and Athena
	•	Visualize KPIs and build interactive dashboards using Amazon QuickSight
	•	Identify areas to improve customer satisfaction and streamline product/seller performance

⸻

📦 Dataset

Source: Olist Brazilian E-commerce Public Dataset on Kaggle

Data Overview:
	•	Covers 100k+ orders from 2016 to 2018 in Brazil
	•	Includes customer, order, product, payment, shipping, and review data

Dataset Organization on S3:
The dataset is organized into multiple files, each representing different aspects of the marketplace:
	1.	customer_data.csv: Contains details about customers, such as their ID, name, and geographic location.
	2.	order_data.csv: Contains order-level details, including order ID, product ID, payment status, and date.
	3.	product_data.csv: Contains details about products, such as product category, seller ID, price, and rating.
	4.	review_data.csv: Contains customer reviews, ratings, and comments associated with the orders.
	5.	shipping_data.csv: Contains shipping information, such as delivery time and status.

These files are stored in Amazon S3 for easy access and management.

⸻

🔧 Architecture Overview

The project will utilize the following AWS services:
	1.	Amazon S3: Data storage for the raw datasets.
	2.	AWS Glue: ETL (Extract, Transform, Load) process to clean and join datasets.
	3.	Amazon Athena: Querying data directly from S3 for analytics.
	4.	Amazon Redshift: Data warehousing for efficient querying and analysis.
	5.	Amazon QuickSight: Building interactive dashboards to visualize KPIs related to customer satisfaction and product performance.

⸻

⚙️ Implementation Steps
	1.	Data Ingestion:
	•	Upload the raw datasets to Amazon S3, categorizing them into distinct folders (e.g., customer, order, product, review, shipping).
	2.	ETL Process:
	•	Use AWS Glue to clean and transform the raw datasets:
	•	Remove duplicates and handle missing data.
	•	Merge datasets based on relevant keys (e.g., order_id, product_id, etc.).
	3.	Data Analytics:
	•	Use Amazon Athena to perform initial exploratory data analysis (EDA) and ad-hoc queries.
	•	Load cleaned data into Amazon Redshift for advanced analytics, such as aggregation, filtering, and complex joins.
	4.	Data Visualization:
	•	Use Amazon QuickSight to create interactive dashboards that display KPIs like delivery time, customer satisfaction, and seller performance.
	•	Visualize data trends over time, identify top-performing products and sellers, and analyze areas for improvement.

⸻

📊 Key Insights & KPIs
	•	Delivery Reliability: Analyze the average delivery time and on-time delivery rate.
	•	Seller Performance: Measure seller ratings, return rates, and customer satisfaction levels.
	•	Product Performance: Identify top-selling products, customer preferences, and rating trends.
	•	Customer Satisfaction: Analyze review scores and customer feedback for patterns.

⸻

📄 Future Improvements & Next Steps
	•	Integrate additional data sources, such as social media sentiment analysis, to enhance customer insights.
	•	Implement machine learning models for predictive analytics (e.g., customer churn prediction, demand forecasting).
	•	Scale the solution to handle larger datasets and provide more granular insights.
