# Pewlett Hackard Analysis

## Overview of the analysis

I am collaborating on this analysis with Pewlette Hackard, a leading technology company, which has been in the market for many years but is currently undergoing a phase of personnel changes; the company has several thousand employees, many of whom are soon to retire.

Therefore, I will help Bobby, an HR analyst, find highly relevant data on how many employees are about to retire and how many new talents can be hired so that the company maintains its high quality and prestige and, above all, to ensure its future.

We are going to use SQL (Structure Query Language) for this project, which is a data query language that will allow us to organize, manipulate, manage and merge data storage in databases.


## Results: 

Our analysis comprises of four important points: Retirement Titles, Unique Titles, Retiring Titles and Mentorship Eligibility.

These four tables will give us more clarity about the important decisions that the company must make.

### 1.	Retirement Titles

According to our first table, there are 133,776 employees who were born between 01-01-1952 and 12-31-1955 and who are about to retire. Of course, this figure is alarming, since the company could not survive without a large part of its employees.

However, if we look at the data, some employee names are repeated. This means that they may have changed jobs within the company or perhaps they no longer belong to it.

IMAGE

### 2.	Unique titles

In our second table, we have removed all duplicates and kept the most recent job title for each employee. This has reduced the number of retiring employees to 72,658, which is a more realistic number but still a bit high for our analysis.

IMAGE

### 3.	Retiring titles

In our third table, we have retrieved employees by their most recent position who are about to retire, and with our results we now have a total count of employees by job title. 

This data is very useful, especially for senior positions, since they are the ones with the largest number of employees about to retire. This is great news for engineers or staff members looking for a new opportunity to work in a senior position.

### 4.	Mentorship eligibility

Finally, in our fourth table, the total number of employees who are eligible to participate in a mentorship program is 1,549.

This result is very low compared to the number of people who are about to leave the company and the new ones who are going to be hired.

IMAGE

