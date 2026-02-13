# DA-and-ML-PJT1

📊 **CAU Data Analytics Project** 
Advanced Customer Segmentation & Sales Intelligence Analysis

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________

📌 **Executive Summary**

This project presents a comprehensive analytical study of online retail transaction data conducted as part of the Data Analytics course at CAU.

The primary objective is to analyze customer purchasing behavior, measure customer value using quantitative methods, and apply machine learning techniques for meaningful customer segmentation.

Through structured preprocessing, statistical exploration, RFM modeling, and clustering algorithms, the project delivers actionable insights aimed at improving customer retention and revenue optimization.

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________

🎯 **Project Objectives**

The key objectives of this project are to design and implement a structured analytical workflow that transforms raw transactional data into business intelligence.

The project focuses on applying statistical reasoning, feature engineering, and unsupervised machine learning techniques to identify customer patterns and segment behavior effectively.

Additionally, the study aims to translate analytical findings into practical, data-driven business recommendations.

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________

👥 **Project Team**

| Role            | Team Member              | Student ID | Responsibility                                                               |
| --------------- | ------------------------ | ---------- | ----------------------------------------------------------------------------  |
| 🧭 Project Lead | **Tursunaliev Hasanboy** | 202490339  | Project coordination                                                         |
| 📊 Data Analyst | **Kim Stanislav**        | 202490171  | Data preprocessing,                                                          |
| 🤖 ML Engineer  | **Yun Yuriy**            | 202490384  | Clustering implementation                                                    |

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________

🗂 **Dataset Description**

The project utilizes the Online Retail Transaction Dataset, which contains transactional data from an e-commerce platform.

The dataset includes variables such as invoice number, product information, quantity, pricing, customer identification, and geographic location.

These attributes enable multi-dimensional analysis of customer behavior and revenue generation patterns.

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________

⚙️ **Methodology**

The project follows a structured analytical pipeline to ensure methodological clarity and reproducibility.

Each stage builds upon the previous one, transforming raw data into strategic business insights.

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________

🔹 **1. Data Preprocessing**

The preprocessing stage focuses on improving data quality and reliability.

Missing values and duplicate records are handled systematically to ensure dataset integrity.

Negative values corresponding to cancelled transactions are filtered out to maintain transactional accuracy.

InvoiceDate is converted into datetime format to enable time-series analysis.

A new feature, Revenue (Quantity × UnitPrice), is created to quantify financial contribution.

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________

🔹 **2. Exploratory Data Analysis (EDA)**

Exploratory analysis is conducted to understand distribution patterns and trends.

Time-based revenue trends are examined to identify seasonal effects and growth patterns.

Country-level comparisons highlight geographical sales performance differences.

Top-performing products are identified based on revenue contribution.

Statistical metrics such as mean, median, and standard deviation are used to summarize data characteristics.

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________

🔹 **3. RFM Analysis**

RFM modeling is applied to evaluate customer value using three core metrics.

Recency measures the time since the last purchase.

Frequency calculates the number of transactions per customer.

Monetary represents the total revenue generated by each customer.

Customers are scored and categorized based on their RFM profiles to determine overall engagement and profitability.

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________

🔹 **4. Machine Learning Implementation**

To ensure comparability across features, data normalization is performed using StandardScaler.

The optimal number of clusters is determined using the Elbow Method and Silhouette Score analysis.

The K-Means clustering algorithm is then applied to segment customers into distinct behavioral groups.

Cluster visualization techniques are used to interpret and validate segmentation quality.

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________

📊 **Model Evaluation**

Clustering performance is evaluated using quantitative metrics to ensure robustness.

Inertia values are analyzed to measure within-cluster variance.

Silhouette Score is used to assess cluster separation and cohesion.

The results demonstrate meaningful segmentation with clear differentiation between customer groups.

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________

📈 **Customer Segments Identified**

The analytical process revealed several distinct customer segments.

Champions represent high-value customers with strong engagement and revenue contribution.

Loyal Customers show consistent purchasing behavior over time.

Occasional Buyers demonstrate moderate activity and growth potential.

At-Risk Customers require re-engagement strategies to prevent churn.

New Customers represent acquisition success and future potential.

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________

💼 **Business Recommendations**

Based on analytical findings, strategic actions are proposed.

High-value customers should be targeted with loyalty programs and exclusive offers.

At-risk customers should receive personalized re-engagement campaigns.

Marketing strategies should be optimized based on purchasing frequency and revenue contribution patterns.

Data-driven decision-making can significantly enhance customer lifetime value and long-term profitability.

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________

🛠 **Tools & Technologies**

The project was implemented using Python and industry-standard data science libraries.

Pandas and NumPy were used for data manipulation and numerical analysis.

Matplotlib and Seaborn were applied for data visualization.

Scikit-learn was utilized for machine learning modeling and evaluation.

All analysis was conducted in a Jupyter Notebook environment.

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________

📁 **Repository Structure**
CAU-Data-Analytics-Project/
│
├── data/               # Raw and processed datasets
├── notebooks/          # Jupyter notebooks
├── src/                # Python scripts
├── reports/            # Analytical reports
├── visuals/            # Charts and visual outputs
└── README.md           # Project documentation

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________

🏆 **Academic Contribution**

This project demonstrates the integration of statistical analysis and machine learning techniques in solving real-world business problems.

It reflects strong analytical reasoning, methodological rigor, and structured problem-solving skills.

The study highlights how data analytics can transform raw transactional data into strategic intelligence.

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________

**✅ Conclusion**

The CAU Data Analytics Project successfully identified meaningful customer segments and generated strategic insights.

By combining statistical methods with unsupervised machine learning, the project illustrates the practical value of data analytics in business decision-making.

The results provide a foundation for targeted marketing, improved retention strategies, and sustainable revenue growth.
