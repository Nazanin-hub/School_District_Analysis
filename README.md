# School_District_Analysis

## Overview of the school district analysis

A chief data scientist for a city school is responsible for analyzing information, preparing all standardized test data for analysis, reporting, and presentation to provide insights about performance trends and patterns. I helped her to analyze data on student funding and students' standardized test scores.

## Resources

 - Data Source: schools_complete.csv, students_complete.csv
 - Software: Python 3.8.3, Jupyter Notebook 6.0.3

## Results:

 - How is the district summary affected?
  
   After deleting the number of students who are from the 9th grade at Thomas high school, the average math score, the average reading score, the percentage of students who         passed math and the percentage of students who passed reading have been decreased by 0.1%. Also, the overall passing percentage has been decreased by 0.3% with the               recalculated total students.
  
 - How is the school summary affected?
 
   School summary just affected on the Thomas high school data. First, with considering 9th-grade students as NAN at Thomas high school, the percentage of passing math, reading,    and overall passing significantly decreased. As the below table shows, the percentage of students who passed math decreased from 93.27% to 66.91%. The percentage of students    who passed reading decreased from 97.31% to 69.66%, and the overall percentage of passing math and reading decreased from 90.95% to 65.08%. While the average math and reading    scores changed from 83.42% to 83.35% and 83.85% to 83.90%.
   
   
  Second, I calculated the percentage of 10th-12th grade students who passed math, reading, and the overall passing percentage. Then, I replaced these new results with previous data at Thomas high school. Based on the below table, the percentage of passing math, reading, and the overall passing percentage increased to 93.19%, 97.14%, and 90.63%          respectively. Average math and reading scores didn't change.
   
 
 - How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
 
 - How does replacing the ninth-grade scores affect the following:
 
    - Math and reading scores by grade
    
    - Scores by school spending
    
    - Scores by school size
    
    - Scores by school type
    

## Summary:
