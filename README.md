# Teacher Turnover
*A data analysis project designed to find correlations between teacher turnover, salary, and teacher working conditions in Kentucky's public schools.*

In the past __ years, teacher turnover has increased by %%% in Kentucky's public schools. Teachers leave for other districts or leave the profession. This project idea came about because I am a former public school teacher who left public eduation to look for other career opportunities.

## Project Setup Instructions
- How to download, install and run this project
- Instructions for setting up virtual environment

## Project Overview
- A description of what the user should expect from the project once it is running
- Assume the reviewer has no coding background; keep language clear and simple


## Project Objective 
The objective of this project is to discover any correlations between several factors and teacher turnover in Kentucky. Kentucky's teachers are leaving the profession in higher numbers than previously seen. I am curious what, if any factors, are most closely related to turnover. The factors I am choosing to compare include: salary and three categories of working conditions: student behavior, school climate, and school leadership. I hope to uncover data that shows any possible correlations.

## Methods and Rationale
Explanation of why this is a suitable and effective approach


## Technologies Used
  Pandas was used to clean and minpulate the data sets
  This project was developed in Jupyter Notebooks to allow for clean, narrative-driven presentation of the code and the results.
  Visualizations were created in Tableau Public
  
## Data Source

Data in this project comes from the Kentucky Derpment of Education.  
https://reportcard.kyschools.us/data-download?pid=c340f7d5-efbd-5fb8-cab8-3a128835f84c   
Under the Overview > Faculty Profile > Teacher Working Conditions, Teacher Turnover.

Salary data came from the Kentucky Department of Education. 
https://www.education.ky.gov/districts/FinRept/Pages/School%20District%20Personnel%20Information.aspx   
Average Certified and Classified Staff Data > Certified Salaries (1985-2025)

## Data Summary
Three main data sets were included in the analysis. Teacher Salary included the average certified salary for each of Kentucky's school districts for the 2023-2024 school year. The Turnvover Percent reports what percentage of teachers did not return to work in the same district. This includes both teachers who left the teaching profession and teachers who changed districts. The Working Conditions data set included ratings given by the teachers anonymously on the bi-annual Imapct Survey. I used three working conditions: school leadership, managing student behavior, and school climate. 

### Data Dictionary 
 | Column Name | Description | Data Type |
 |-----------|-------------|------------|
 | District Number | A unique number assigned to each school disctrict in Kentucky | integer |
 | District Name | The name of the school district | string |
 | Impact Measure | The category of rating being measured on the survey | string |
| Impact Value | A percetange value given as favorable rating | integer |
| Average Salary | The average salary for all certified employees in that district | float |
 | Managing Student Behavior | An impact measure relating to how student discipline is managed | string |
  | School Climate | An impact measure relating to the quality and character of school life | string |
  | School Leadership |  An impact measure relating to school administration | string |
  | Turnover Percent | The percentage of teachers who did not return to the same district for employment | float |



## Project Summary
 Description of problem or question you aimed to solve. Summary of the key findings from the data analysis. Any data inconsistencies, limitations, or issues that could have influenced your results. Written plainly.




