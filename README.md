# Healthcare-Disease-Analytics
GCP Data Engineer
End-to-end data pipeline on Google Cloud Platform using Cloud Storage, BigQuery, and Cloud Composer (Airflow) for batch data processing and analytics.

📝 **Project Description:**

This project focuses on building a GCP-based data pipeline and analytics platform for public health data across countries and years. It processes structured healthcare datasets containing disease prevalence, incidence, mortality, treatment details, and socio-economic indicators such as income, education, and urbanization.

**Key goals include:**

Understanding disease trends by age group, gender, and country.

Analyzing the impact of healthcare access and infrastructure (e.g., doctors, hospital beds).

Correlating treatment types, cost, and vaccine availability with recovery and DALYs.

Evaluating socioeconomic influence (income, education, urbanization) on public health outcomes.

Monitoring 5-year health improvements and regional disparities.

**Dataset**:
Used Global Health Data official dataset for analysing data.

**global_health_data.csv** - This dataset contains the following information like Country, Year, Disease Name, Disease Category, Prevalence Rate, Incidence Rate, Mortality Rate,	Age, Group, Gender, Population Affected, etc.

**Technologies Used:**

**Cloud :** Google Cloud Platform (GCP)

**Data Lake:** Google Cloud Storage (GCS)

GCS is used to store and manage the transactional data

**CLI:** gsutil, gcloud, bq

**Workflow orchestration:** Airflow (Cloud Composer)

Composer, a managed Apache Airflow service, is utilized to orchestrate Dataflow jobs

**Data Warehouse:** Google BigQuery

BigQuery serves as a serverless data warehouse which is pay-u-go which is built using Machine Learning Algorithms where it is cost effective along with built in infra structure

**Transformation:** PySpark (DataBricks)

Dataflow, based on Apache Beam, is responsible for data processing, transformation, and loading into BigQuery

**Visualisation:** Google Data Studio

Looker, a business intelligence and analytics platform, is employed to generate daily reports

These technologies work together to efficiently process, store, and generate reports on the daily transaction data.

**Procedure:**

1.Dowloaded the dataset from Kaggle.

2.Designed the GCP complete architecture.

3.Created a data pipeline using Airflow for processing the dataset, uploading it to the datalake, moving the data from the data lake to the data warehouse.

4.Transform the data in the data warehouse using ETL (extract, transform and load) tool and prepare it for analytics and visualisations.

<img width="500" alt="workflow" src="https://github.com/user-attachments/assets/82ba754a-696c-412f-93c4-8659d43941d8" />



