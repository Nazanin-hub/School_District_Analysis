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
   
   
   Second, I calculated the percentage of 10th-12th grade students who passed math, reading, and the overall passing percentage. Then, I replaced these new results with previous    data at Thomas high school. Based on the below table, the percentage of passing math, reading, and the overall passing percentage increased to 93.19%, 97.14%, and 90.63%        respectively. Average math and reading scores didn't change.
   
 
 - How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
 
   The performance of Thomas High School has not changed. It is still at the second top-performing schools.
 
 - How does replacing the ninth-grade scores affect the following:
 
    - Math and reading scores by grade
      
      Thomas High School's 9th grade class has no math or reading score data to count. Everything else was unaffected
    
    - Scores by school spending
    
      Just the spending ranges between $630-644 has marginally changed since Thomas High School is in this range. The average math score for spending range between $630-644           decreased from 78.52% to 78.50%, the average reading score increased from 81.62% to 81.64%. The percentage of students who passed math in range $630-644 decreased from           73.48% to 73.46%, the percentage of students who passed the reading decreased from 84.39% to 84.32%, and the overall percentage of passing math and reading decreased from       62.86% to 62.79%.    

      
    - Scores by school size
    
      Just the medium schools size has slightly changed since Thomas High School is in this size. The average math score for medium size schools decreased from 83.37% to 83.36%,       the average reading score increased from 83.86% to 83.87%. The percentage of students who passed math in medium size schools decreased from 93.60% to 93.58%,the percentage       of students who passed the reading decreased from 96.79% to 96.73%, and the overall percentage of passing math and reading decreased from 90.62% to 90.56%.    
    
    - Scores by school type
    
      Since Thomas High School is in chartar type, all the data in this type have been a bit changed. If we round the numbers, we can not see any diffrence between numbers             because the percentage of change is too small. Forexample, The average math score for chartar type schools decreased about 0.009%

## Summary:


