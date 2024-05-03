# Trucking-Risk-Analysis

Functionalities

This project is designed to analyze trucking data to enhance safety, efficiency, and compliance within the fleet using PySpark, Databricks, and AWS technologies. 
Key functionalities include:

Data Ingestion and Storage: Raw trucking data, such as mileage, gas usage, geolocation, events, and driver specifics, are stored in AWS S3 in CSV format.
Data Processing and Transformation: Utilizing Databricks for Spark session management to transform and analyze the trucking data effectively.
Event and Risk Analysis: Analyze driving events to identify risky behaviors and calculate a risk factor for each driver, helping prioritize interventions.

Architecture & Design

This project leverages AWS S3 for data storage and Databricks hosted on AWS for distributed data processing. PySpark is utilized for data processing and transformations, while visualizations are generated using Matplotlib to highlight key insights such as driver efficiency and event frequencies.

![image](https://github.com/PranavSheth12/Trucking-Risk-Analysis/assets/79102762/57896c94-e7f1-431a-8b43-d0cb3189cacb)

Deployment Instructions

Environment Setup:
Clone the GitHub repository to your local machine using: git clone https://github.com/PranavSheth12/Trucking-Risk-Analysis.git

Set up an AWS account and configure access to an S3 bucket.
Create a Databricks workspace and deploy a cluster.

Data Setup:
Upload the structured CSV data files to your configured S3 bucket.

Project Execution:
Open the Databricks workspace and import the notebook from the cloned repository.
Attach the notebook to your cluster and configure the Spark session to access the S3 data.
Execute the notebook to perform data transformations, analysis, and visualizations.

Steps to Run the Application

Ensure AWS credentials are set up for accessing S3.
Configure the Databricks cluster with the necessary Spark version and libraries.
Run the notebook cells sequentially to ingest, process, analyze the data, and view results.

Test Results

The application outputs several visualizations and metrics, such as the distribution of event types, driver efficiency scores, and calculated risk factors.
Detailed logs and output files can be found in the Databricks workspace or can be configured to store in AWS S3 for persistence and review.
