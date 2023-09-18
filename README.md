# pandas-challenge
Module 4 Challenge

Background
As the neew Chief Data Scientist for the city's school district. I am  supporting the school board and mayor make strategic decisions regarding future school budgets and priorities.
My first project is to analyze the district-wide standardized test results. Using csv data files for every student's math and reading scores, as well as various information on the schools they attend. I cleaned and process the data using Jupyter notesbook and pandas and python to identify obvious trends in school performance in the district 


Here is the requirements and results provided in this analysis


Part 1 District Summary:

Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.


1. Total number of unique schools
2. Total number of students
3. Total budget
4. Average math score across all schools
5. Average reading score across all schools
6. Percentage of students passing math 
7. Percentage of students passing reading 
8. Percentage of students passing both math and reading 

Here is my conclusions for District Summary:

1. After peroforming necassary processing and calculation on the data, there are a total of 15 schools with 39,170 student with % Passing reading and % passing math is %85.8 and %75.0% respectively. Average Math score came higher than reading (81 vs 78)



Part 2: School Summary: DataFrame which summarizes following key metrics for each school in the district:

1. School name
2. School type
3. Total number of students in each school
4. Total school budget for each school
5. Budget per student for each school
6. Average math score for each school
7. Average reading score for each school
8. Percentage of students passing math in each school 
9. Percentage of students passing reading in each school 
10. Percentage of students passing both math and reading in each school 

Highest-Performing Schools (by % Overall Passing)
Sorted the schools by % Overall Passing in descending order and display the top 5 rows.

Lowest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.

Here is my conclusions for school Summary:

1. After peroforming necassary processing and calculation on the data. Cabrera High School had the lowest Cost "Per Student Budget". For the top 5 schools sorted by highest "% Overall passing" have similar "% Overall Passing" around %90.5 to %91.3, with varrying "Total Budget" figures ranging from $585k to $1.08M. Whereas for the school sorted by the lowest "% Overall passing" they all had on avg %52.5 for Overall passing.
-------------------------------------------------------

Math Scores by Grade
Performed the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Reading Scores by Grade
Created a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Scores by School Spending
- Average math score
- Average reading score
- % passing math 
- % passing reading 
- % overall passing 

Create a table that breaks down school performance based on average spending ranges (per student).

Here is my conculsion:
1. After peroforming necassary processing and calculation on the data. I couldn't find a strong correlation between school spending and passing % and average scores across math and reading by looking at the spending ranges (per student)

Scores by School Size & Scores by School Type:
1. After peroforming necassary processing and calculation on the data. Based on scores by School Size summary DataFrame, small and Medium Size schools have a much higher performacing across math and reading compared to large Schools

2. By School type, charter schools have signficantly higher "%passing Math" than District schools 


