# Trucking Risk Analysis

## Functionalities

This project is designed to analyze trucking data to enhance safety, efficiency, and compliance within the fleet using PySpark, Databricks, and AWS technologies.

**Key functionalities include**:

- **Data Ingestion and Storage**: Raw trucking data, such as mileage, gas usage, geolocation, events, and driver specifics, are stored in AWS S3 in CSV format.

- **Data Processing and Transformation**: Utilizing Databricks for Spark session management to transform and analyze the trucking data effectively.

- **Event and Risk Analysis**: Analyze driving events to identify risky behaviors and calculate a risk factor for each driver, helping prioritize interventions.

## Architecture & Design

This project leverages AWS S3 for data storage and Databricks hosted on AWS for distributed data processing. PySpark is utilized for data processing and transformations, while visualizations are generated using Matplotlib to highlight key insights such as driver efficiency and event frequencies.

![Architecture Diagram](https://github.com/PranavSheth12/Trucking-Risk-Analysis/assets/79102762/57896c94-e7f1-431a-8b43-d0cb3189cacb)

## Deployment Instructions

### Environment Setup:

1. Clone the GitHub repository to your local machine using: `git clone https://github.com/PranavSheth12/Trucking-Risk-Analysis.git`
2. Set up an AWS account and configure access to an S3 bucket.
3. Create a Databricks workspace and deploy a cluster.

### Data Setup:

1. Upload the structured CSV data files to your configured S3 bucket.

### Project Execution:

1. Open the Databricks workspace and import the notebook from the cloned repository.
2. Attach the notebook to your cluster and configure the Spark session to access the S3 data.
3. Execute the notebook to perform data transformations, analysis, and visualizations.

## Steps to Run the Application

1. Ensure AWS credentials are set up for accessing S3.
2. Configure the Databricks cluster with the necessary Spark version and libraries.
3. Run the notebook cells sequentially to ingest, process, analyze the data, and view results.

## Test Results

The application outputs several visualizations and metrics, such as the distribution of event types, driver efficiency scores, and calculated risk factors.

Test results for the machine learning model's performance, including Root Mean Square
Error (RMSE) or other relevant metrics, can be found in the project's output or logs.

Detailed logs and output files can be found in the Databricks workspace or can be configured to store in AWS S3 for persistence and review.

# Screenshots of the work

## Creating Cluster
<img width="1044" alt="image" src="https://github.com/PranavSheth12/Trucking-Risk-Analysis/assets/79102762/8f485ed0-ad59-4451-9734-f50fb1008e41">

## Creating S3 bucket
<img width="556" alt="image" src="https://github.com/PranavSheth12/Trucking-Risk-Analysis/assets/79102762/448fc2b5-9991-4635-b619-aa7984216c32">

## Ingesting Data from S3 bucket
<img width="1199" alt="image" src="https://github.com/PranavSheth12/Trucking-Risk-Analysis/assets/79102762/094a3980-9740-48d5-8c82-56035be7f614">

## Data Transformations using Spark SQL
<img width="963" alt="image" src="https://github.com/PranavSheth12/Trucking-Risk-Analysis/assets/79102762/eae09d58-9644-4a32-933d-60b72f69aa5a">
<img width="544" alt="image" src="https://github.com/PranavSheth12/Trucking-Risk-Analysis/assets/79102762/1ffdb4bd-746b-4db7-a11e-67e959d7e5ad">
<img width="972" alt="image" src="https://github.com/PranavSheth12/Trucking-Risk-Analysis/assets/79102762/350e18b0-6006-4d98-834b-4bb4327f1ae4">

## Visualisations
<img width="1273" alt="image" src="https://github.com/PranavSheth12/Trucking-Risk-Analysis/assets/79102762/14ba7c6c-2181-404c-bbfa-b172a974e994">
<img width="758" alt="image" src="https://github.com/PranavSheth12/Trucking-Risk-Analysis/assets/79102762/57cc9028-cdd2-4345-b60e-e9b490bcce88">
<img width="510" alt="image" src="https://github.com/PranavSheth12/Trucking-Risk-Analysis/assets/79102762/3b90d3c7-ebf8-44d2-95ea-e3b82a831e7e">
<img width="481" alt="image" src="https://github.com/PranavSheth12/Trucking-Risk-Analysis/assets/79102762/310d83d8-ad5b-407d-b201-7373721f126b">
<img width="1275" alt="image" src="https://github.com/PranavSheth12/Trucking-Risk-Analysis/assets/79102762/2855ce4f-2bc0-46a3-9483-46022087916a">

## Risk factor prediction model using spark SQL and matplotlib
<img width="1270" alt="image" src="https://github.com/PranavSheth12/Trucking-Risk-Analysis/assets/79102762/91b62d63-781f-410d-88cc-4e6e2b4dc093">
<img width="955" alt="image" src="https://github.com/PranavSheth12/Trucking-Risk-Analysis/assets/79102762/20fdb8ec-2542-4f8c-bc50-6764c9e530dc">
<img width="824" alt="image" src="https://github.com/PranavSheth12/Trucking-Risk-Analysis/assets/79102762/fa34944b-17a1-4428-adce-dfd7e2e5e629">









