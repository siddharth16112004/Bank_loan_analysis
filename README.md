# Financial_loan_analysis
In order to monitor and assess our bank's lending activities and performance, we need to create a comprehensive Bank Loan Report. This report aims to provide insights into key loan-related metrics and their changes over time. The report will help us make data-driven decisions, track our loan portfolio's health, and identify trends that can inform our lending strategies.

Dashboard 1: Summary

Key Performance Indicators (KPIs)

Total Loan Applications:

Calculate the total number of loan applications received during a specified period.
Monitor the Month-to-Date (MTD) Loan Applications.
Track changes Month-over-Month (MoM).
Total Funded Amount:

Understand the total amount of funds disbursed as loans.
Monitor the MTD Total Funded Amount.
Analyze MoM changes in this metric.
Total Amount Received:

Track the total amount received from borrowers to assess the bank's cash flow and loan repayment.
Analyze the MTD Total Amount Received.
Observe MoM changes.
Average Interest Rate:

Calculate the average interest rate across all loans.
Monitor MTD average interest rate.
Track MoM variations.
Average Debt-to-Income Ratio (DTI):

Evaluate the average DTI for borrowers to gauge their financial health.
Compute the average DTI for all loans.
Track MoM fluctuations.
Good Loan vs. Bad Loan KPIs
Good Loan KPIs:

Good Loan Application Percentage: Calculate the percentage of loan applications classified as 'Good Loans' (status: 'Fully Paid' and 'Current').
Good Loan Applications: Identify the total number of 'Good Loan' applications.
Good Loan Funded Amount: Determine the total amount of funds disbursed as 'Good Loans'.
Good Loan Total Received Amount: Track the total amount received from borrowers for 'Good Loans'.
Bad Loan KPIs:

Bad Loan Application Percentage: Calculate the percentage of loan applications categorized as 'Bad Loans' (status: 'Charged Off').
Bad Loan Applications: Identify the total number of 'Bad Loan' applications.
Bad Loan Funded Amount: Determine the total amount of funds disbursed as 'Bad Loans'.
Bad Loan Total Received Amount: Track the total amount received from borrowers for 'Bad Loans'.
Loan Status Grid View
To gain a comprehensive overview of our lending operations, we will create a grid view report categorized by 'Loan Status'. This report will analyze key indicators associated with different loan statuses, including 'Total Loan Applications,' 'Total Funded Amount,' 'Total Amount Received,' 'MTD Funded Amount,' 'MTD Amount Received,' 'Average Interest Rate,' and 'Average Debt-to-Income Ratio (DTI)'.

Dashboard 2: Overview
In our Bank Loan Report project, we aim to visually represent critical loan-related metrics and trends using various chart types to facilitate data-driven decision-making.

Chart Requirements
Monthly Trends by Issue Date (Line Chart):

Chart Type: Line Chart
Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
X-Axis: Month (based on 'Issue Date')
Y-Axis: Metrics' Values
Objective: Showcase how 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received' vary over time, identifying seasonality and long-term trends.
Regional Analysis by State (Filled Map):

Chart Type: Filled Map
Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
Geographic Regions: States
Objective: Visually represent lending metrics by state, identifying regions with significant lending activity and regional disparities.
Loan Term Analysis (Donut Chart):

Chart Type: Donut Chart
Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
Segments: Loan Terms (e.g., 36 months, 60 months)
Objective: Depict loan statistics based on different loan terms, understanding the distribution of loans across various term lengths.
Employee Length Analysis (Bar Chart):

Chart Type: Bar Chart
Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
X-Axis: Employee Length Categories (e.g., 1 year, 5 years, 10+ years)
Y-Axis: Metrics' Values
Objective: Illustrate lending metrics distribution among borrowers with different employment lengths, assessing the impact of employment history on loan applications.
Loan Purpose Breakdown (Bar Chart):

Chart Type: Bar Chart
Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
X-Axis: Loan Purpose Categories (e.g., debt consolidation, credit card refinancing)
Y-Axis: Metrics' Values
Objective: Provide a visual breakdown of loan metrics based on the stated purposes of loans, aiding in understanding borrowers' primary reasons for seeking financing.
Home Ownership Analysis (Tree Map):

