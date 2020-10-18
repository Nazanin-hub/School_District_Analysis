# School_District_Analysis

## Overview of the school district analysis

A chief data scientist for a city school is responsible for analyzing information, preparing all standardized test data for analysis, reporting, and presentation to provide insights about performance trends and patterns. I helped her to analyze data on student funding and students' standardized test scores.

## Resources

 - Data Source: schools_complete.csv, students_complete.csv
 - Software: Python 3.8.3, Jupyter Notebook 6.0.3
 
 ## Challenge Overview
 
  Since the school board had evidence of academic dishonesty specifically, reading and math 9th grades for Thomas High School. So, I replaced the math and reading scores for       Thomas High School with NaNs. Then, I recalculated the following data:
    
   - The district and school summary DataFrames.
   - The top 5 and bottom 5 performing schools, based on the overall passing rate.
   - The average math and reading scores received by students in each grade at each school
   - The school performance based on the spending per student.
   - The school performance based on the size of the school.
   - The school performance based on the type of school.
      
## Results:
 - How is the district summary affected?
  
    After deleting the number of students who are from the 9th grade at Thomas high school, the average math score, the average reading score, the percentage of students who         passed math and the percentage of students who passed reading have been decreased by 0.1%. Also, the overall passing percentage has been decreased by 0.3% with the               recalculated total students.
  
 - How is the school summary affected?
 
   The only change in data is with Thomas High School. I Subtracted the number of students that are in ninth grade at Thomas High School from the total number of students to        get the new total student count who are in 10th-12th grades. Based on the below table, the percentage of passing math decreased from 93.27% to 93.19, the percentage of          reading   decrease from 97.31% to 97.02%, and the overall passing percentage decreased from 90.95% to 90.63%. Average math and reading scores didn't change. So, this            recalculation didn't have any remarkable effect on the percentages of reading and math at Thomas High School. 
   ![](https://github.com/Nazanin-hub/School_District_Analysis/blob/main/pic.2.png) 
   
 
 - How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
 
    Based on the below table,the performance of Thomas High School has not changed. It is still at the second top-performing schools.
    
    ![](https://github.com/Nazanin-hub/School_District_Analysis/blob/main/performance.png)
   
 - How does replacing the ninth-grade scores affect the following:
 
    - Math and reading scores by grade
      
     Based on the below table, replacing the 9th-grade doesn't have any effect on the average reading and math scores. The average math and reading scores for 9th grade at            thomas high School have been shown by "Nan" whereas the remaining data remained intact.
     
     ![](https://github.com/Nazanin-hub/School_District_Analysis/blob/main/math-grade.png)
     
    - Scores by school spending
    
      Based on the below table, just the spending ranges between $630-644 has marginally changed and the remaining data remained intact. The average math score for spending           range between $630-644 decreased from 78.52% to 78.50%, the average reading score increased from 81.62% to 81.64%. The percentage of students who passed math in range           $630-644 decreased from 73.48% to 73.46%, the percentage of students who passed the reading decreased from 84.39% to 84.32%, and the overall percentage of passing math and       reading decreased from 62.86% to 62.79%. so, the rate of changes is negligible.   
      
      ![](https://github.com/Nazanin-hub/School_District_Analysis/blob/main/reading-grade.png)  
      
    - Scores by school size
    
      Based on the below table, just the medium schools size has slightly changed. The average math score for medium size schools decreased from 83.37% to 83.36%, the average         reading score increased from 83.86% to 83.87%. The percentage of students who passed math in medium size schools decreased from 93.60% to 93.58%, the percentage of               students who passed the reading decreased from 96.79% to 96.73%, and the overall percentage of passing math and reading decreased from 90.62% to 90.56%.
      
      ![](https://github.com/Nazanin-hub/School_District_Analysis/blob/main/school size-.png)
      
    - Scores by school type
    
      Based on the below table, since Thomas High School is in chartar type, all the data in this type have been a bit changed. If we round the numbers, we can not see any             diffrence between numbers because the percentage of change is too small. Forexample, The average math score for chartar type schools decreased about 0.009%

## Summary:

   - Charter schools performed better than district schools
   - 
   - 
   


