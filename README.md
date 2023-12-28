# Employee Data: Performance of Employee
## Introduction
In this period, employees are employed after rigorous tests, interviews and trainings. After being employed, it is recommended to engage the employees on continuous trainings (like workshops) for personal development to improve their productivity. Performance of an employee can be measured using the parameters like engagement score, performance score, satisfaction score, work-life balance score and current employee rating. The objectives of this analysis are to track employee metrics such as employee turnover, training, and performance.
## The Data
The data contains different tables including engagement-survey data, recruitment data, training and development data. The data contains exactly 3,000 sampled employee with unique ID numbers.
## Rating System for Satisfaction Score, Work-Life Balance and Current Employee Rating:
5= Excellent performance
4= Very good performance
3= Good performance
2= Poor performance
1= Very poor performance 	
## Project Tool Used: Excel
## Analysis Questions 
The business questions to look into in this project are the following:
1. Can you create a pivot table to summarize the total number of employees in each department?
2. Apply conditional formatting to highlight employees with a "Performance Score" below 3 in red.
3. Calculate the average "Satisfaction Score" for male and female employees separately using a pivot table.
4. Create a chart to visualize the distribution of "Work-Life Balance Score" for different job functions.
5. Filter the data to display only terminated employees and find out the most common "Termination Type."
6. Calculate the average "Engagement Score" for each department using a pivot table.
7. Use VLOOKUP to find the supervisor's email address for a specific employee.
8. Can you identify the department with the highest average "Employee Rating?"
9. Create a scatter plot to explore the relationship between "Training Duration (Days)" and "Training Cost."
10. Build a pivot table that shows the count of employees by "RaceDesc" and "GenderCode."
11. Use INDEX and MATCH functions to find the "Training Program Name" for an employee with a specific ID.
12. Create a multi-level pivot table to analyze the "Performance Score" by "BusinessUnit" and "JobFunctionDescription."
13. Design a dynamic chart that allows users to select and visualize the performance of any employee over time.
14. Calculate the total training cost for each "Training Program Name" and display it in a bar chart.
15. Apply advanced conditional formatting to highlight the top 10% and bottom 10% of employees based on "Current Employee Rating."
16. Use a calculated field in a pivot table to determine the average "Engagement Score" per year.
17. Can you build a macro that automates the process of updating and refreshing all pivot tables in the workbook?
18. Create a histogram to understand the distribution of "ExitDate" for terminated employees.
19. Utilize the SUMPRODUCT function to calculate the total training cost for employees in a
specific location.
20. Develop a dashboard that provides an overview of key HR metrics, including headcount, performance, and training costs, using charts and pivot tables.
## Availability of Data
- The provided data would be good enough for the analysis to answer the business questions asked.
## Data Cleaning Process
The missing values in the ExitDate column were replaced with “Nill” while the rows with “Unk” values in the Termination Type column were replaced with “Unknown”. The data in the Survey column were formatted to have uniform data type. There were no duplicate in the dataset.
Unnecessary columns like Payzone, Termination Description, State, Termination Description and Location Code were removed due to their irrelevances to the business questions. 
## Analysis and Insights
Using pivot tables and plotting different graphs, the following insights could be deduced from the analysis:  
1. The production department greatly leads other departments having the highest number of employees (2020) followed by IT/IS (430) while Executive Office has the least number of only 24 employees.
 
2. Employees with a "Performance Score" (Current Employee Rating) below 3 are highlighted below.
 
3. The average "Satisfaction Score" of both the male and female employee are fairly the same with good value.
 
4. The distribution of "Work-Life Balance Score" for different job functions is shown below.
 
5. The terminated employees are majorly on voluntary.
6. The Executive Office department has the highest average engagement score (3.375) followed by IT/IS (3.025) while Production department has the least value (2.906)
 
7. The supervisor's email address for a specific employee is found using: =VLOOKUP(S2, A2:R3001, 8, FALSE) in the recruitment dataset.
8. The department with the highest average "Employee Rating?" is Admin Office.
 
9. There is no relationship between "Training Duration (Days)" and "Training Cost."
 s
10. Female employees are always more than the male counterparts in every "RaceDesc".
 
11. The "Training Program Name" for an employee with a specific ID can be found using: =INDEX(A2:C3001, MATCH(J2, A2:A3001, 0), 3 ) in the Training and Development Dataset.
12. Create a multi-level pivot table to analyze the "Performance Score" by "BusinessUnit" and "JobFunctionDescription"
   
 
13. Performance score of the employees over time is shown below using a dynamic chart.
 
14. The “Communication Skills” incurs the highest training cost followed by Project Management with Customer Service as the least expensive.
 
15. Apply advanced conditional formatting to highlight the top 10% and bottom 10% of employees based on "Current Employee Rating."
   
16. 2018 records the year with greatest average engagement score followed by 2020 and 2019 while 2022 records the least average engagement score.
 
17. A macro that automates the process of updating and refreshing all pivot tables in the workbook is built and assigned in the automator sheet.
18. The distribution of "ExitDate" for terminated employees is shown below.
 
19. The total training cost for employees in a specific location can be calculated using =SUMPRODUCT(--(F2:F3001=J4),I2:I3001) in the Training and Development Dataset.
## Conclusion
The Executive Office department with the least number of employees has the highest average engagement score of 3.375 whereas the Production department with the majority of employees has the least average engagement score of 2.906. Therefore, the organization could be advised to check the number of workers in the production department for better engagement score.
## Dashboard
 ![Screenshot (244)](https://github.com/quadri-usman/EmpolyeeDataAnalysis/assets/105228467/173465f7-4484-4210-b50b-d793f464592d)
