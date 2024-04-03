Module 4 Challenge
PyCity School Budget and Standardized Test Analysis

Overview
This Python script uses the Pandas library to conduct analysis on standardized test results, budget by school and per capita, school size and type.

The analysis begins by analyzing at the district level to understand how many schools there are, the size of each school, the total budget per school, average math and reading scores, 
percent of students who passed math or reading with a 70 or better, percent of students passing math and reading with a 70 or better, and presenting a District Summary via Pandas DataFrame.

After completing the District Summary, the analysis focuses on creating the School Summary by analyzing the following mertics: School Type, Student Count Per School, Total School Budgets
and Per Capita Spending, Average Test Scores Per School, Number of Students Per school Passing Math, Number of Students Per School Passing Reading, Number of Students Passing Per
School Passing Reading, Number of Students Per School Passing Both Math and Reading, Per School Passing Rates for both Math and Reading, and presenting the School Summary via Pandas DataFrame. 

Finally, the analysis helps us drill into more granular details.  We looked at the top and bottom performing schools by % overall passing, math and reading scores by grade, test scores by school spending by
capita, test scores by school size, and test scores by school type.  

Through this analysis we can see we are looking at a total of 15 schools, a mix of district and charter school types, a student population of roughly 39k, and a total budget of $24,649.428.

Charter schools comprise the top 5 performing schools, while spending less per capita than the bottom 5 performing schools.  The bottom 5 performing schools are all District schools, with much larger student populations 
Than the top 5 performing schools.  This leads me to believe smaller class sizes, and better fund allocation help drive better performance.  It is also worth noting that district schools overall
passing rates are awful compared to the charter schools.  In conclusion, Charter Schools out perform District Schools not because of more spending per capita but due to smaller class sizes


Requirements
Python 3, Jupyter, CSV files containing schools_complete and student_complete data

District Analysis
Path to School Data: The code assumes that the budget data is stored in a CSV file named schools_complete.csv. Unique Schools: The code calculates the total number of unique schools (school_count) included in the dataset. 
Total Students: Calculates the total count of students (student_count). Total Budget: Calculates the total budget of all schools combined. Average Math & Reading: Calculates the average (mean) score for Math and Reading across all schools 
Percentage of students who passes math, reading & both: calculates the rates of students who passed either math, or reading, or both.

School Analysis
School Type: determines the different school types being analyzed. Student Count Per School: calculates population by school. School budget and per capita spending: calculates the budget available per school and what is being
spent per student at each school.  Average test Scores by School: calculates average math and reading scores by school.  Passing Rates: calculates students who only passed math or reading and students who passed both.  The per
school summary displays the DataFrame created with previous calculations.  

Output
The results of each analyses are printed to the below each cell in the Jupyter notebook. Additionally, the report is contained within this README.

Usage
Ensure Python 3 is installed on your system. Place the CSV files containing school and student data in their respective directories (PyCitySchools/Resources). Run the Python script in your terminal: "python -m notebook" to launch
the Jupyter notebook.  

Note
This script utilizes the Pandas library and Pathlib.
