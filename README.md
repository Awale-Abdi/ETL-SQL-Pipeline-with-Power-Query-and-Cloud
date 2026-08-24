<h1 align="center">Cloud-Based SQL ETL & Labor Market Analytics (2M+ Records)</h1>

This repository showcases an end-to-end **cloud-based ETL and SQL analytics pipeline** developed as a **team project** during my Master's in Business Analytics. As **project lead**, I designed the relational database schema, provisioned the cloud infrastructure, developed all SQL code, and oversaw the end-to-end analytical workflow. The project processed over **2 million H1B Labor Condition Application (LCA)** records to support labor market analysis and executive reporting.

Although the project uses U.S. H1B labor certification data as its case study, the techniques demonstrated such as ETL development, relational database design, SQL analytics, cloud database deployment, data modeling, and executive reporting are broadly transferable across business intelligence, data engineering, finance, operations, supply chain, marketing, retail, healthcare, insurance, manufacturing, consulting, human resources, workforce analytics, and other data-driven domains.

Using **Power Query Editor**, **MySQL Workbench**, and a **cloud-hosted Azure MySQL database**, the project transformed four large raw datasets into a normalized relational database capable of supporting scalable SQL analysis and efficient querying.

The project concludes with an executive report summarizing labor market trends affecting international students pursuing H1B sponsorship while demonstrating the ability to communicate complex analytical findings to non-technical stakeholders.

## 🎯 Project Goals

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

## 🏗️ Solution Architecture

#### Workflow

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

#### Data

- **Primary Dataset:** H1B Labor Condition Application (LCA) Disclosure Data (FY2022)
- **Source:** U.S. Department of Labor
- **Volume:** 4 quarterly CSV files containing over **2 million** records
- **Focus:** H1B applications, prevailing wages, occupations, employers, industries, and geographic trends

#### Data Preparation

Prepared the datasets for relational database storage by:

- Cleaning inconsistent values.
- Removing unnecessary attributes.
- Standardizing data types.
- Preparing records for bulk SQL import.
- Structuring reproducible ETL workflows across all quarterly datasets.

#### ETL Pipeline

Developed a cloud-based ETL pipeline that:

- Imported four large CSV datasets.
- Performed transformations using Power Query Editor.
- Loaded cleaned data into Azure MySQL.
- Automated repeatable data preparation workflows.
- Produced normalized tables for downstream SQL analysis.

#### Relational Database Design

Designed a normalized relational schema using **MySQL Workbench**, including:

- Entity identification.
- Primary and foreign key relationships.
- Normalized table structures.
- Referential integrity.
- Cloud-ready database deployment.

#### Cloud Database Deployment

Provisioned and configured an **Azure MySQL** database to:

- Host the production database.
- Support remote SQL access.
- Enable secure stakeholder connectivity.
- Demonstrate cloud database administration.

#### SQL Analytics

Developed SQL queries to analyze:

- Prevailing wages.
- Occupation demand.
- State-level application trends.
- Employer hiring activity.
- Industry sponsorship patterns.
- Willful violator impacts.

#### Executive Reporting

Communicated analytical findings through a concise executive report summarizing key labor market trends relevant to international students pursuing H1B sponsorship.

## 📊 Analytical Insights

SQL analysis of over **2 million H1B labor certification records** identified several notable labor market patterns across wages, occupations, employers, geographic regions, and employer compliance.

#### Prevailing Wage Trends

- The average prevailing wage across the analyzed applications was approximately **$75,816**.
- Prevailing wages varied substantially across occupations, industries, and geographic regions.
- Specialized occupations, particularly certain medical roles, ranked among the highest-paying positions in the dataset.
- Compensation therefore represents an important additional dimension when comparing sponsorship opportunities across occupations.

#### Occupation Demand

- Software development represented one of the strongest areas of H1B sponsorship activity.
- Mechanical engineering and medical and clinical laboratory occupations also demonstrated substantial application volumes.
- Sponsorship activity was concentrated among highly skilled and specialized occupations.
- Several highly compensated medical specialties, including radiology, critical care, obstetrics, breast surgery, and vascular surgery, appeared among the highest-paying occupations analyzed.

#### Geographic Distribution

- H1B sponsorship activity was concentrated in several major labor markets.
- **California, New York, New Jersey, Texas, and Pennsylvania** recorded particularly high application volumes.
- These concentrations indicate substantial employer demand for H1B-sponsored labor within those states.
- Geographic analysis demonstrated that sponsorship opportunities are distributed unevenly across the United States.

#### Employer Sponsorship & Compliance

- Employer sponsorship patterns varied substantially across the analyzed records.
- Employers classified as **willful violators** exhibited markedly different application and rejection patterns from non-willful violators in the project analysis.
- Willful violators required more than **10 times as many applications** relative to the comparison described in the executive analysis.
- Employer compliance history therefore emerged as an important consideration alongside occupation, geography, and compensation.

#### Labor Market Decision Support

- No single variable provides a complete picture of the H1B labor market.
- Combining **prevailing wages, occupation demand, geographic concentration, employer sponsorship activity, and compliance information** provides a stronger framework for evaluating employment opportunities.
- The analysis demonstrates how large-scale administrative data can be transformed into practical decision-support insights through relational databases and SQL analytics.

