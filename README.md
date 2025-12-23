
# Insurance-Analysis

### Dashboard Link : https://app.powerbi.com/links/oDxN2pLLOT?ctid=d8d099a6-07db-4517-8615-314cd9ffc39f&pbi_source=linkShare

## Problem Statement

Insurance companies manage diverse datasets related to policies, customers, premiums, and claims. Without proper analysis, it becomes challenging to monitor claim behavior, identify loss-driving segments, and evaluate policy performance. This project aims to analyze insurance data to understand claim trends, customer risk profiles, and premium-to-claim relationships, enabling data-driven decisions for underwriting, pricing, and risk management.

This dashboard helps the companies understand their customers better. It helps the companies know if their customers are satisfied with their services. Through different policies, they get to know their improvement area, & thus they can improve their services by identifying these area. It also lets them know the pending requests & rejected requests, thus since by using this dashboard they have identified this problem, they can further work on factors responsible for these unwanted problem.

Since, number of pending/rejected requests are more than settled customers , thus in all they must work on improving their strategies. 

Also since Inactive policy status is huge (41.87%), thus they must try to reduce it.

### Steps followed 

- Step 1 : Open Power BI Service -> Select workspace -> Create Dataflow -> Add DataSource -> Connect to the Data Source.
- Step 2 : Open Power BI Desktop -> Connect to Power BI Dataflows -> Select Workspace & Dataflow.
- Step 3 : Load data into Power BI Desktop, dataset is a csv file.
- Step 4 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 4 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 5 : In the report view, under the view tab, theme was selected. 
- Step 6 : Visual filters (Slicers) were added for three fields named "Policy Number", "Claim Number", & "Customer ID".
- Step 7 : Three card visuals were added to the canvas, one representing Premium Amount,second representing Coverage Amount & other representing Claim Amount.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
- Step 8 : A Ribbon chart was also added to the report design area representing the number of Claims by Claim Status.
- Step 9 : A Bar chart was also added to the report design area representing the Premium Amount by Policy Type. 
- Step 10 : A Line chart was also added to the report design area representing the Claim Amount by Age Group.
- Step 11 : A Donut chart was also added to the report design area representing the Count of Policy Status.
- Step 12 : A Multi-row Card was also added to the report design area to segregate the single according to the "Gender".
- Step 13 : A Matrix was also introduced to the report  design area to generate table Policy Type and Claim Status.
- Step 14 : In the report view, under the insert tab, a text box was added to the canvas, in which name of the company was mentioned.
- Step 15 : The report was then published to Power BI Service.
 
# Snapshot of Dashboard (Power BI Service)

![Screenshot 2025-12-23 201841](https://github.com/user-attachments/assets/c65dc56c-8d02-4b5f-9699-326f55c5cc11)

 
 # Report Snapshot (Power BI DESKTOP)

 ![Screenshot 2025-12-23 202115](https://github.com/user-attachments/assets/6088ae62-d639-4d18-ba2e-87e58fabecc0)


# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Number of Customers = 10004

   Number of  Customers (Male) = 5003 (50.01 %)

   Number of  Customers (Female) = 5001 (49.99 %)



           thus, Number of Male and Female Customers is  almost same .

### [2] Total Premium Amount = 5.98M

   Total Premium Amount (Male) = 2.99M (50.00 %)

   Total Premium Amount (Female) = 2.99M (50.00 %)



           thus, Total Premium of Amount Male and Female Customers is equal .    

### [3] Total Coverage Amount = 600.55M

   Total Premium Amount (Male) = 298.92M (49.77 %)

   Total Premium Amount (Female) = 301.63M (50.23 %)



           thus, Female Customers Have had  higher coverage amount.   

### [4] Total Claim Amount = 16.91M

   Total Claim Amount (Male) = 8.50 (50.26 %)

   Total Claim Amount (Female) = 8.41M (49.74 %)



           thus,  Male Customers receives Higher claim amount. 

 ### [5] Some other insights
 
 ### Policy Status
 
 1.1) 41.87 % customers had Inactive policy status.
 
 1.2) 58.13 % customers had Active policy status.
 
 
         thus, maximum customers had Active policy status.
 
 ### Premium Amount
 
 2.1)  2.5M premium amount is paid for Travel.
 
 2.2)  1.2M premium amount is paid for Health.
 
 2.3)  1.0M premium amount is paid for Automobiles.
 
 2.4)  0.7M premium amount is paid for Life.

 2.5)  0.6M premium amount is paid for Home.
 
         thus, Highest premium amount is paid for Travel.
         
### Number of Claims

3.1) 4.4k application have Rejected.

3.2) 3.4k application have Settled.

3.2) 2.3k application have Pending.
       
       thus, Most Applicants are not eligible for Insurance.

### Claim Amount

4.1) 8.8M claim amount have received by Adult.

4.1) 6.4M claim amount have received by Elder.

4.1) 1.7M claim amount have received by Young Adult.

        thus, Most Claim Amount have received by Adult.