Chart Type: Tree Map
Metrics: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
Hierarchy: Home Ownership Categories (e.g., own, rent, mortgage)
Objective: Display loan metrics categorized by different home ownership statuses, providing a hierarchical view of how home ownership impacts loan applications and disbursements.
These diverse chart types will enhance our ability to visualize and communicate loan-related insights effectively, supporting data-driven decisions and strategic planning within our lending operations.

#Over_View Dashboard
<img width="1325" height="666" alt="overview dashboard" src="https://github.com/user-attachments/assets/dd61a789-6ffa-4982-8d39-90de53ebd3ba" />

#Summary Dashboard
<img width="1327" height="665" alt="summary dashboard" src="https://github.com/user-attachments/assets/108eecf3-0362-48ec-b853-fc33d6c904df" />

Overview
This Power BI project analyzes various aspects of bank loans to provide valuable insights for decision-making. It comprises three main dashboards: Summary, Overview, and Details.

Dashboard 1: Summary
Key Performance Indicators (KPIs) Requirements:
Total Loan Applications: Calculate the total number of loan applications received during a specified period, including Month-to-Date (MTD) and Month-over-Month (MoM) changes.
Total Funded Amount: Understand the total amount of funds disbursed as loans, monitor MTD Total Funded Amount, and analyze MoM changes.
Total Amount Received: Track the total amount received from borrowers to assess cash flow and loan repayment, including MTD Total Amount Received and MoM changes.
Average Interest Rate: Calculate the average interest rate across all loans, MTD, and monitor MoM variations.
Average Debt-to-Income Ratio (DTI): Evaluate the average DTI for borrowers, compute the average DTI for all loans, MTD, and track MoM fluctuations.
Summary Visualization:
Loan Status Grid View: Gain a comprehensive overview of lending operations and monitor loan performance categorized by 'Loan Status'. This grid view provides insights into metrics such as Total Loan Applications, Total Funded Amount, Total Amount Received, MTD Funded Amount, MTD Amount Received, Average Interest Rate, and Average DTI.

Dashboard 2: Overview
Monthly Trends by Issue Date (Line Chart): Identify seasonality and long-term trends in lending activities.
Regional Analysis by State (Filled Map): Identify regions with significant lending activity and assess regional disparities.
Loan Term Analysis (Donut Chart): Understand the distribution of loans across various term lengths.
Employee Length Analysis (Bar Chart): Assess how lending metrics are distributed among borrowers with different employment lengths.
Loan Purpose Breakdown (Bar Chart): Provide a visual breakdown of loan metrics based on stated purposes of loans.
Home Ownership Analysis (Tree Map): View how home ownership impacts loan applications and disbursements hierarchically.
Dashboard 3: Details
Objective:
The Details Dashboard provides a comprehensive view of key loan-related metrics and data points, facilitating efficient access to critical information about loan portfolios, borrower profiles, and loan performance.

Dataset Used:
The bank loan analysis dataset comprises essential fields such as Loan ID, Address State, Purpose, Grade, Sub Grade, Annual Income, Loan Status, Last Payment Date, Verification Status, Debt-to-Income Ratio, and Interest Rates. These fields provide insights into borrower demographics, employment stability, loan characteristics, risk assessment, and payment behavior.

Conclusion:
The Details Dashboard streamlines access to critical loan data, facilitating informed decision-making, enhancing operational efficiency, optimizing lending strategies, mitigating risks, and maximizing overall performance.

#Summary Dashboard
<img width="1331" height="738" alt="image" src="https://github.com/user-attachments/assets/49da1705-71d7-4fc6-88d8-828fe88ce0cf" />

#Overview Dashboard
<img width="1326" height="745" alt="image" src="https://github.com/user-attachments/assets/4b578b5f-6d11-426d-ae64-b758312ef0de" />

#Details Dashboard
<img width="1317" height="733" alt="image" src="https://github.com/user-attachments/assets/ed51970c-a95f-4d08-b968-e229d470cac2" />

Contributing
Contributions to enhance the analysis or add new features are welcome! If you have any suggestions, ideas, or bug fixes, feel free to open an issue or submit a pull request.





