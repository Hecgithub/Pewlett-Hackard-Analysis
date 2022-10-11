# Pewlett-Hackard-Analysis
## Overview of the analysis:
In this project, we used data modeling, engineering, and analysis to create entity relationship diagrams, import data into a database, troubleshoot common errors, and create queries that use data to answer questions regarding the Pewlett Hakckard and their assessment of employees’ time in the company. By creating various tables, we can better understand future risks or opportunities within the company regarding employment. For the final analysis, we are looking to accomplish two goals listed below. 
### Goal # 1
This analysis aims to determine the number of retiring employees per title and identify employees eligible to participate in a mentorship program. 
### Goal # 2
Summarize analysis and help prepare management for the “silver tsunami” as many current employees reach retirement age.
## Results:
•	For the first goal, we generated a query that pulled info from the employee’s table and titles table. We joined the two tables and created the retirement_titles table. We filtered the data by birth date to only retrieve employees born between 1952 and 1955. There were 133,776 results from the query. 

![image](https://user-images.githubusercontent.com/110510718/195002502-47cec18c-c8bd-49f1-9d5f-c91b1340c64c.png)

 
•	In the second query, we excluded employees that have already left the company and created a new table that reduced the total number to 90,398. We used the “Distinct On” statement to remove duplicate names of employees that had job changes and only kept the most recent one. 
 
 ![image](https://user-images.githubusercontent.com/110510718/195002532-cbbb08ad-f220-451d-9ad4-4147f14659bf.png)

 
•	We generated a list of eligible retirees by title. 

![image](https://user-images.githubusercontent.com/110510718/195002554-1e4d8a0d-4a93-4aea-93c6-c0cf0797a14f.png)

 
•	Lastly, we created a table that lists eligible employees participating in a mentorship program. These employees had to be born between January 1, 1965, and December 1, 1965. There was a total of 1,940 candidates for the mentorship program.
 
 ![image](https://user-images.githubusercontent.com/110510718/195002586-e4511ebf-0965-4f79-9ccb-89c57759fcc9.png)

 

## Summary:
o	How many roles will need to be filled as the "silver tsunami" begins to impact?

In summary, there are a little over 90 thousand employees that will potentially retire soon, and out of that amount, the majority are Staff and Senior Engineers, equating to about two-thirds.

o	Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pawlett Hackard employees?

One thousand nine hundred forty employees are eligible for the mentorship program. This means there are not enough department employees to mentor the next generation of Pawlett Hackard employees, as this would require about 46 new hires. 

