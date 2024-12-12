Exploratory Data Analysis

Project Description:
Exploratory Data Analysis of School Distribution in Vancouver

Project Title:
School Distribution in Vancouver: A Focus on Renfrew-Collingwood

Objective:
The primary goal of this project is to perform an exploratory data analysis (EDA) on the City of Vancouver's school data to understand the distribution of different school categories across the city, with a specific focus on the Renfrew-Collingwood area. By analyzing the number of public, independent, and StrongStart BC schools, we aim to identify areas with the highest concentration of schools and gain insights into the educational resources available in different neighborhoods.

Dataset:
The dataset consists of a list of schools in Vancouver, with the following information:

-ADDRESS: The street address of the school.
-SCHOOL_CATEGORY: The type of school (e.g., Independent School, Public School, StrongStart BC).
-SCHOOL_NAME: The official name of the school.
-Geom: Geographical coordinates of the school in JSON format.
-Geo Local Area: The local area or neighborhood where the school is located.
-geo_point_2d: Latitude and longitude of the school in a simplified format.

Methodology:
Data Collection and Preparation:
-Data was injected into AWS S3.
-Data profiling and cleaning were performed using AWS Data Group services.
-An ETL pipeline was created using AWS Glue to prepare the data for analysis.

Descriptive Statistics:
The total number of schools in Vancouver was calculated, along with the number of schools in each category (public, independent, StrongStart BC).
The number of schools of each category in the Renfrew-Collingwood area was identified.

Area Focus:
The Renfrew-Collingwood area was identified as having the highest number of schools. The distribution of school types within this area was analyzed.

Comparative Analysis:
The proportion of each school type in Renfrew-Collingwood was compared to the overall proportion of each school type in the entire city of Vancouver.

Insights and Findings:
-The city of Vancouver has a total of 194 schools, including 121 public schools, 54 independent schools, and 19 StrongStart BC schools.
-The Renfrew-Collingwood area has 13 public schools, 6 independent schools, and 2 StrongStart BC schools, demonstrating a high concentration of educational resources in this area.
-Renfrew-Collingwood's distribution of school types was compared to the overall city distribution to highlight any significant differences. For example, is the proportion of independent schools higher or lower in Renfrew-Collingwood compared to the city average?

Conclusion:
The analysis highlighted the concentration of schools in the Renfrew-Collingwood area. Further analysis could explore factors contributing to this concentration, such as population density, demographics, or city planning.

Tools and Technologies:
-AWS S3 (for data storage)
-AWS Data Group services (for data profiling and cleaning)
-AWS Glue (for ETL)
-AWS KMS (for encryption)
-AWS CloudWatch (for monitoring)
-AWS CloudTrail (for user activity tracking)

