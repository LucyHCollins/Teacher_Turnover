# Teacher Turnover
This data analysis project is designed to find correlations between teacher turnover, salary, and teacher working conditions in Kentucky's 171 public school districts. In the past 5 years teacher turnover has increased in Kentucky's public schools. Many teachers leave for other districts or leave the profession completely. This project idea came about because I am a former public school teacher who left public eduation to look for other career opportunities. 

## Project Objective 
The objective of this project is to discover any correlations between several factors and teacher turnover. The factors I am choosing to compare are both quantitative and qualitative and include salary, student behavior, school climate, and school leadership. My methods include cleaning and merging data published by the Kentucky Department of Education. I removed extraneous columns and info so I can clearly and concisely examine whether any correlations occur between these factors and teacher turnover at the district level. I ran a regression analysis comparing turnover as the dependent variable to salary, school climate, managing student behavior, and school leadership as the four independent variables. I used the R values to understand to what extent those variables affected teacher turnover.


## Project Setup Instructions
The requirements to run this project are included in the 'Requirements.txt' folder.
I created this project in a Jupyter notebook using Python (3.13.1) in a virtual environment.

In order to run this project:
1. Clone the repository.
2. Save the Folder.
3. Open Jupyter Notebook from the command line or start menu.
4. Go to the where you saved the notebook.
5. Open 'Teacher_Turnover.ipynb'
6. Click Run All.

If you choose to run it in a virtual environment:

On a Mac:
From your terminal run: python3 -m venv env
Run sourc env/bin/activate

On Windows:
From your termin run: python -m venv env
Run env\Scripts\activate.bat


## Technologies Used
  Pandas was used to clean and minpulate the data sets.
  This project was developed in Jupyter Notebooks to allow for clean, narrative-driven presentation of the code and the results.
  Visualizations were created using matplotlib. Regression analyses used statsmodels.
  
## Data Source

Data in this project comes from the Kentucky Derpment of Education.  
https://reportcard.kyschools.us/data-download?pid=c340f7d5-efbd-5fb8-cab8-3a128835f84c   
Under the Overview > Faculty Profile > Teacher Working Conditions, Teacher Turnover.

Salary data came from the Kentucky Department of Education. 
https://www.education.ky.gov/districts/FinRept/Pages/School%20District%20Personnel%20Information.aspx   
Average Certified and Classified Staff Data > Certified Salaries (1985-2025)

## Data Summary
Three main data sets were included in the analysis. Teacher Salary included the average certified salary for each of Kentucky's school districts for the 2023-2024 school year. The Turnvover Percent reports what percentage of teachers did not return to work in the same district. This includes both teachers who left the teaching profession and teachers who changed districts. The Working Conditions data set includes ratings given by the teachers anonymously on the bi-annual Imapct Survey. I used three working conditions: school leadership, managing student behavior, and school climate. 

### Data Dictionary 
 | Column Name | Description | Data Type |
 |-----------|-------------|------------|
 | District Number | A unique number assigned to each school disctrict in Kentucky | int |
 | District Name | The name of the school district | obj |
 | Impact Measure | The category of rating being measured on the survey | obj |
| Impact Value | A percetange value given as favorable rating | int |
| Average Salary | The average salary for all certified employees in that district | float |
 | Managing Student Behavior | An impact measure relating to how student discipline is managed | obj |
  | School Climate | An impact measure relating to the quality and character of school life | obj |
  | School Leadership |  An impact measure relating to school administration | obj |
  | Average Impact Value | An average of: managing student behavior, school climate, school leadership impact values | float |
  | Turnover Percent | The percentage of teachers who did not return to the same district for employment | float |
  | R-squared value | A range between 0 and 1, with 0 being a week relationship and 1 being a strong relationship between a dependent and independent variable | float |



## Project Summary
 In summary, the R-values showed that the strongest correlations with teacher turnover were school climate and managing student behavior at about 11%. Salary was insignificant at less than 1% and school leadership was small at 3%. 
 
Further analysis of this data should span multiple school years to see how change over time affects results. For example, did districts whose average satisfaction score decreased over multiple years see an increase in teacher turnover during that same period? Other independent variables could include a district's Kentucky Summative Assessment(KSA) scores and the socio-economic status of a district's student population. 




