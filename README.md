## Overview
This project enables seamless visualization of **DynamoDB data** in **Amazon QuickSight** using **AWS Athena** and **Lambda**. It integrates various AWS services to build an efficient data analytics pipeline.

<img width="1890" height="851" alt="Architecture Diagram" src="https://github.com/user-attachments/assets/619e0f53-4440-4510-8d4e-8f9420b0baac" />


## Technologies Used
- **Amazon DynamoDB**
- **AWS Lambda**
- **AWS Athena**
- **Amazon QuickSight**
- **AWS Glue**
- **Amazon S3**

## Features
- **DynamoDB Table Setup** with partition & sort keys
- **AWS Athena Integration** using Lambda DynamoDB Connector
- **S3 Spill Location** for Athena query results
- **IAM Role Configuration** for QuickSight access
- **Data Import & Visualization** in QuickSight (SPICE & Direct Query)

<img width="1600" height="824" alt="Task List" src="https://github.com/user-attachments/assets/75145451-72b9-4195-879c-40ee08b73a89" />


- **Custom Dashboards** with Donut Charts, Bar Charts, and Interactive Tables

<img width="587" height="301" alt="Task By Category" src="https://github.com/user-attachments/assets/6e77a9f4-f441-4b8d-9b7a-56fc8303f7e9" />

<img width="580" height="328" alt="Task Completion Status" src="https://github.com/user-attachments/assets/2a0165f4-d4bf-49ca-8b32-383deb106a67" />


- **Live Data Updates** by syncing DynamoDB changes with QuickSight
- **Cost Efficiency**: Entire setup runs at a minimal cost
