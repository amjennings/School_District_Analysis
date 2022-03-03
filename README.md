# School_District_Analysis

## Project Overview
The purpose of this project was to provide an analysis of a school district. This analysis included the top five and bottom five performing schools, as indicated by overall passing rates from math and reading scores. Additionally, the average math and reading scores were calculated for each grade level at each school. School performance was also included based on the budget per student, the size, and the school type. This analysis was then adjusted to account for potential academic dishonesty for one grade in one high school. These grades were replaced with NaNs and the analysis was repeated.

## Results
- After the scores for ninth graders from Thomas High School were removed, the district summary was affected as shown by a slight decrease in the percentage of students passing math, passing reading, and the overall percentage passing. 
- The school summary specifically for Thomas High School shows increases in the percentage passing math, percentage passing reading, and overall percentage passing, as shown by the last three columns in the images below. 

Before:
<img width="744" alt="ths_summary_before" src="https://user-images.githubusercontent.com/98051208/156588327-15a38205-d259-4c83-aa89-75257c9a2875.png">

After:
<img width="744" alt="ths_summary_after" src="https://user-images.githubusercontent.com/98051208/156588384-3af876af-ed2d-4605-bb2a-94756a7363d7.png">

- Prior to replacing the ninth graders’ math and reading scores, the relative performance for Thomas High School was with other schools on the lower end with 65% of students passing. Following the replacement, Thomas High School moved up to the top five schools for performance based on overall passing. 

- The math and reading scores by grade for Thomas High School were affected as the scores were replaced by NaNs, as shown by the math scores below.

<img width="249" alt="math_scores_by_grade_before" src="https://user-images.githubusercontent.com/98051208/156591949-f806b8ee-3f8c-4b64-a14b-1364fabe64ab.png">


<img width="249" alt="math_scores_by_grade_after" src="https://user-images.githubusercontent.com/98051208/156591978-5e3e3857-b3e5-4ff2-b446-a5eeeb33b5d4.png">

- Replacing the ninth-grade scores did not affect scores by school spending, by school size, or by school type. This is likely to due to the fact the scores of the ninth grade students were so similar to the scores of students in other grades from the same school. 

## Summary: 
- The greatest affect of replacing the ninth-grade scores was seen in the school summary, as removal of these grades from the analysis resulted in Thomas High School demonstrating better performance. 
