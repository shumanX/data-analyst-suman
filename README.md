# data-analyst-suman

 Goal: Improve the Fee Paid for Business Licenses in Vancouver
The main objective is to improve how fees for business licenses are managed and increased in Vancouver.
 1. Descriptive Metric: Average Fee Paid Annually
•	Objective: This step aims to determine the average amount of fees paid for business licenses annually.
•	Data Source: "Fee Paid Annually" is extracted from the operational data source, which provides historical data regarding the fees businesses pay to obtain or renew their licenses.
•	Purpose: It helps summarize the historical trends, giving a clear picture of the past average fees.
Supporting Operational Data Sources
Throughout this process, additional operational data sources are integrated:
•	Staff Meetings: Provides insights into discussions and decisions made by the staff.
•	Staff Calls: Includes records of calls and communications related to fee collection, business licensing, or other operational issues.
Data Centers and Infrastructure
The process involves two main data centers:
1. UCW Data Center (Vancouver)
•	The data related to the project is stored in Vancouver. The server contains various types of files:
•	Business License Files (Excel)
•	Staff Emails (JSON)
•	Meeting and Call Records
•	These files are marked with "AF-W/M/Q/Y," indicating the data could be categorized and stored by annual, monthly, weekly, or quarterly intervals.
2. AWS Data Center (Virginia)
•	This section includes a Data Analytics Platform designed for business licensing, where data from Vancouver is ingested for further analysis.
•	Data is stored in Amazon S3, under a bucket for the business license office with a structured hierarchy:
•	A bucket structure is defined under `BusinessLicense/Landing`.
 Data Ingestion Process
Data from Vancouver (UCW Data Center) is sent to the AWS Data Center through a data ingestion process. The ingested data will be utilized in the analytics platform to run the analyses required for improving the business license fees, leveraging AWS infrastructure for cloud-based analytics.
![Data Visualization](https://github.com/shumanX/data-analyst-suman/blob/main/Picture1.png)

In summary, this descriptive analysis shows the flow from identifying the problem (fees paid), using various metrics and data sources to understand and predict trends, and then using infrastructure (cloud-based and local servers) to store, analyze, and ultimately improve fee structures and business operations in Vancouver's Business License Office.
