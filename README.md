<h1 align="center">H1B Insights Engine | Cloud-Based SQL ETL & Labor Market Analytics (2M+ Records)</h1>

This repository showcases an end-to-end **cloud-based ETL and SQL analytics pipeline** developed as a **team project** during my Master's in Business Analytics. As **project lead**, I designed the relational database schema, provisioned the cloud infrastructure, developed all SQL code, and oversaw the end-to-end analytical workflow. The project processed over **2 million H1B Labor Condition Application (LCA)** records to support labor market analysis and executive reporting.

Although the project uses **U.S. H1B labor certification data** as its case study, the techniques demonstrated such as **ETL development, relational database design, SQL analytics, cloud database deployment, data modeling, and executive reporting** are broadly transferable across business intelligence, data engineering, analytics, finance, healthcare, operations, and other data-driven domains.

Using **Power Query Editor**, **MySQL Workbench**, and a **cloud-hosted Azure MySQL database**, the project transformed four large raw datasets into a normalized relational database capable of supporting scalable SQL analysis and efficient querying.

The project concludes with an executive report summarizing labor market trends affecting international students pursuing H1B sponsorship while demonstrating the ability to communicate complex analytical findings to non-technical stakeholders.

# 🎯 Project Goals

The project was designed to build a scalable cloud-based ETL pipeline capable of transforming large public labor-market datasets into a normalized relational database for SQL analytics.

The primary objectives were to:

- Design and implement a normalized relational database schema.
- Build an end-to-end ETL pipeline for over **2 million** records.
- Clean and transform large raw datasets using Power Query Editor.
- Deploy the database to a cloud-hosted Azure MySQL server.
- Perform SQL-based labor market analyses.
- Provision secure read-only database access for stakeholders.
- Produce an executive report communicating key labor market insights.
- Demonstrate scalable database engineering and analytical workflows.

# 🏗️ Solution Architecture

## Workflow

```text
Raw H1B Labor Certification Data (4 CSV Files)
                    ↓
Data Cleaning & Transformation
                    ↓
Power Query ETL
                    ↓
Normalized Relational Schema Design
                    ↓
Azure MySQL Cloud Deployment
                    ↓
Bulk Data Loading
                    ↓
SQL Query Development
                    ↓
Labor Market Analytics
                    ↓
Executive Reporting
```

### Data

- **Primary Dataset:** H1B Labor Condition Application (LCA) Disclosure Data (FY2022)
- **Source:** U.S. Department of Labor
- **Volume:** 4 quarterly CSV files containing over **2 million** records
- **Focus:** H1B applications, prevailing wages, occupations, employers, industries, and geographic trends

### Data Preparation

Prepared the datasets for relational database storage by:

- Cleaning inconsistent values.
- Removing unnecessary attributes.
- Standardizing data types.
- Preparing records for bulk SQL import.
- Structuring reproducible ETL workflows across all quarterly datasets.

### ETL Pipeline

Developed a cloud-based ETL pipeline that:

- Imported four large CSV datasets.
- Performed transformations using Power Query Editor.
- Loaded cleaned data into Azure MySQL.
- Automated repeatable data preparation workflows.
- Produced normalized tables for downstream SQL analysis.

### Relational Database Design

Designed a normalized relational schema using **MySQL Workbench**, including:

- Entity identification.
- Primary and foreign key relationships.
- Normalized table structures.
- Referential integrity.
- Cloud-ready database deployment.

### Cloud Database Deployment

Provisioned and configured an **Azure MySQL** database to:

- Host the production database.
- Support remote SQL access.
- Enable secure stakeholder connectivity.
- Demonstrate cloud database administration.

### SQL Analytics

Developed SQL queries to analyze:

- Prevailing wages.
- Occupation demand.
- State-level application trends.
- Employer hiring activity.
- Industry sponsorship patterns.
- Willful violator impacts.

### Executive Reporting

Communicated analytical findings through a concise executive report summarizing key labor market trends relevant to international students pursuing H1B sponsorship.

# 📊 Analytical Insights

SQL analysis of over **2 million H1B labor certification records** identified several notable labor market trends across occupations, employers, industries, wages, and geographic regions.

### Prevailing Wage Trends

- Significant wage variation exists across occupations and industries.
- Specialized technical roles consistently command higher prevailing wages.
- Wage levels differ considerably between states and metropolitan areas.

### Occupation Demand

- Software and technology-related occupations account for a substantial share of H1B applications.
- Engineering, data, healthcare, and business roles also demonstrate strong demand.
- Sponsorship activity is concentrated among highly skilled occupations.

