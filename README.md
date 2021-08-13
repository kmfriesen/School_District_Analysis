# School_District_Analysis

# Overview

The chief data scientist for a school district asked the analyst to aggregate student test score data and showcase trends in student performance. The results and summary of this project will be used by the school board and superintendent to make decisions regarding school budgets and spending. 

After some initial analysis, the school board discovered academic dishonesty amongst 9th graders at Thomas High School. To uphold state-testing standards, the analyst was asked to erase 9th grade test scores at Thomas High School with while keeping the rest of the data in tact. Next the data analyst repeated the analysis to discover the impact of the dishonesty.


# Results

How is the district summary affected?
The percentages of students who passed math, reading, and both went slightly down, less than 1% per category. The average scores, however, stayed relatively the same. The math score average went down .1 points while the reading remained the same.

District Summary Before
![alt text](https://github.com/kmfriesen/School_District_Analysis/blob/main/Resources/district%20summary%20OLD.png)

District Summary After
![alt text](https://github.com/kmfriesen/School_District_Analysis/blob/main/Resources/district%20summary%20NEW.png)


How is the school summary affected?
To adjust for getting rid of all of the 9th grade scores, we adjusted the caulculations for Thomas High School to only include 10th-12th grade for the average math and reading scores, as well as passing percentages for each category. All of these numbers stayed relatively the same, only fluctuating less than 1 percentage point per category.

School Summary Before
![alt text](https://github.com/kmfriesen/School_District_Analysis/blob/main/Resources/school%20summary%20OLD.png)

School Summary After
![alt text](https://github.com/kmfriesen/School_District_Analysis/blob/main/Resources/School%20Summary%20NEW.png)

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Replacing the math and reading scores for ninth graders at Thomas High School did not affect their performance relative to other high schools at all. Thomas High School still sits as the second best school for overall passing rates for math and reading exams.

Top 5 Schools Before
![alt text](https://github.com/kmfriesen/School_District_Analysis/blob/main/Resources/top%20schools%20OLD.png)

Top 5 Schools After
![alt text](https://github.com/kmfriesen/School_District_Analysis/blob/main/Resources/School%20Summary%20NEW.png)


How does replacing the ninth-grade scores affect the following?
Math and reading scores by grade: It does not affect any of the average math and reading scores by grade, except for the ninth grade at Thomas High School where it is marked as "NaN" since all of the scores have been removed. This is because changing the ninth grade scores to Nan does not impact any of the scores for the other grades at Thomas High School or the grades at any other schools.

Math Score Summary Before
![alt text]()


Math Score Summary After
![alt text]()


Reading Score Summary Before
![alt text]()


Reading Score Summary After
![alt text]()


Scores by school spending:
It does not affect any of the scores by spending for any cateogory except for the $630-644/student bin, where Thomas High School sits. In this bin, the average scores and percentage passing changes so minimally that when the data is formatted to only one decimal points, there appears to be no changes at all.

Scores by Spending Before
![alt text]()

Scores by Spending After
![alt text]()

Scores by school size: 
It does not affect any of the scores by spending for any cateogory except for the Medium Size school bin (1000-2000), where Thomas High School sits. In this bin, the average scores and percentage passing changes so minimally that when the data is formatted to only one decimal points, there appears to be no changes at all.

Scores by Size Before
![alt text]()

Scores by Size After
![alt text]()

Scores by school type: 
It only affects the Charter School cateogry, where Thomas High School sits. In this bin, the average scores and percentage passing changes so minimally that when the data is formatted to only one decimal points, there appears to be no changes at all.

Scores by Type Before
![alt text]()


Scores by Type After
![alt text]()


# Summary 

- The amount of null values in the dataset changed as there were no null values in the original data. While having lots of null values can lead to inaccuracy, this does not appear to be the case because many parts of the analysis were unchanged.

- Another major change to the analysis was the number of students being analyzed. The number of students in the analysis went down by 461 students (~39100 to ~38700). However, I did not changes the student count in any of the analyses.

- When comparing three different categories for schools, spending per student, type, and size, the bins that Thomas High School is in changed so the averages were slightly lower, however not enough to affect their placement in comparison to the other bins.

- Another change of this analysis is that Thomas High School performed worse in math and reading scores and passsing rates. However, this did not change their position as number two school for highest overall passing rates.
