# School_District_Analysis
## Overview
Peforming analysis for school district student information with Python. Analyse the different performance of students' math and reading scores in different school capita, school types, school sizes. After the school board has notified that there is evidence of academic dishonesty in Thomas HS ninth graders, we also perfom analysis by removing the 9th grade score from Thomas HS to see if there is any impact on the results.

# Results
### How is the district summary affected?
  - **Original District Summary**
![oritginal_ district summary](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/District_summary_df.png)
  - **Updated District Summary**
![updated_district_summary](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/updated_district_summary_df.png)
  
  There are total 15 school in this district with 39,170 students. After removing the 9th graders from Thomas HS, all the score metrics go down slightly.
### How is the school summary affected?
  - **Original School Summary**
![original_school_summary](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/school_summary.png)
  - **Updated School Summary**
![updated_school_summary](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/updated_school_summary.png)
    - As we only replacing grades in Thomas HS graders, it is the only one has change with the score metrics.
    - The results for average math score, passing math %, passing reading %, and overall passing % decreased slightly.
    - The result for average reading score increased.
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - **Original Top Five School Rank**
![original_top_schools](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/top_schools.png)
  - **Updated Top Five School Rank**
![updated_top_schools](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/updated_top_schools.png)
    - The removal 9th graders' math score and reading score didn't impact Thomas HS rank over all other schools.
### How does replacing the ninth-grade scores affect the following:
### - Math and reading scores by grade
  - **Original Score by Grades**

![original_score_by_grade](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/original_score_by_grades.png)
  - **Updated Score by Grades**

![updated_score_by_grade](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/updated_score_by_grades.png)
    - Only the score from Thomas HS 9th graders got removed. The removal didn't affect other graders or schools.
### - Scores by school spending
  - **Original Score by School Spending**
![score_by_school_spending](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/spending_summary.png)
  - **Updated Scores by School Spending**
![updated_by_school_spending](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/updated_spending_summary.png)
    - 
### - Scores by school size
### - Scores by school type

# Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
