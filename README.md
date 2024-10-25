Creating a Sales Insights Data Analysis for XYZ company that sales computer hardware and peripherals. 

Problem Statement: Sales Director of the company is facing difficulty in getting hold of various regional managers for sales insights and areas of improvements. So Power BI dashboards are to be introduced to the rescue.
It will help the Sales Director and other stakeholders to get a gist of what has performed well and what has not in a hassle free way.

Project Planning: Done using AIMS grid & data discovery. AIMS is a project management tool with 4 components to it.

AIMS components: 
1.Purpose: To unlock sales insights that are not visible before sales team for decision support & automate them to reduce manual time spent in data gathering.
2.Stakeholders: Sales Director, Marketing team, Customer Service Team, Data and Analytics Team & IT
3.End Result: An automated dashboard providing quick and latest sales insights in order to support data driven decisions.
4. Sucess Criteria: a) Dashboards uncovering sales order insights with latest available data
                    b) Sales team able to make better decisions and prove 10% cost savings of total spent.
                    c) Sales analysts stop gathering insights manually in order to save 20% of their business time and reinvest value added activities


Step A: Data discovered from mysql DB (Sales Management System) which will be the data source for the PowerBI platform.
To reduce any impact on mysql -OLTP(Online Transaction Processing System) and prevent its effect on sales/business of the organisation, all transformation (ETL) is applied and stores data in a 
Datawarehouse (Terra data, SNowflake etc.,). Apache,Nifi/Python pandas used for transformations.We transform the data in such a way that it is suitable for analytical queries.
Here, in this case study for simplicity we just plug in PowerBI with MySQL and carry on analytics without building a Data Warehouse.
 3 Main Steps:
 
Step B: Data Analysis using SQL.
Step B: Data Wrangling/Data Munching/ Data Cleaning + ETL with Power BI. Established STAR schema with Transaction TB as Fact Table and remaining as Dimenison TBs

Step C: Building Power BI dashboard/report