### Geographic Distribution

- H1B applications are concentrated in major economic and technology hubs.
- California, Texas, New York, and Washington account for a significant proportion of certified applications.
- Geographic patterns closely reflect regional industry specialization.

### Employer Sponsorship

- A relatively small number of employers account for a large share of H1B sponsorships.
- Large multinational organizations consistently submit the highest application volumes.
- Sponsorship activity varies considerably across industries.

### Labor Market Compliance

- Willful violator status represents only a small proportion of employers.
- SQL analysis enables rapid identification and comparison of employer compliance patterns.

# ⚠️ Project Limitations

- Analysis is limited to publicly available FY2022 H1B Labor Condition Application (LCA) data.
- Labor Condition Applications do not represent final H1B visa approvals.
- Some employer and occupation names required standardization during data preparation.
- Findings reflect a single fiscal year and may not capture long-term labor market trends.

# 📈 Analytical Recommendations

Based on the SQL analysis, several recommendations emerge:

- Focus job searches on occupations with consistently high sponsorship demand.
- Prioritize employers with established H1B sponsorship histories.
- Consider geographic regions demonstrating sustained hiring activity.
- Monitor prevailing wage trends when evaluating employment opportunities.
- Expand future analyses by incorporating multiple fiscal years to identify long-term labor market trends.

# 🛠️ Technical Skills Demonstrated

### Programming & Query Languages

- SQL

### Data Engineering

- ETL Pipeline Development
- Data Cleaning & Transformation
- Relational Database Design
- Data Modeling
- Database Normalization
- Bulk Data Import
- Cloud Database Deployment
- Database Administration

### Data Analytics

- SQL Query Development
- Labor Market Analytics
- Trend Analysis
- Geographic Analysis
- Employer Analysis
- Wage Analysis
- Executive Reporting

### Cloud & Database Technologies

- Azure MySQL
- MySQL Server
- Relational Database Management Systems (RDBMS)

### Software

- Power Query Editor
- MySQL Workbench
- Azure Database for MySQL
- AWS S3
- Microsoft Word
- Command Prompt

# 💡 What This Project Demonstrates

This project demonstrates the ability to design, build, and deploy an end-to-end cloud-based data engineering and SQL analytics solution using production-scale datasets.

Key competencies demonstrated include:

- Designing normalized relational databases.
- Developing scalable ETL workflows.
- Deploying cloud-hosted SQL databases.
- Managing large-scale structured datasets.
- Writing efficient analytical SQL queries.
- Transforming raw data into actionable business insights.
- Communicating technical findings through executive reporting.

Although centered on H1B labor market data, the workflow and technologies demonstrated are broadly transferable to business intelligence, data engineering, analytics, finance, healthcare, operations, and other data-driven industries.

# 📁 Repository Structure

```text
Datasets/
│
├── FY2022_Q1.7z
├── FY2022_Q2.7z
├── FY2022_Q3.7z
└── FY2022_Q4.7z

Outputs/
│
├── Final Cleaned Data.zip
├── Executive Summary.docx
├── Schema Screenshot.png
├── Schema.mwb
├── Command Prompt Video 1.mp4
└── Command Prompt Video 2.mp4

README.md
```

# 🚀 Replicating the Project

### Prerequisites

- Azure Database for MySQL
- MySQL Workbench
- Microsoft Power Query Editor
- AWS S3 (for large dataset storage)
- H1B Labor Condition Application (LCA) FY2022 datasets

### Repository Setup

Clone the repository:

```bash
git clone https://github.com/yourusername/h1b-insights-engine.git
```

### Data Preparation

1. Download the quarterly H1B datasets.
2. Extract the compressed archives.
3. Clean and transform the data using Power Query Editor.
4. Export the cleaned datasets for SQL import.

### Database Deployment

1. Create an Azure MySQL database.
2. Open the provided schema in MySQL Workbench.
3. Execute the schema to create the database structure.
4. Configure user permissions if remote access is required.

### Load the Data

Import the cleaned datasets into Azure MySQL using MySQL Workbench or the MySQL command-line client.

### Run the Analysis

Execute the SQL queries to analyze:

- Prevailing wages
- Occupation demand
- Employer sponsorship
- Geographic trends
- Labor market compliance

### Review the Outputs

The **Outputs** directory contains:

- Executive report
- Database schema
- Demonstration videos
- Cleaned datasets
- Supporting documentation

# 📬 Contact Me

For questions or collaboration, feel free to reach out.

**Email**  
Awaleiabdi@outlook.com

**LinkedIn**  
https://www.linkedin.com/in/awale-abdi/
