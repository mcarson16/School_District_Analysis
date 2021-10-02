# School_District_Analysis
## Objective:
The School District has requested the following deliverables:
 - A high-level snapshot of the district's key metrics, presented in a table format
 - An overview of the key metrics for each school, presented in a table format
 - Tables presenting each of the following metrics:
    - Top 5 and bottom 5 performing schools, based on the overall passing rate
    - The average math score received by students in each grade level at each school
    - The average reading score received by students in each grade level at each school
    - School performance based on the budget per student
    - School performance based on the school size 
    - School performance based on the type of school

After discovering evidence of potential academic dishonesty in the reading and math Scores for Thomas High School, the School District also requested:
 - An isolated analysis of the reading and math scores for Thomas High School
 - Refactored deliverables that exclude these scores in the final analysis for the district.

## Resources:
 - https://github.com/mcarson16/School_District_Analysis/blob/main/Resources.zip
 - Software: Python 3.7.6, Jupyter Notebook

## School District Analysis Results
- As spending per student increases, average scores and passing rates do not tend to increase.
  - ![image](https://user-images.githubusercontent.com/83254435/135700143-7e7ed0c2-5451-431b-8ecd-72663a5c586f.png)
- A student's average reading or math score was more influenced by the school they attended than by their grade level.
  - ![image](https://user-images.githubusercontent.com/83254435/135700168-6ace1333-e1cd-4d4f-a96f-bde9fba99c1b.png)
- Large schools (over 2,000 students) tended to have lower average scores and passing percentages. Small and Medium schools were relatively comparable.
  - ![image](https://user-images.githubusercontent.com/83254435/135700127-283643a6-21f7-44f0-b595-1d7e948d4be7.png)
- Charter Schools had higher average scores and passing rates than District Schools.
  - ![image](https://user-images.githubusercontent.com/83254435/135700121-8d353fcd-ceec-452d-8a66-18467012315b.png)

- The ninth grade class of Thomas High School's scores were replaced with NaNs, with the following results:
  - % Passing Reading dropped from 97.3% to 69.6%
  - % Passing Math dropped from 93% to 66%
  - % Overall Passing dropped from 90% to 65.0%

## Challenge Overview
After reading and math scores for Thomas High School's 9th graders were replaced with NaNs, the following changes were observed:

- Thomas High School dropped in overall rankings from 2nd to 8th place.

- School Spending (Per Student) in bin $630-644 decreased by:
  - % Passing Math decreased by 6%
  - % Passing Reading decreased by 7%
  - % Overall Passing decreased by 7%

- Medium (1000-2000) schools decreased by:
  - % Passing Math decreased by 8%
  - % Passing Reading decreased by 6%
  - % Overall Passing decreased by 6%

Charter schools decreased by:
  - % Passing Math decreased by 4%
  - % Passing Reading decreased by 4%
  - % Overall Passing decreased by 3%
