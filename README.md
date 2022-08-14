Challenge 4
# School_District_Analysis

## 1. Overview of the school district analysis
### Project overview
In the PyCity school district, an analysis was conducted on student funding and students’ standardized test scores, where every student’s math and reading scores were collected. However, the school board believed that the data file showed evidence of academic dishonesty and that the reading and math scores for Thomas High School ninth graders had been altered, which requires a further investigation on the potential data alteration.

### Procedures
Originally, two files were provided to perform the analysis, schools_complete.csv and students_complete.csv. Because the potential alteration was identified in the students_complete.csv file. All math and reading scores for Thomas High School ninth graders in the students_complete file are going to be replaced with NaNs. However, the rest of the data will be kept unchanged.

Based on the new data created by replacement, the same set of summary tables will be created as the original analysis including the district summary, school summary, and other score summaries. 

## 2. Results
### District summary
Overall, the number of students is calculated as 38,709, which is lower than the original student count by the number of students in the ninth grade at Thomas High School. As shown in the table 1, the overall passing rate decreased slightly from 65.17% to 64.90%.

#### Table 1. District summary after change
![](https://github.com/Ryoichi2022/School_District_Analysis/blob/main/T1_PyCity_District_After.png)

School summary
By creating the school summary, changes are identified in the Thomas High School summary. As shown in the table 2 and 3, Thomas High School’s average score has changed from 83.42 to 83.35 in math and from 83.85 to 83.90 in reading. In addition, the passing rate of Thomas High School has decreased from 93.27% to 93.18%, 97.31% to 97.02%, and 90.94% to 90.63%, in math, reading and overall, respectively. 
Impact on Thomas High School’s performance relative to the other schools
According to the changes in the average scores and passing rates, the high school dropped from fourth to sixth place in the average math score and from first to third place in the reading passing rate. Otherwise, Thomas High School is ranked in the same place in both data.
Changes in the other score summaries
Both table 4 and 5 indicate the average score as NaN for Thomas High School as all math and reading scores have been removed from the data. In other summaries, no changes are identified based on the analysis at the one decimal place level. 


Summary

Changes in the updated school district analysis are summarized as the following four topics after the scores have been replaced.

As the average score becomes lower by replacement compared with the original average score in both math and reading. Therefore, the original scores for the ninth grader of Thomas High School could possibly be higher on purpose than they are.

Based on analysis, the average scores and passing rates have changed, but they seem immaterial. This might be because the number of students in the ninth grade at Thomas High School only accounts for 1.18%, or 461 students, of the total number of students in the school district.

The average scores will be expressed as NaN for the Thomas High School’s ninth graders until their scores are validated. However, it will not significantly influence the other analyses based on school spending, school size, and school type.
If academic dishonesty is considered pervasive as a result of further investigation on data from other graders of Thomas High School or other schools, another analysis will be necessary, which could greatly impact the consequences.
