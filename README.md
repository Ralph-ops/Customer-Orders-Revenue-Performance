📌 Overview
A UK‑based non‑store online retail company specializing in unique all‑occasion gifts faced challenges in understanding customer purchasing behavior and revenue drivers. Using transactional data from December 2010 to December 2011, this project explores customer trends, revenue optimization opportunities, and builds decision‑support dashboards to improve profitability.

📊 Dataset
Source: UCI Machine Learning Repository (archive.ics.uci.edu in Bing)

Dataset: Online Retail (UK transactions)

Scope: 500,000+ transactions covering product descriptions, quantities, prices, customer IDs, and countries.

Period: Dec 2010 – Dec 2011

🛠 Tools & Technologies
Python (Pandas, NumPy, Matplotlib, Seaborn) – Data loading, cleaning, EDA, and transformation

MySQL – Structured storage and querying of prepared datasets

Power BI & Excel – Interactive dashboards and visual analytics

Microsoft PowerPoint – Presentation of insights and recommendations

🔄 Project Steps
Data Loading

Fetched dataset using from ucimlrepo import fetch_ucirepo

Imported into Python for preprocessing

Exploratory Data Analysis (EDA)

Identified missing values, duplicates, and anomalies

Analyzed customer purchase frequency, product performance, and revenue distribution

Data Cleaning & Transformation

Removed invalid records (negative quantities, missing customer IDs)

Created new features (e.g., purchase frequency, revenue per customer)

Database Integration

Connected Python to MySQL

Stored cleaned datasets for efficient querying and reporting

Dashboard Development

Built interactive dashboards in Power BI and Excel

Visualized KPIs: revenue trends, customer segmentation, product performance

Presentation

Summarized findings and recommendations in a professional PowerPoint deck

📈 Dashboard Highlights
Revenue Trends: Monthly and seasonal sales patterns

Customer Segmentation: One‑time vs repeat buyers

Top Products & Countries: High‑performing SKUs and regions

Profitability Drivers: Wholesale vs retail strategies

✅ Results
Identified seasonality patterns and off‑season revenue gaps

Segmented customers into one‑time vs repeat buyers with clear revenue contributions

Highlighted high‑potential EU markets for expansion

Proposed loyalty programs to improve retention and CLV

Recommended wholesale vs retail strategy segmentation for margin optimization

🚀 How to Run
Clone the repository and install dependencies (pip install -r requirements.txt).

Fetch dataset from UCI ML Repo using Python.

Run preprocessing scripts to clean and transform data.

Load prepared datasets into MySQL.

Open Power BI or Excel dashboards to explore KPIs.

Review insights and recommendations in the PowerPoint presentation.
