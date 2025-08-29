# 📊 Nexus DataLens – Cloud-Native Automated Data Analytics Pipeline

Nexus DataLens is a serverless, end-to-end automated data analytics pipeline built on Amazon Web Services (AWS).
It helps businesses and data professionals transform raw, unstructured CSV files into clean, structured insights without manual effort or deep technical expertise.

Through a simple web interface, users upload raw data, and the system autonomously executes the pipeline: ingestion, cleaning, cataloging, and visualization — accelerating data-to-decision workflows in a secure, scalable, and cost-effective way.

## 📌 Table of Contents

1. [Project Overview](#-project-overview)  
2. [Features](#-features)  
3. [Architecture](#-architecture)  
4. [Tech Stack](#-tech-stack)  
5. [How It Works](#-how-it-works)  
6. [Screenshots](#-screenshots)  
7. [Live Demo](#-live-demo)  
8. [Setup Instructions](#-setup-instructions)  
9. [Future Enhancements](#-future-enhancements)  
10. [Contact](#-contact)

## 🌍 Project Overview

Data analytics often requires time-consuming manual processing before insights can be generated.
Nexus DataLens automates this by enabling:
- Easy CSV upload via a web interface
- Data cleaning & preparation with AWS Glue DataBrew
- Schema cataloging using AWS Glue Crawlers & Data Catalog
- Visualization in Amazon QuickSight or Power BI
- Scalable & serverless architecture for low-cost analytics
This project demonstrates the power of AWS serverless and event-driven architectures for modern data engineering.

## ✨ Features

✅ Simple CSV upload through a web interface
✅ Automated data cleaning & transformation with Glue DataBrew
✅ Schema detection & metadata cataloging via Glue Crawlers
✅ Ready-to-use dashboards in QuickSight / Power BI
✅ Secure, scalable, and fully serverless backend
✅ Automated pipeline triggered on file upload
✅ Cost-efficient, pay-as-you-go cloud solution

## 🏗 Architecture
<img width="940" height="625" alt="image" src="https://github.com/user-attachments/assets/7a2d15f0-b26a-455f-94ea-e3d30f8c73f3" />

## Architecture Flow

- User uploads CSV via web interface → stored in Amazon S3
- AWS Lambda triggers Glue DataBrew job for cleaning
- Glue Crawlers update schema in Glue Data Catalog
- Data made query-ready for QuickSight / Power BI dashboards

## AWS Services Used:
- Amazon S3 – Data lake for raw CSV storage
- AWS Lambda – Serverless orchestration & triggers
- AWS Glue DataBrew – Data cleaning & transformation
- AWS Glue Crawlers & Data Catalog – Schema cataloging
- Amazon QuickSight / Power BI – Visualization layer
- Amazon CloudFront + S3 – Hosting for web interface

## ⚙ Tech Stack

Frontend: HTML, CSS, JavaScript
Backend: Node.js (AWS Lambda)
Data Processing: AWS Glue DataBrew
Cataloging: AWS Glue Crawlers + Data Catalog
Visualization: Amazon QuickSight / Power BI
Storage: Amazon S3
Orchestration: AWS Lambda + EventBridge
CI/CD: AWS CodePipeline, AWS CodeBuild
IaC: AWS CloudFormation

## 🔄 How It Works

- User uploads CSV file → S3 bucket
- Lambda function triggers DataBrew cleaning workflow
- Glue Crawlers scan & update schema in Glue Data Catalog
- Data becomes queryable and ready for dashboards
- QuickSight/Power BI generates visual insights for end users

## 📸 Screenshots

Upload CSV Page
<img width="940" height="468" alt="image" src="https://github.com/user-attachments/assets/2a0f3ea6-1548-4746-91a5-f04285ebfd70" />

Cleaned Data Preview
<img width="940" height="410" alt="image" src="https://github.com/user-attachments/assets/c04d81dd-a008-43d7-b56a-8ef7290592b2" />

QuickSight Dashboard Example
<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/80ee8c85-205b-42c6-9a5a-b260c20999e9" />


## 🎥 Live Demo

▶ Coming soon...






## 📬 Contact

👤 Sahil Shaikh
📧 sahilshaikhh313@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/sahilshaikh78
