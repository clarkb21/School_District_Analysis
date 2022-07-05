# School District Analysis

## Project Overview
- Analyze data on student funding and student test scores
- Breakdown math and reading scores based on grade, school, and school type
- Tasked to aggregate the data and showcase trends in school performance
- Present data to school board to assist in making decisions regarding school budget allotments

### Challenge Overview
- School board discovered cases of Academic Dishonesty at a particular school
- I was tasked with replacing scores for those students with "Nans" to adjust the data
- The rest of the data needs to be fully intact, only adjusting the math and reading scores from that school

## Resources
- Data Source: schools_complete.csv; students_complete.csv
- Software: Python 3.7.6, Conda 4.13.0, Jupyter Notebook 6.4.8, Pandas 1.4.3
- MSU Bootcamp Spot Module 4: https://courses.bootcampspot.com/courses/2508/assignments/31963?module_item_id=634879

## Results

### Was District Summary Affected?
- Original District Summary
![image](https://user-images.githubusercontent.com/104038813/177370423-c22614f5-0789-4a12-9d05-acaa8293c4ae.png)
- Updated District Summary

![image](https://user-images.githubusercontent.com/104038813/177370862-4ba4c646-53ad-4eb7-9682-1d47cc996313.png)

- Changing the data from Thomas High School did not affect the total number of schools, students, or the budget. 
- Based on the images above, the data for average math score changed slightly, and average reading score did not change.
- Since the changes to the averages was so small, the % Passing Categories did not reflect much change, either.

### Was School Summary Affected? 
- Original School Summary 
![image](https://user-images.githubusercontent.com/104038813/177373506-12db1a92-0982-4af5-8e1d-da92855284c6.png)
- Updated School Summary 
![image](https://user-images.githubusercontent.com/104038813/177373810-8bfb2270-a421-4e8c-8709-6006c7767c96.png)
- Because of the way I updated the data, only data from Thomas High School would be affected. 
- All other schools data remained untouched, so the data would not change. 

- Replacing scores for 9th graders at Thomas High School with "Not a Number" removes those scores from future calculations. Those scores are ignored rather than placing zeros, which would greatly impact the average scores. 

### Impact of Replacing 9th Grade Scores
![image](https://user-images.githubusercontent.com/104038813/177378725-dccbd4f4-fe93-41a1-b383-c9b268f9a459.png)

![image](https://user-images.githubusercontent.com/104038813/177378793-ef713dcb-a2a9-46d5-8571-903ac3b9bd21.png)


- From the above images, 9th grade Math scores from Thomas High School were replaced with NaN 
- The same was done to reading scores for 9th graders at Thomas High School.

- Scores based on School Spending 
![image](https://user-images.githubusercontent.com/104038813/177379240-f3222570-2c7f-4a85-ad9b-37a0cd0a70f2.png)


- Scores by School Size 

![image](https://user-images.githubusercontent.com/104038813/177379337-bbd3dc50-37de-49ee-bd1a-da7e8ddbb3ae.png)

- Scores by School Type

![image](https://user-images.githubusercontent.com/104038813/177379426-d04a82eb-cc4d-47eb-a7d6-58ab1d4c19b1.png)


## Challenge Summary