Deliverables:
A summary report outlining the analysis process, findings, and comparisons between Renfrew-Collingwood and the city of Vancouver.
This EDA project provides insights into the distribution of schools in Vancouver, focusing on the Renfrew-Collingwood area and its high concentration of educational resources. 
![WhatsApp Image 2024-12-11 at 8 25 20 PM](https://github.com/user-attachments/assets/fd3c5f15-bdbb-48ce-b2cd-3a3d75d7e8ee)

Descriptive Analysis

Project Description:
Descriptive Analysis of School Distribution in Vancouver

Project Title:
Understanding School Distribution in Vancouver

Objective:
The primary goal of this project is to conduct a descriptive analysis of the City of Vancouver's school data. Through this analysis, we aim to summarize key characteristics of school distribution across the city, identify patterns in school locations, and provide a comprehensive overview of the educational resources available.

Dataset:
The dataset consists of a list of schools in Vancouver, with the following information:

-ADDRESS: The street address of the school.
-SCHOOL_CATEGORY: The type of school (e.g., Independent School, Public School, StrongStart BC).
-SCHOOL_NAME: The official name of the school.
-Geom: Geographical coordinates of the school in JSON format.
-Geo Local Area: The local area or neighborhood where the school is located.
-geo_point_2d: Latitude and longitude of the school in a simplified format.

Methodology:

Data Collection and Preparation:
-Data was injected into AWS S3.
-Data profiling and cleaning were performed using AWS Data Group services.
-An ETL pipeline was created using AWS Glue to prepare the data for analysis and to calculate the number of public schools in the city.

Descriptive Statistics:
-Calculated the total number of schools in Vancouver.
-Calculated the number of schools in each category (public, independent, StrongStart BC).
-Determined the distribution of schools across different local areas (Geo Local Area) within Vancouver.

School Category Analysis:
-Analyzed the proportion of each school category relative to the total number of schools in the city.
-Identified which local areas have a higher or lower concentration of particular school categories.

Insights and Findings:
-The city of Vancouver has a total of 194 schools.
-There are 121 public schools, 54 independent schools, and 19 StrongStart BC schools.

Recommendations:
Based on the distribution analysis, recommendations could be made regarding resource allocation, future school planning, or addressing any potential imbalances in access to different school categories across Vancouver.

Tools and Technologies:
-AWS S3 (for data storage)
-AWS Data Group services (for data profiling and cleaning)
-AWS Glue (for ETL and data preparation)
-AWS KMS (for encryption)
-AWS CloudWatch (for monitoring)
-AWS CloudTrail (for user activity tracking)

Deliverables:
-A report summarizing the methods, findings, and analysis of school distribution in Vancouver.
-This descriptive analysis provides a comprehensive overview of school distribution in Vancouver, enabling stakeholders to understand the current landscape of educational resources and inform future planning and decision-making.
![WhatsApp Image 2024-12-11 at 8 25 20 PM](https://github.com/user-attachments/assets/fe38bb57-0ee6-4e47-8269-d6858a94b09b)

Diagnostic Analysis

Project Description:
Diagnostic Analysis of Complaints at UCW

Project Title:
Investigating the Factors Related to Witness Presence in UCW Complaints

Objective:
The primary goal of this project is to conduct a diagnostic analysis to identify factors associated with the presence or absence of witnesses in workplace bullying and harassment complaints at UCW. By analyzing the complaint data, we aim to uncover trends and patterns that might explain why some complaints have witnesses while others do not, providing insights for improving prevention and reporting processes.

Background:
UCW's HR department maintains a complaint file for workplace bullying and harassment. Understanding the circumstances surrounding complaints, including the presence or absence of witnesses, is crucial for effective intervention and prevention. This analysis seeks to understand potential factors influencing witness presence, which can inform strategies for promoting a safer reporting environment.

Dataset:
The analysis will utilize the UCW HR department's complaint file for workplace bullying and harassment. This dataset includes:
-Complaint ID: A unique identifier for each complaint.
-Employee ID: A unique identifier for the employee filing the complaint.
-Department: The department where the alleged incident occurred.
-Complaint Date: The date the complaint was formally filed.
-Nature of Complaint: A description of the type of bullying or harassment alleged.
-Incident Date: The date the alleged incident occurred.
-Location: The location where the alleged incident occurred.
-Gender: The gender of the employee filing the complaint.
-Witnesses: Information about whether any witnesses were present.
-Evidence Provided: Information about whether any evidence was provided with the complaint.

Methodology:
Data Collection and Preparation:
The cleaned and transformed dataset from the Data Wrangling project (using AWS Data Brew) will be used for this analysis. This dataset is categorized by the presence or absence of witnesses.

Comparative Analysis:
Compare characteristics of complaints with witnesses to those without witnesses. This includes comparing distributions of:
-Department: Are complaints from certain departments more likely to have witnesses?
-Nature of Complaint: Are certain types of complaints more likely to have witnesses?
-Incident Date/Time: Do incidents occurring at certain times or days have a higher likelihood of witnesses?
-Location: Do incidents occurring in specific locations have a higher likelihood of witnesses?
-Gender: Is the gender of the complainant associated with witness presence?
-Evidence Provided: Is there a relationship between evidence provided and witness presence?

Synthesis of Findings:
Integrate the findings from the comparative and statistical/qualitative analyses to identify potential factors associated with the presence or absence of witnesses.

Tools and Technologies:
AWS Data Brew.

Deliverables:
-A report summarizing the analysis process, findings, and potential factors associated with witness presence in complaints.
-Recommendations for UCW based on the findings, focusing on strategies to encourage reporting and witness involvement.

Timeline:
Expected completion of the project: [2 weeks].

This diagnostic analysis aims to provide UCW with actionable insights into the factors related to witness presence in workplace bullying and harassment complaints, ultimately contributing to a more transparent and supportive reporting environment.
![WhatsApp Image 2024-12-11 at 8 12 16 PM](https://github.com/user-attachments/assets/81cc9f9b-93c8-48fc-9503-55a0d7d66f0c)

Data Wrangling

Project Description:
Data Wrangling for UCW HR Complaint Data Analysis

Project Title:
Preparing UCW's Workplace Bullying and Harassment Complaint File for Analysis

Objective:
The primary goal of this project is to perform comprehensive data wrangling to prepare a robust dataset from UCW's HR complaint file related to workplace bullying and harassment. By cleaning, transforming, and organizing the data, the project aims to enhance its usability for subsequent analysis, specifically to understand the prevalence of complaints with and without witnesses.

Background:
UCW's HR department maintains a complaint file regarding workplace bullying and harassment. This data, while valuable, requires preparation before it can be effectively analyzed. The data may contain inconsistencies, missing information, or be structured in a way that makes it difficult to extract meaningful insights. This data wrangling project addresses these issues to facilitate a clear understanding of complaint patterns.

Dataset:
The data wrangling process focuses on the UCW HR department's complaint file for workplace bullying and harassment. This dataset contains the following information about each complaint:
-Complaint ID: A unique identifier for each complaint.
-Employee ID: A unique identifier for the employee filing the complaint.
-Department: The department where the alleged incident occurred.
-Complaint Date: The date the complaint was formally filed.
-Nature of Complaint: A description of the type of bullying or harassment alleged.
-Incident Date: The date the alleged incident occurred.
-Location: The location where the alleged incident occurred.
-Gender: The gender of the employee filing the complaint.
-Witnesses: Information about whether any witnesses were present.
-Evidence Provided: Information about whether any evidence was provided with the complaint.

Methodology:
Data Collection:
The raw complaint file was ingested into AWS Data Brew.

Data Assessment:
AWS Data Brew's profiling capabilities were used to assess the data, identifying data types, missing values, and potential inconsistencies.

Data Cleaning:
AWS Data Brew's data cleaning recipes were used to address any identified data quality issues, such as inconsistencies in formatting or data entry errors. The specific cleaning steps performed are documented within the Data Brew recipes.

Data Transformation:
The primary transformation performed was categorizing complaints based on the presence or absence of a witness. This was done using AWS Data Brew's transformation features to create two distinct datasets or flags within a single dataset:
-Complaints with witnesses.
-Complaints without witnesses.

Data Consolidation:
Since the data originated from a single source (the complaint file), no data consolidation was required. The transformation created distinct categories within the dataset, effectively creating two subsets for analysis.

Documentation and Validation:
-The entire data wrangling process is documented within AWS Data Brew, including the recipes used for cleaning and transformation.
-Validation was performed by reviewing the resulting datasets (complaints with and without witnesses) to ensure accurate categorization.

Tools and Technologies:
-AWS Data Brew (for data profiling, cleaning, and transformation).
-Draw.io (for visualizing the data wrangling process/data flow).

Deliverables:

-A transformed dataset within AWS Data Brew, categorized by the presence or absence of witnesses.
-Documentation of the data wrangling process within AWS Data Brew, including the recipes used.
-A visualization of the data wrangling process using Draw.io.

Timeline:
Expected completion of the data wrangling process: [1 week].

This data wrangling project prepares UCW's HR complaint data for analysis, specifically enabling a clear comparison of complaints with and without witnesses. This will allow for more targeted investigations and interventions related to workplace bullying and harassment.
![WhatsApp Image 2024-12-11 at 8 12 16 PM](https://github.com/user-attachments/assets/91de26b1-b342-4dee-bb09-e837ffecf9d4)

Data Quality Control

Project Description:
Data Quality Control for UCW HR Complaint Data

Project Title:
Ensuring Data Quality in UCW's Workplace Bullying and Harassment Complaint File

Objective:
The primary objective of this project is to establish a comprehensive Data Quality Control (DQC) framework for UCW's HR complaint file regarding workplace bullying and harassment. This framework will ensure the accuracy, completeness, consistency, and reliability of the data, enhancing the ability to analyze trends, identify problem areas, and implement effective interventions.

Background:
UCW's HR department maintains a complaint file related to workplace bullying and harassment. Maintaining high-quality data in this file is crucial for understanding the prevalence and nature of these issues within the organization. Inaccurate or incomplete data can hinder effective analysis and lead to ineffective or even harmful interventions. This project aims to implement robust data quality control measures to mitigate these risks.

Dataset:
The Data Quality Control process focuses on the UCW HR department's complaint file for workplace bullying and harassment. This dataset contains the following information about each complaint:
-Complaint ID: A unique identifier for each complaint.
-Employee ID: A unique identifier for the employee filing the complaint.
-Department: The department where the alleged incident occurred.
-Complaint Date: The date the complaint was formally filed.
-Nature of Complaint: A description of the type of bullying or harassment alleged.
-Incident Date: The date the alleged incident occurred.
-Location: The location where the alleged incident occurred.
-Gender: The gender of the employee filing the complaint.
-Witnesses: Information about whether any witnesses were present.
-Evidence Provided: Information about whether any evidence was provided with the complaint.

Scope:
The project focuses specifically on the complaint file data and includes the following key areas:
-Data Profiling: Analyzing the existing complaint file to assess current data quality levels.
-Data Cleansing: Developing and implementing processes within AWS Glue to address missing values and redact sensitive information.
-Data Validation: Implementing validation rules within the ETL process to ensure data integrity during ingestion and transformation.
-Monitoring and Reporting: Monitoring the ETL process and data quality metrics through AWS Glue's monitoring capabilities and custom logs.

Methodology:
Current State Assessment:
-Reviewed the existing structure and content of the complaint file.
-Identified key data fields relevant to analysis (e.g., date of complaint, nature of complaint, department involved, outcome).

Data Profiling:
Used AWS Glue's data profiling capabilities to analyze the complaint file and identify instances of missing values and assess the presence of sensitive data requiring redaction.

Establish Data Quality Metrics:
Defined key metrics:
-Percentage of records with missing values in critical fields.
-Number of records with successfully redacted sensitive information.
-Number of records processed and passed to the "passed" folder vs "failed" folder.

Data Cleansing Processes:
Developed an ETL pipeline using AWS Glue to perform the following:
-Check for missing values in key fields. Records with missing values were moved to a "failed" folder for further review.
-Redact sensitive information (e.g., names, addresses, specific details that could identify individuals) using appropriate string manipulation functions within AWS Glue.
-Data that passed both quality checks (no missing values and successful redaction) was moved to a "passed" folder for analysis.

Validation Rules and Procedures:
-Implemented validation rules within the AWS Glue ETL job to check for missing values and ensure proper redaction.
-The ETL process itself acts as the validation mechanism, separating clean data from data requiring attention.

Monitoring and Reporting:
Utilized AWS Glue's monitoring features to track the progress and success of the ETL jobs.
Implemented logging within the Glue job to track the number of records processed, passed, and failed. This information served as a basis for monitoring data quality metrics.

Training and Best Practices:
While this project focuses on automating quality control, documentation was created outlining the ETL process and data quality rules. This documentation serves as a resource for maintaining and improving the process.

Feedback Mechanism:
The "failed" folder acts as a feedback mechanism, allowing for review of data that did not meet quality standards. This review can inform adjustments to the ETL process or data entry procedures.

Tools and Technologies:
-AWS Glue (for ETL, data profiling, and data cleansing).
-Draw.io for visualization of the ETL process.

Deliverables:
-A documented AWS Glue ETL job implementing data quality checks and redaction.
-"Passed" and "Failed" data folders in S3.
-Documentation of the ETL process, data quality rules, and monitoring procedures.
-Visualization of the ETL process using draw.io.

Timeline:
Expected completion of the DQC implementation: [2 weeks].

This Data Quality Control initiative empowers UCW's HR department to maintain high-quality data in its complaint file, enabling more effective analysis, reporting, and intervention related to workplace bullying and harassment.
![WhatsApp Image 2024-12-11 at 8 23 03 PM](https://github.com/user-attachments/assets/66a89d9b-4af0-4f19-9198-2d24327288bf)
