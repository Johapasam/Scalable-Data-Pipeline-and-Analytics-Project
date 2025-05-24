🚖 Scalable Data Pipeline and Analytics Project 

This project demonstrates an end-to-end data engineering pipeline for analyzing Uber trip data. It leverages Google Cloud Platform (GCP) services, Python, Mage (an open-source data pipeline tool), BigQuery, and Looker Studio to automate ETL processes, perform data transformations, and create interactive dashboards for insightful analytics.
GitHub
+4
GitHub
+4
GitHub
+4

📌 Project Overview

Objective: To build a scalable data pipeline that ingests, processes, and visualizes Uber trip data, enabling data-driven decision-making.
Key Features:
Automated data ingestion and transformation using Mage.
Data storage and querying with BigQuery.
Interactive dashboards created in Looker Studio.
Insights into trip patterns, peak hours, and operational efficiency.
GitHub
+4
GitHub
+4
GitHub
+4
GitHub
GitHub
+4
GitHub
+4
GitHub
+4
arXiv
+1
GitHub
+1
🛠️ Technologies Used

Programming Language: Python
Cloud Platform: Google Cloud Platform (GCP)
Google Cloud Storage
Compute Engine
BigQuery
Data Pipeline Tool: Mage
Data Visualization: Looker Studio
GitHub
GitHub
+4
GitHub
+4
GitHub
+4
GitHub
+4
GitHub
+4
GitHub
+4
GitHub
+3
GitHub
+3
GitHub
+3
🗂️ Dataset

Source: NYC TLC Trip Record Data
Description: Contains detailed records of taxi trips in New York City, including pick-up/drop-off times and locations, trip distances, fares, payment types, and passenger counts.
Data Dictionary: TLC Trip Record Data Dictionary
GitHub
+8
GitHub
+8
GitHub
+8
GitHub
+4
GitHub
+4
GitHub
+4
🧱 Architecture

The project follows a modular architecture:

Data Ingestion:
Raw CSV data is uploaded to Google Cloud Storage.
Data Processing:
Mage orchestrates the ETL pipeline:
Extract: Data is read from Cloud Storage.
Transform: Data cleaning and transformation are performed using Python.
Load: Processed data is loaded into BigQuery.
Data Analysis:
SQL queries in BigQuery extract insights from the data.
Data Visualization:
Looker Studio connects to BigQuery to create interactive dashboards.
GitHub
+1
GitHub
+1
GitHub
GitHub
+4
GitHub
+4
GitHub
+4
📊 Dashboard

An interactive dashboard has been created in Looker Studio, showcasing key metrics such as:

Total trips over time
Peak hours and days
Average trip distances
Revenue analysis
GitHub
GitHub
+2
GitHub
+2
GitHub
+2
GitHub
Note: Please refer to the Uber_Dashboard_final.pdf in the repository for a snapshot of the dashboard.

📁 Repository Structure


Uber-Data-Engineering-Project/
├── mage_files/                 # Mage pipeline configurations
├── Uber_Dashboard_final.pdf    # Dashboard snapshot
├── big_query.sql               # SQL queries for analysis
├── uber data engineering.ipynb # Jupyter notebook with ETL code
├── uber data model.pdf         # Data model diagram
└── uber_data.csv               # Sample dataset
🚀 Getting Started

Clone the Repository:
git clone https://github.com/tejobaddula/Uber-Data-Engineering-Project.git
Set Up GCP Services:
Create a project in GCP.
Enable BigQuery, Cloud Storage, and Compute Engine APIs.
Create a Cloud Storage bucket and upload the dataset.
Set up a Compute Engine VM for running Mage.
arXiv
+7
GitHub
+7
GitHub
+7
Install Mage:
SSH into your VM and install Mage following the official guide.
GitHub
+3
GitHub
+3
GitHub
+3
Configure the Pipeline:
Use the configurations in the mage_files/ directory to set up your pipeline.
Modify the ETL code in uber data engineering.ipynb as needed.
GitHub
Run the Pipeline:
Execute the pipeline to process and load data into BigQuery.
Create the Dashboard:
Connect Looker Studio to your BigQuery dataset.
Use the provided SQL queries to build visualizations.
GitHub
+4
GitHub
+4
GitHub
+4
GitHub
+2
GitHub
+2
GitHub
+2
📈 Insights and Outcomes

Identified peak demand hours and days for Uber rides.
Analyzed revenue trends and trip distances.
Provided data-driven recommendations for operational improvements.
GitHub
+4
GitHub
+4
GitHub
+4
🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

📄 License

This project is licensed under the MIT License. See the LICENSE file for details.


