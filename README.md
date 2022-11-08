# Pewlett Hackard Analysis

## Overview of the analysis

I am collaborating on this analysis with Pewlett Hackard, a leading technology company, which has been in the market for many years but is currently undergoing a phase of personnel changes; the company has several thousand employees, many of whom are soon to retire.

Therefore, I will help Bobby, a HR analyst, find highly relevant data on how many employees are about to retire and how many new talents can be hired so that the company maintains its high quality and prestige and, above all, to ensure its future.

We are going to use SQL (Structure Query Language) for this project, which is a data query language that will allow us to organize, manipulate, manage and merge data stored in databases.


## Results: 

Our analysis comprises of four important points: Retirement Titles, Unique Titles, Retiring Titles and Mentorship Eligibility.

These four tables will give us more clarity about the important decisions that the company must make.

### 1.	Retirement Titles

According to our first table, there are 133,776 employees who were born between 01-01-1952 and 12-31-1955 and who are about to retire. Of course, this figure is alarming, since the company could not survive without a large part of its employees.

However, if we look closely at the data, some employee names are repeated. This means that they may have changed jobs within the company or perhaps they no longer belong to it.

<img width="692" alt="rt_results" src="https://user-images.githubusercontent.com/112814924/200469802-19cc6f48-b40b-40bf-b5c7-fb271054f70c.png">

### 2.	Unique titles

In our second table, we have removed all duplicates and kept the most recent job title for each employee. This has reduced the number of retiring employees to 72,658, which is a more realistic number but still a bit high for our analysis.

<img width="547" alt="ut_results" src="https://user-images.githubusercontent.com/112814924/200469842-cda4686b-180d-491f-a648-66e3b6564bf2.png">

### 3.	Retiring titles

In our third table, we have retrieved employees by their most recent position who are about to retire, and with our results we now have a total count of employees by job title, 72,468 to be precise. 

This data is very useful, especially for senior positions, since those are the ones with the largest number of employees about to retire. This is great news for engineers or staff members looking for a new opportunity to work in a senior role.

<img width="557" alt="retiring_results" src="https://user-images.githubusercontent.com/112814924/200469869-78b5fa38-5bff-4b0f-b8c2-aa3f323997ee.png">

### 4.	Mentorship eligibility

Finally, in our fourth table, the total number of employees who are eligible to participate in a mentorship program is 1,549.

This result is very low compared to the number of people who are about to leave the company and the new ones who are going to be hired.

<img width="770" alt="me_results" src="https://user-images.githubusercontent.com/112814924/200469896-fc2934f1-abed-4630-8918-91c08d09c2fd.png">

## Summary

The number of employees that are about to retire is alarming high. Pewlett Hackard will not be able to survive without so many employees, especially since the recruitment process takes time.

One of the most important recommendations for the HR manager would be to invest in onboarding talent, either through an external recruitment agency or internally. Bear in mind that when the “silver tsunami” starts to hit, 72,458 roles will need to be filled as shown in the retiring titles table and, as mentioned above, time is a major constraint in the process.

<img width="350" alt="retirement" src="https://user-images.githubusercontent.com/112814924/200477087-8babebb9-6e75-4644-a898-be20e91851dd.png">

On the other hand, the number of retirement-ready employees eligible to mentor the next generation is very low compared to the total number of people leaving, and that's concerning because it can be a big disadvantage for the company.

For this reason, one suggestion for the recruiting team is to create a temporary mentoring department (10 departments in total) that will give employees who are ready to retire the opportunity to work part-time as a mentor to new hires. This would be a mutual benefit, as they will continue to receive income, the company will maintain knowledge and the young people hired will develop faster thanks to the mentoring of the semi-retirees. 

<img width="427" alt="departments" src="https://user-images.githubusercontent.com/112814924/200477108-5a3bbf88-344e-4158-bb21-c3d4fd3d0d40.png">

## Resources

Data source: CSV files on Data folder

Software: SQL

