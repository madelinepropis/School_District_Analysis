# PyCitySchool Challenge

## Overview of Project

The purpose of the PyCitySchool Analysis was to provide data for administrators in a school district. The analysis includes preparing standardized testing at 15 schools. Using given data about each school and each student, I was able to provide data for Maria about performance trends and patterns. Maria will use this data to make decisions at both the school and district levels.

In this challenge, it was found that some ninth-graders at Thomas High School had incorrect grades in the system. These grades were replaced with null values, NaNs, which are not included in total and average amounts in the analysis in the end. Thomas High School values in the final charts represent students in grades 10-12.

## Results

### District Summary

In the original District Summary Data Frame, the Thomas High School's fake ninth-graders' scores are included. They are excluded in the new Data Frame.

* Total Students: Remained the same
* Total Student Budget: Remained the same
* Average Math Score: Decreased minimally
* Average Reading Score: Remained the same
* % Passing Math: Decreased minimally
* % Passing Reading: Decreased minimally
* % Overall Passing: Decreased minimally

Original DataFrame Including Thomas High School's Ninth-Graders' Grades:
![Original_DistrictSummary](https://user-images.githubusercontent.com/109561408/186549966-47d961f5-a19b-497a-bb24-3c05d221f0c3.png)

DataFrame Excluding Thomas High School's Ninth-Graders' Grades:
![New_DistrictSummaryDf](https://user-images.githubusercontent.com/109561408/186550001-e594ba9e-b439-4ce4-a1cc-8ab95d68dcf1.png)

### School Summary

In the original School Summary Data Frame, the Thomas High School's ninth-graders' scores are included. They are excluded in the new Data Frame.

* Per Student Budget: Remained the same
* Average Math Score: Decreased minimally
* Average Reading Score: Increased minimally
* % Passing Math: Increased minimally
* % Passing Reading: Decreased minimally
* % Overall Passing: Decreased minimally 

Original DataFrame Containing Thomas High School's Ninth-Graders' Grades:
![Original_SchoolDataCompleteDf](https://user-images.githubusercontent.com/109561408/186550029-51794707-cb56-4a56-9ee6-399c3a66fd94.png)

DataFrame Excluding Thomas High School's Ninth-Graders' Grades:
![New_SchoolDataDf](https://user-images.githubusercontent.com/109561408/186550053-62f1d2b4-0f9c-4bad-866f-49326be1e5a2.png)

DataFrame with Only 10-12th graders from Thomas High School:
![Removed_SchoolDataDf](https://user-images.githubusercontent.com/109561408/186550079-bd3a46d0-dc3f-488f-af83-64910263b0a0.png)

### Replacing Thomas High School's Performance

In comparison to other the schools, before replacing the ninth-grader's grades, Thomas High School had the 2nd highest overall passing rate. After moving the grades, Thomas High School dropped to become the 8th highest ranked school out of 15 since null grades were being calculated as 0s while the total student count remained the same. ADD HERE The district summary was not greatly impacted by replacing Thomas High School's ninth-graders' grades.

### Replacing the Ninth-Grade Scores

#### Math and Reading Scores by Grade

Math:

Original DataFrame Containing Thomas High School's Ninth-Graders' Grades:
![Original_MathScoresByGrade](https://user-images.githubusercontent.com/109561408/186550433-7cfe4c30-88bc-4390-8ce6-905ad96cf043.png)

DataFrame with Only 10-12th graders from Thomas High School:
![Removed_MathScoresByGrade](https://user-images.githubusercontent.com/109561408/186550406-594084a8-d0bc-4b37-9fb0-764f3cb352bf.png)

Reading:

Original DataFrame Containing Thomas High School's Ninth-Graders' Grades:
![Original_ReadingScoresByGrade](https://user-images.githubusercontent.com/109561408/186550449-972fc375-5e84-4c52-b8a9-8a54f57fb1de.png)

DataFrame with Only 10-12th graders from Thomas High School:
![Removed_ReadingScoresByGrade](https://user-images.githubusercontent.com/109561408/186550473-0dacf140-a1b1-411d-a3bd-e8ebf616ff0f.png)

#### Scores by School Spending

Original DataFrame Containing Thomas High School's Ninth-Graders' Grades:
![Original_AvgScoresBySpending](https://user-images.githubusercontent.com/109561408/186550516-491a3e2d-027e-4908-b959-f28d47de8d58.png)

DataFrame with Only 10-12th graders from Thomas High School:
![Removed_AvgScoresBySpending](https://user-images.githubusercontent.com/109561408/186550504-47b49bcd-8830-4773-bf23-0d2bac7ecce4.png)

#### Scores by School Size

Original DataFrame Containing Thomas High School's Ninth-Graders' Grades:
![Original_AvgScoresBySize](https://user-images.githubusercontent.com/109561408/186550540-ee197d45-a342-4917-af07-a58724a68b33.png)

DataFrame with Only 10-12th graders from Thomas High School:
![Removed_AvgScoresBySize](https://user-images.githubusercontent.com/109561408/186550655-27d9733b-4132-4b87-bb39-de13699780a0.png)

#### Scores by School Type

Original DataFrame Containing Thomas High School's Ninth-Graders' Grades:
![Original_AvgScoresByType](https://user-images.githubusercontent.com/109561408/186550629-d2578c2c-7b8e-4536-b83f-736d25b5e8b6.png)

DataFrame with Only 10-12th graders from Thomas High School:
![Removed_AvgScoresByType](https://user-images.githubusercontent.com/109561408/186550582-cee386e7-f82f-430a-a99c-bd53272fe6f7.png)

## Summary

The incorrect grades put into the system changed the dataset more when null values were included in totals. Once, Thomas High School averages did not include the null values in the totals, the data did not seem to change much. Overall, removing the ninth-graders' grades did not greatly impact the overall findings when Thomas High Schools averages were only for grades 10-12.

Some significant findings were that when replacing the Thomas High School ninth-graders' grades, the passing rates for math, reading and overall decreased when looking at the school level view. Additionally, the analysis shows that removing the grades was not extremely impactful at district level view as all of the metrics were decreased by less than a percent. Both the total number of students and the total student budget remained the same when removing the grades as the python code only removed the grades from the ninth-graders at Thomas High School. Another finding was that ....

