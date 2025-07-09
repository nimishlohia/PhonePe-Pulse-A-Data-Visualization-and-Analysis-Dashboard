# PhonePe-Pulse-A-Data-Visualization-and-Analysis-Dashboard

🌐 Overview

PhonePe Pulse Dashboard is a full-fledged Streamlit application designed to visualize and analyze digital transaction data across India using PhonePe's open datasets. This project connects to a MySQL database and presents deep insights into various transaction types, user trends, district-level activity, and mobile brand usage.

🔧 Technologies Used

Python (Pandas, Plotly, Requests)

Streamlit for frontend dashboard

MySQL for backend data storage

PyMySQL for MySQL connection

Plotly Express for interactive data visualizations

📊 Features

Aggregated Insurance & Transaction Analysis (Yearly & Quarterly)

User Device Brand Insights

District-Wise Mapping using GeoJSON Choropleths

Map-Level Insights on Insurance, Transactions, and User Engagement

Top Pincode-Based Analytics

Top Charts for Most/Least Active States and Districts

Export DataFrames as CSV

Interactive Filters (Year, Quarter, State)

Embedded Video Demonstrations of PhonePe Services

📂 Folder Structure

ACTUAL PROJECT/
├── phonepe.py                # Main Streamlit App
├── videos/                    # Promotional videos used in dashboard
│   └── PHONEPE.mp4
├── DATASETS/                 # CSV exports of MySQL tables
│   ├── aggregated_insurance.csv
│   ├── map_transaction.csv
│   └── ...
└── README.md

⚡ Installation & Run

Clone this repo or download files

Ensure you have MySQL running with the database phonepe_data populated

Install dependencies:

pip install streamlit pymysql pandas plotly streamlit-option-menu

Run the app:

streamlit run "path_to/phonepe.py"

Note: If your path has spaces or parentheses, enclose it in quotes.

📊 Data Sources

Public PhonePe Pulse GitHub datasets

Transformed and stored into MySQL with structured schema

📄 Author

Nimish LohiaB.Tech CSE (AI) | Bennett UniversityInternship: LabmentixEmail: nimish.lohia1855@gmail.com

🌟 Acknowledgements

PhonePe Pulse

Streamlit

Plotly

MySQL
