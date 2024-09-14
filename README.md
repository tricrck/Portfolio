# Data Analytics Portfolio

## Data Wrangling Project

### Project Title: Data Analytics Platform (DAP) Implementation for Enhanced Admission Procedures at UCW Registrar's Office

#### Objective
The primary goal of this project was to implement a Data Analytics Platform (DAP) to improve the performance of admission procedures at the University Canada West (UCW) Registrar's Office. By leveraging AWS services and following a structured data analytics approach, the project aimed to enhance the efficiency, accuracy, and insights derived from the admission process data.

#### Background
The UCW Registrar's Office had accumulated data from various aspects of the admission process, including applications, admission requirements, enrollment, and staff interactions. However, this data was often scattered across different systems, making it challenging to derive meaningful insights. The implementation of a DAP facilitated better decision-making and more efficient admission procedures.

#### Dataset
The data wrangling process involved various datasets, including:
- Applications: Containing applicant details such as name, date of birth, gender, application date, and desired major.
- Admission Requirements: Information on specific requirements for each program.
- Enrollment Data: Records of successful enrollments.
- Staff Interactions: Data from staff emails, meetings, and calls related to the admission process.

#### Methodology
The project followed a 15-step Data Analytics Platform implementation process:
1. Data Analytical Question Formulation
2. Data Discovery
3. Data Storage Design
4. Test Dataset Generation
5. Data Ingestion
6. Data Storage
7. Data Pipeline Design
8. Data Cleaning
9. Data Structuring
10. Data Pipeline Implementation
11. Data Analysis
12. Data Visualization
13. Data Publishing
14. Data Enriching
15. Data Protection

#### AWS Architecture and Tools

![Data Wrangling DAP](https://github.com/tricrck/Portfolio/blob/main/images/DW.jpg)

The DAP utilized the following AWS services and components:
1. Amazon S3: For data storage, with multiple buckets for different stages of data processing.
2. AWS Glue: For data integration and ETL (Extract, Transform, Load) processes.
3. AWS Glue DataBrew: For data preparation and transformation.
4. Amazon Athena: For querying data stored in S3.
5. Amazon QuickSight: For data visualization and dashboard creation.
6. Amazon EC2: For hosting custom applications or processing tasks.

The architecture also included:
- Data pipelines for the Registrar's Office
- Data Catalog for metadata management
- Web Server and General Server for hosting applications

#### Key Metrics
The project focused on four types of metrics:
1. Descriptive Metric: Application Completion Rate 
   - Data Source: Applications
2. Diagnostic Metric: Error Rate in Application Submission 
   - Data Source: Admission Requirements
3. Predictive Metric: Application Yield Rate 
   - Data Source: Enrollment
4. Prescriptive Metric: Application Resource Allocation Index 
   - Data Sources: Staff Email, Staff Meeting, Staff Calls

#### Data Flow
1. Raw data was ingested into the "Admission/Landing" S3 bucket.
2. Data was then processed and moved to the "Admission/Raw" bucket.
3. Further processing occurred, and data was stored in the "Admission/Trusted" bucket.
4. Finally, curated data was stored in the "Admission/Curated" bucket.
5. The curated data was then used for analysis, visualization, and creation of data products.

#### Security and Compliance
The architecture included security measures, as indicated by the security-related icons in the bottom-left corner of the image.

#### Deliverables
1. A fully implemented Data Analytics Platform on AWS
2. Cleaned and transformed datasets ready for analysis
3. Interactive dashboards for visualizing key admission metrics
4. Documentation of the data wrangling and analysis processes
5. Recommendations for improving admission procedures based on the insights gained

#### Timeline
The project timeline was 9 weeks.

## Descriptive Analysis Project

### Project Title: Implementing an AWS-Based Data Analytics Platform to Optimize Business License Issuance in Vancouver

#### Objective
The primary goal of this project was to design and implement a Data Analytics Platform (DAP) on AWS for the City of Vancouver, focusing on optimizing the business license issuance process. Through this platform, we aimed to enhance operational efficiency, improve decision-making, and streamline the city's data management capabilities.

![Descriptive Analysis DAP](https://github.com/tricrck/Portfolio/blob/main/images/DA.jpg)

#### Dataset
The dataset included business license information from the City of Vancouver's Open Data Portal, containing the following key features:
- License Number: Unique identifier for each business license
- Business Name
- Issue Date
- Expiration Date
- Business Category
- Geographic Information

#### Methodology
1. Data Collection and Preparation
2. Data Storage Design
3. Data Ingestion
4. Data Processing and ETL
5. Data Analysis
6. Data Visualization
7. Data Access and Distribution
8. Automation and Orchestration

#### Tools and Technologies
- AWS Services: S3, EC2, Glue, Athena, QuickSight, Glue DataBrew
- Data Analysis: SQL (via Athena), Python (for custom ETL scripts if needed)
- Data Visualization: Amazon QuickSight

#### Deliverables
- Fully functional AWS-based Data Analytics Platform
- Automated ETL pipelines for data processing and preparation
- Interactive QuickSight dashboards presenting key insights on business license issuance
- Detailed reports on Business License Issue Rate and process efficiency
- Recommendations for optimizing the business license issuance process based on data-driven insights

## Data Quality Control Project

### Project Title: Implementation of Data Quality Control Measures in AWS Data Analytic Platform for The City of Vancouver

#### Objective
The primary objective of this project was to establish a comprehensive Data Quality Control (DQC) framework within the AWS Data Analytic Platform for the City of Vancouver. This framework ensures the accuracy, security, consistency, and reliability of data, enhancing the city's ability to make informed decisions and manage resources efficiently.

#### Background
As the City of Vancouver continued to expand its data-driven initiatives, maintaining high data quality was crucial for accurate analytics and decision-making. The AWS Data Analytic Platform project involved processing vast amounts of business license data. However, issues such as data security, governance, and monitoring needed to be addressed to ensure the platform's effectiveness and reliability.

![Data Quality Control DAP](https://github.com/tricrck/Portfolio/blob/main/images/DQC.jpg)

#### Scope
The project focused on the following key areas:
- Data Protection
- Data Governance
- Data Monitoring

#### Methodology
1. Current State Assessment
2. Data Protection (Step 15)
3. Data Governance (Step 16)
4. Data Monitoring (Step 17)
5. Validation Rules and Procedures
6. Training and Best Practices
7. Feedback Mechanism

#### Tools and Technologies
- AWS Key Management Service (KMS) for data encryption
- AWS Glue for metadata management and data cataloging
- Amazon CloudWatch for monitoring data quality metrics and generating alerts
- AWS Trusted Advisor and AWS CloudTrail for security auditing and operational insights

#### Deliverables
- A comprehensive Data Quality Control framework, including data protection, governance, and monitoring processes
- Real-time monitoring dashboards visualizing data quality metrics

#### Timeline
The project was completed in 1 week, covering assessment, implementation, validation, training, and continuous monitoring setup.

This Data Quality Control initiative within the AWS Data Analytic Platform ensured the City of Vancouver's data is secure, well-governed, and reliable, enhancing data-driven decision-making and operational efficiency.
