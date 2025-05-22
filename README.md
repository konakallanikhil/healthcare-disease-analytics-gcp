# Healthcare-Disease-Analytics
GCP Data Engineer
End-to-end data pipeline on Google Cloud Platform using Cloud Storage, BigQuery, and Cloud Composer (Airflow) for batch data processing and analytics.

📝 **Project Description:**

This project focuses on building a GCP-based data pipeline and analytics platform for public health data across countries and years. It processes structured healthcare datasets containing disease prevalence, incidence, mortality, treatment details, and socio-economic indicators such as income, education, and urbanization.

The pipeline uses Cloud Storage for raw data ingestion, Cloud Composer (Airflow) for orchestration, BigQuery for transformation and analysis, and Looker Studio or BigQuery BI Engine for visualization.

**Key goals include:**

Understanding disease trends by age group, gender, and country.

Analyzing the impact of healthcare access and infrastructure (e.g., doctors, hospital beds).

Correlating treatment types, cost, and vaccine availability with recovery and DALYs.

Evaluating socioeconomic influence (income, education, urbanization) on public health outcomes.

Monitoring 5-year health improvements and regional disparities.

**Technologies Used:**

GCS is used to store and manage the transactional data

Composer, a managed Apache Airflow service, is utilized to orchestrate Dataflow jobs

Dataflow, based on Apache Beam, is responsible for data processing, transformation, and loading into BigQuery

BigQuery serves as a serverless data warehouse

Looker, a business intelligence and analytics platform, is employed to generate daily reports

These technologies work together to efficiently process, store, and generate reports on the daily transaction data.

<img width="500" alt="workflow" src="https://github.com/user-attachments/assets/82ba754a-696c-412f-93c4-8659d43941d8" />



