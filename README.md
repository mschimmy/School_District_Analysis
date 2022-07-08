# School District Analysis
## Overview of Project
It was discovered that the original school district analysis summary showed evidence of academic dishonesty, specifically in the reading and math scores for ninth-grade students at Thomas High School.

### Purpose
The purpose of this analysis is to replace the math and reading scores for ninth-graders at Thomas High School with NaNs, while keeping the rest of the data intact. The school district analysis is then repeated and this report describes how these changes changes affected the overall analysis.

## Results
### District Summary Analysis
![District Summary, old](https://github.com/mschimmy/School_District_Analysis/blob/main/Resources/district_summary_old.png)
      District summary, old

![District Summary, new](https://github.com/mschimmy/School_District_Analysis/blob/main/Resources/district_summary_new.png)
      District summary, new

How is the district summary affected?
- When comparing the old and new district summaries, we can see that removing the reading and math scores for ninth-grade Thomas High School students did not drastically affect the district statistics. The largest change was in “% Passing Reading” where the percentage fell 0.3%.

### School Summary Analysis
![School summary, old](https://github.com/mschimmy/School_District_Analysis/blob/main/Resources/school_summary_old.png)
      School summary, old

![School summary, new](https://github.com/mschimmy/School_District_Analysis/blob/main/Resources/school_summary_new.png)
      School summary, new

How is the school summary affected?
- Since we only removed data for Thomas High School ninth-graders, that high school was the only school affected. We can see from the data that all measurements of performance decreased, except for the average reading score which increased by 0.046782. Overall, the performance scores did not drastically change; the statistic with the most change was for the percentage of students passing overall, which fell by 0.317699%.

### Top 5 and Bottom 5 Performing Schools
![Top 5 performing schools, old](https://github.com/mschimmy/School_District_Analysis/blob/main/Resources/top_five_schools_old.png)
      Top 5 performing schools, based on overall passing rate, old

![Top 5 performing schools, new](https://github.com/mschimmy/School_District_Analysis/blob/main/Resources/top_five_schools_new.png)
      Top 5 performing schools, based on overall passing rate, new

![Bottom 5 performing schools, old](https://github.com/mschimmy/School_District_Analysis/blob/main/Resources/bottom_five_schools.png)
      Bottom 5 performing schools, based on overall passing rate

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? 
- Though the performance statistics for Thomas High School changed, it did not affect the ranking of the top five or bottom five schools in the district, these rankings remained the same.

### Average Math and Reading Scores for Each Grade Level from Each School
![Average math scores, old](https://github.com/mschimmy/School_District_Analysis/blob/main/Resources/math_scores_by_grade_old.png)

      Average math scores for each grade level from each school, old

![Average math scores, new](https://github.com/mschimmy/School_District_Analysis/blob/main/Resources/math_scores_by_grade_new.png)

      Average math scores for each grade level from each school, new

![Average reading scores, old](https://github.com/mschimmy/School_District_Analysis/blob/main/Resources/reading_scores_by_grade_old.png)

      Average reading scores for each grade level from each school, old

![Average reading scores, new](https://github.com/mschimmy/School_District_Analysis/blob/main/Resources/reading_scores_by_grade_new.png)

      Average reading scores for each grade level from each school, new

How does replacing the ninth-grade scores affect the math and reading scores by grade?
- The only change in average reading and math scores for each grade level from each school was that the performance statistics for ninth-grade Thomas High School students were removed, which was replaced by NaN (“not a number”).

### Scores by School Spending per Student
![Scores by school spending per student, old](https://github.com/mschimmy/School_District_Analysis/blob/main/Resources/scores_by_spending_old.png)
      Scores by school spending per student, old

![Scores by school spending per student, new](https://github.com/mschimmy/School_District_Analysis/blob/main/Resources/scores_by_spending_new.png)
      Scores by school spending per student, new

How does replacing the ninth-grade scores affect the performance scores by school spending?
- From the DataFrames, we can see that the performance scores for schools with a spending range of $586-630 per student or $631-645 increased. The most notable increase was in “% Passing Overall” for schools with a budget of $589-630 per student, which increased by 9 points. This is pretty significant as this would translate as going from a B- to an A- on the grading scale, a whole letter grade difference. The smallest increase was in the average reading score for schools with a budget of $631-645, which only increased by 0.3, keeping the statistic at a B- letter grade.

### Scores by School Size
![Scores by school size, old](https://github.com/mschimmy/School_District_Analysis/blob/main/Resources/scores_by_size_old.png)
      Scores by school size, old

![Scores by school size, new](https://github.com/mschimmy/School_District_Analysis/blob/main/Resources/scores_by_size_new.png)
      Scores by school size, new

How does replacing the ninth-grade scores affect the performance scores by school size?
- Though the performance statistics for Thomas High School ninth-graders were removed, this change did not affect the performance scores by school size.

### Scores by school type
![Scores by school type, old](https://github.com/mschimmy/School_District_Analysis/blob/main/Resources/scores_by_type_old.png)
      Scores by school type, old

![Scores by school type, new](https://github.com/mschimmy/School_District_Analysis/blob/main/Resources/scores_by_type_new.png)
      Scores by school type, new

How does replacing the ninth-grade scores affect the performance scores by school type?
- Though the performance statistics for Thomas High School ninth-graders were removed, this change did not affect the performance scores by school type.

## Summary
Four changes to the school district analysis after the reading and math scores for ninth-graders at Thomas High School were replaced with NaNs:
1. All performance statistics for Thomas High School decreased, except for the average reading score which had a marginal increase.
2. The change in performance statistics for Thomas High School was not significant enough to affect the top five and bottom school rankings.
3. The new district summary had a marginal decrease in all performance statistics besides the average reading score, which remained the same. When translated to +/- letter grades the performance statistics remained the same.
4. The most significant change was in the statistics for school performance by school funding. The “% Passing Overall” for schools with a budget of $589-630 per student rose by a whole letter grade.
