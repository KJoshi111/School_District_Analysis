# School_District_Analysis

## Overview of Analysis:
The purpose of this analysis was to use our knowledge of the Pandas library and use it to conduct an analysis on a school district. The first part of the challenge was replacing the ninth-grade reading and math scores in Thomas High School, as they were inaccurate due to academic dishonesty. In the second step of the anaysis challenge, we repeated the school district analysis with the accurate data.

## Results:

### How was the District Summary affected?
#### Original District Summary:

![original_district_summary](https://github.com/KJoshi111/School_District_Analysis/blob/main/original_district_summary.png)

#### Edited District Summary: 
![edited_district_summary](https://github.com/KJoshi111/School_District_Analysis/blob/main/edited_district_summary.png)

The pictures above show that taking the Thomas High School's ninth graders' math and reading scores and turning them into NaN values, the average reading scores, average math scores, percentage of students passing math, percentage of students passing reading, and the overall percentage all went down, although very slightly.

### How was the School Summary affected?
#### Original School Summary:
![original_school_summary](https://github.com/KJoshi111/School_District_Analysis/blob/main/original_school_summary.png)

#### Edited School Summary:
![edited_school_summary](https://github.com/KJoshi111/School_District_Analysis/blob/main/edited_school_summary.png)

The pictures above show that taking the Thomas High School's ninth graders' math and reading scores and turning them into NaN values, the average math score went slightly down, the average reading score went slightly up, and the percentage of students passing math, the percentage of students passing reading, and the overall percentage all went down drastically.

### How did replacing the ninth graders' reading and math scores affect the following:
* Thomas High School's performance as compared to other schools
  - Thomas High School's performance goes down rapidly after we change the Thomas High School's ninth graders' reading and math scores to NaN, as shwon by these pictures:
#### Original Performance:
![original_performance](https://github.com/KJoshi111/School_District_Analysis/blob/main/original_performance.png)
#### Edited Performance:
![edited_performance](https://github.com/KJoshi111/School_District_Analysis/blob/main/edited_performance.png)
 
* Math and Reading Scores by Grade
  - The math and reading scores by grade for Thomas High School's ninth graders has changed to NaN, as shown by the pictures below:
#### Average Math Scores:
![average_math_scores_by_grade](https://github.com/KJoshi111/School_District_Analysis/blob/main/average_math_scores_by_grade.png)
#### Average Reading Scores:
![average_reading_scores_by_grade](https://github.com/KJoshi111/School_District_Analysis/blob/main/average_reading_scores_by_grade.png)

* Scores by school spending
 - Thomas High School comes into the $630 to $644 per capita spending range. As we can see, there was minor change by changing the ninth_grade scores to NaN:
#### Original Scores by School Spending:
![original_schools_by_per_capita_spending](https://github.com/KJoshi111/School_District_Analysis/blob/main/original_scores_by_school_spending.png)
#### Edited Scores by School Spending:
![edited_scores_by_per_capita_spending](https://github.com/KJoshi111/School_District_Analysis/blob/main/edited_scores_by_school_spending.png)

* Scores by school type
 - The scores by school type show that charter schools are overall doing better than District Schools, as shown below:
#### Original Performance by School Type:
![original_performance_by_school_type](https://github.com/KJoshi111/School_District_Analysis/blob/main/original_performance_by_school_type.png)
#### Edited Performance by School Type:
![edited_performance_by_school_type](https://github.com/KJoshi111/School_District_Analysis/blob/main/edited_performance_by_school_type.png)

## Summary:
The results show that replacing the math and reading scores of the ninth graders from Thomas High School to NaN made Thomas High School's overall performance worse, the scores by school spending decreased slightly for the $630 - $644 range, and finally, the scores by school type show that charter schools overall do better than district schools, although changing the ninth graders' scores to NaN made the charter schools' performance go down very slightly.