## ⚠️ Project Limitations

- The analysis is limited to publicly available **FY2022 H1B Labor Condition Application (LCA)** data.
- Labor Condition Applications represent employer filings and **do not represent final H1B visa approvals**.
- High application volume indicates sponsorship activity and labor demand but should not be interpreted as a higher probability of receiving an H1B visa.
- Some employer and occupation names required standardization during data preparation.
- Findings reflect a single fiscal year and may not capture longer-term changes in wages, occupations, employer behavior, or geographic demand.
- The analysis does not incorporate subsequent H1B petition, lottery, adjudication, or final visa outcome data.
- Observed relationships should therefore be interpreted as **labor-market and sponsorship patterns rather than causal determinants of H1B approval**.

## 📈 Analytical Recommendations

Based on the SQL analysis, several recommendations emerge for international students and other professionals evaluating H1B sponsorship opportunities:

- Target roles with compensation at or above prevailing wage requirements, using approximately **$75,816** as the average prevailing wage observed within the analyzed dataset.
- Prioritize occupations demonstrating high levels of H1B sponsorship activity, particularly software development, engineering, and specialized healthcare roles.
- Consider major sponsorship markets such as **California, New York, New Jersey, Texas, and Pennsylvania**, where application volumes indicate substantial demand for H1B-sponsored labor.
- Evaluate employers' H1B sponsorship histories when identifying prospective employment opportunities.
- Review employer compliance status and exercise additional caution when considering organizations classified as **willful violators**.
- Compare both sponsorship activity and compensation when evaluating occupations, since the highest-volume occupations are not necessarily the highest-paying.
- Consider highly compensated specialized occupations where relevant to an individual's qualifications and career path.
- Monitor prevailing wages, geographic demand, occupation trends, and employer sponsorship patterns together rather than evaluating any single factor in isolation.
- Expand future analyses across multiple fiscal years and incorporate H1B petition and approval data to distinguish labor-market demand from actual visa outcomes.

## 🛠️ Technical Skills Demonstrated

#### Programming & Query Languages

- SQL

#### Data Engineering

- ETL Pipeline Development
- Data Cleaning & Transformation
- Relational Database Design
- Data Modeling
- Database Normalization
- Bulk Data Import
- Cloud Database Deployment
- Database Administration

#### Data Analytics

- SQL Query Development
- Labor Market Analytics
- Trend Analysis
- Geographic Analysis
- Employer Analysis
- Wage Analysis
- Executive Reporting

#### Cloud & Database Technologies

- Azure MySQL
- MySQL Server
- Relational Database Management Systems (RDBMS)

#### Software

- Power Query Editor
- MySQL Workbench
- Azure Database for MySQL
- AWS S3
- Microsoft Word
- Command Prompt

## 💡 What This Project Demonstrates

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

## 📁 Repository Structure

```text
Cloud-SQL-ETL-Pipeline/
│
├── Datasets/
│   └── README.md
│       └── Download links to the original FY2022 H1B datasets (.7z)
│
├── Outputs/
│   └── README.md
│       └── Download links to cleaned datasets, schema files,
│           executive report, and demonstration videos
│
└── README.md
    └── Project documentation
```

**Datasets**

Contains download links to the original quarterly FY2022 H1B Labor Condition Application datasets hosted on AWS S3.

**Outputs**

Contains download links to the project's final deliverables, including:

- Cleaned datasets
- Executive report
- MySQL schema files
- Schema diagram
- Command-line demonstration videos

## 🚀 Replicating the Project

#### Prerequisites

- Azure Database for MySQL
- MySQL Workbench
- Microsoft Power Query Editor
- MySQL command-line client (optional)

#### Access the Project Files

Open the repository's:

```text
Datasets/
```

directory and use the provided AWS S3 links to download the four original FY2022 H1B datasets.

Then open:

```text
Outputs/
```

to access the cleaned datasets, schema files, executive report, and demonstration videos.

#### Data Preparation

1. Extract the quarterly H1B dataset archives.
2. Clean and transform the data using Power Query Editor.
3. Standardize data types and required fields.
4. Export the cleaned datasets for SQL import.

#### Database Deployment

1. Create an Azure Database for MySQL instance.
2. Open the provided schema file in MySQL Workbench.
3. Execute the schema to recreate the relational database structure.
4. Configure user permissions if remote stakeholder access is required.

#### Load the Data

Import the cleaned datasets into Azure MySQL using MySQL Workbench or the MySQL command-line client.

#### Run the Analysis

Execute the SQL queries to reproduce analyses of:

- Prevailing wages
- Occupation demand
- Employer sponsorship activity
- Geographic trends
- Labor market compliance

#### Review the Results

Compare the reproduced database and analyses with the materials available in:

```text
Outputs/
```

including the:

- Executive report
- Database schema
- Schema diagram
- Cleaned datasets
- Demonstration videos

## 📬 Contact Me

For questions or collaboration, feel free to reach out.

**Email**  
Awaleiabdi@outlook.com

**LinkedIn**  
https://www.linkedin.com/in/awale-abdi/
