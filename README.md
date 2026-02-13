# DA-and-ML-PJT1
Отлично 😎 Делаем версию уровня A+ (Distinction / Excellent Grade) — более академичную, структурированную и профессиональную, как полноценный университетский аналитический проект.

Ниже — усиленная версия, которую можно сразу использовать для сдачи или GitHub.

📊 CAU Data Analytics Project
Advanced Customer Segmentation & Sales Intelligence Analysis
📌 Executive Summary

This project presents a comprehensive analytical study of online retail transaction data. The primary objective is to explore purchasing patterns, evaluate customer value, and implement customer segmentation using quantitative methods and Machine Learning techniques.

Through systematic data preprocessing, exploratory analysis, RFM modeling, and K-Means clustering, the project identifies meaningful customer groups and provides actionable business recommendations aimed at revenue optimization and customer retention improvement.

The results demonstrate the practical application of data analytics methodologies in solving real-world business problems.

🎯 Project Objectives

The project aims to:

Perform structured data preprocessing and validation

Conduct in-depth exploratory data analysis (EDA)

Calculate RFM metrics to measure customer value

Apply unsupervised learning (K-Means Clustering)

Evaluate clustering performance using validation metrics

Generate business-focused recommendations

👥 Project Team
Role	Team Member	Student ID	Responsibility
🧭 Project Lead	Tursunaliev Hasanboy	202490339	Project coordination, architecture design, integration & documentation
📊 Data Analyst	Kim Stanislav	202490171	Data preprocessing, statistical analysis, RFM computation
🤖 ML Engineer	Yun Yuriy	202490384	Clustering implementation, model validation, performance evaluation
🗂 Dataset Description

Online Retail Transaction Dataset

The dataset contains transactional records including:

InvoiceNo

StockCode

Description

Quantity

InvoiceDate

UnitPrice

CustomerID

Country

The dataset represents real-world e-commerce transactions and includes multiple countries and customer segments.

⚙️ Methodology
🔹 1. Data Preprocessing

Handling missing values (CustomerID, Description)

Removing duplicate records

Filtering negative values (cancelled transactions)

Converting InvoiceDate into datetime format

Creating Revenue feature (Quantity × UnitPrice)

Outlier detection and treatment

🔹 2. Exploratory Data Analysis (EDA)

Time-series revenue analysis

Country-level sales comparison

Identification of top-performing products

Revenue distribution analysis

Customer purchase frequency patterns

Key statistical indicators were used:

Mean

Median

Standard deviation

Distribution plots

🔹 3. RFM Analysis

Each customer was evaluated using:

Recency (R): Days since last purchase

Frequency (F): Number of transactions

Monetary (M): Total revenue generated

Customers were scored and grouped based on RFM values to measure overall business impact.

🔹 4. Machine Learning Implementation
Data Scaling

StandardScaler was applied to normalize RFM values.

Optimal Cluster Selection

Elbow Method

Silhouette Score

Clustering Model

K-Means algorithm

Cluster labeling and interpretation

📊 Model Evaluation

The clustering performance was assessed using:

Inertia (Within-cluster sum of squares)

Silhouette Score

Visual cluster separation

The model demonstrated clear segmentation with distinguishable customer groups.

📈 Customer Segments Identified

The analysis revealed several meaningful segments:

🏆 Champions (High R, High F, High M)

💎 Loyal Customers

🛍 Occasional Buyers

⚠️ At-Risk Customers

🆕 New Customers

Each segment was analyzed in terms of revenue contribution and engagement level.

💼 Business Recommendations

Based on analytical findings:

Implement loyalty programs for high-value customers

Launch re-engagement campaigns for at-risk customers

Personalize marketing for frequent buyers

Optimize product strategies based on revenue drivers

These strategies can increase customer lifetime value (CLV) and improve retention rates.

🛠 Tools & Technologies

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

📁 Repository Structure
CAU-Data-Analytics-Project/
│
├── data/
├── notebooks/
├── src/
├── reports/
├── visuals/
└── README.md

🏆 Academic Contribution

This project demonstrates:

Application of statistical analysis techniques

Implementation of unsupervised machine learning

Real-world business problem solving

Analytical reasoning and data-driven decision making

✅ Conclusion

The project successfully identified key customer segments and provided strategic insights for improving revenue and customer retention.

By integrating statistical analysis with machine learning techniques, the study highlights the importance of data analytics in modern business decision-making.
