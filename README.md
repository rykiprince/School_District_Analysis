# School_District_Analysis
## Overview
Peforming analysis for school district student information with Python. Analyse the different performance of students' math and reading scores in different school capita, school types, school sizes. After the school board has notified that there is evidence of academic dishonesty in Thomas HS ninth graders, we also perfom analysis by removing the 9th grade score from Thomas HS to see if there is any impact on the results.

# Results
### How is the district summary affected?
_**Original District Summary**_
![oritginal_ district summary](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/District_summary_df.png)
_**Updated District Summary**_
![updated_district_summary](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/updated_district_summary_df.png)
- There are total 15 school in this district with 39,170 students. After removing the 9th graders from Thomas HS, all the score metrics go down slightly.
  
### How is the school summary affected?
_**Original School Summary**_
![original_school_summary](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/school_summary.png)
_**Updated School Summary**_
![updated_school_summary](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/updated_school_summary.png)
- As we only replacing grades in Thomas HS graders, it is the only one has change with the score metrics.
- The results for average math score, passing math %, passing reading %, and overall passing % decreased slightly.
- The result for average reading score increased.
    
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
_**Original Top Five School Rank**_
![original_top_schools](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/top_schools.png)
_**Updated Top Five School Rank**_
![updated_top_schools](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/updated_top_schools.png)
- The removal 9th graders' math score and reading score didn't impact Thomas HS rank over all other schools.
    
### How does replacing the ninth-grade scores affect the following:
### - Math and reading scores by grade
_**Original Score by Grades**_

![original_score_by_grade](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/original_score_by_grades.png)

_**Updated Score by Grades**_

![updated_score_by_grade](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/updated_score_by_grades.png)
    
- Only the score from Thomas HS 9th graders got removed. The removal didn't affect other graders or schools.
    
### - Scores by school spending
_**Original Score by School Spending**_
![score_by_school_spending](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/spending_summary.png)
  
_**Updated Score by School Spending**_
![updated_by_school_spending](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/updated_spending_summary.png)
      
- As Thomas HS is in the "$630-644" bin, only the results of this category was impacted.
- The average reading score in this bracket increased slightly.
- All other score metrics decreased slightly.
   
### - Scores by school size
_**Original Score by School Size**_
![original_score_by_school_size](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/school_size_summary.png)
_**Updated Score by School Size**_
![updated_score_school_size](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/updated_school_size_summary.png)

- As Thomas HS is in the medium school size bin, only the results of this category was impacted.
- The average reading score in this bracket increased slightly.
- All other score metrics decreased slightly.

### - Scores by school type
_**Original Score by School type**_

![school_type_summary](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/school_type_summary.png)
_**Updated Score by School type**_
![updated_school_type_summary](https://github.com/rykiprince/School_District_Analysis/blob/main/Resources/updated_school_type_summary.png)

- As Thomas HS is a Charter School, only the results of this category was impacted.
- The average reading score in this bracket increased slightly.
- All other score metrics decreased slightly.

# Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
1. After the math and reading scores of 9th graders from Thomas HS were omitted, all 5 score metrics result as slightly decreased.
2. As for Thomas HS, replacing reading and math scores for the ninth grade results to the average reading score increased slightly but the average math score decreased slightly as well as all passing percentages.
3. The replacement of reading and math score didn't impact Thomas HS' ranking over all other schools in the district.
4. All the categories analysis result as the same way as Thomas HS itself in the specific category that it falls to. Thus, in the group of school spending $630 to 644 per student, and group of Medium school size, and group of Charter School, the average reading score increased slightly, while the average math score and all passing percentages decreased slightly.
