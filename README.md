# Teacher Turnover
This data analysis project is designed to find correlations between teacher turnover, salary, and teacher working conditions in Kentucky's public schools. In the past 5 years since COVID, teacher turnover has increased in Kentucky's public schools. Many teachers leave for other districts or leave the profession completely. This project idea came about because I am a former public school teacher who left public eduation to look for other career opportunities. 

## Project Objective 
The objective of this project is to discover any correlations between several factors and teacher turnover. The factors I am choosing to compare are both quantitative and qualitative and include salary, student behavior, school climate, and school leadership. 

## Project Setup Instructions
The requirements to run this project are included in the 'Requirements.txt' folder.
I created this project in a Jupyter notebook using Pything (3.13.1) in a virtual environment.

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
  | Average Impact Value | An average of: managing student behavior, school climate, school leadership impact values | integer |
  | Turnover Percent | The percentage of teachers who did not return to the same district for employment | float |



## Project Summary
 Description of problem or question you aimed to solve. Summary of the key findings from the data analysis. Any data inconsistencies, limitations, or issues that could have influenced your results. Written plainly.




