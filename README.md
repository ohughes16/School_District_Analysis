# School District Analysis

## Overview of the school district analysis: Explain the purpose of this analysis.
Maria asked me to re-analyze the school districts test scores after the first analysis showed evidence of 9th grade math and reading scores being falsified. The following analysis will report on how removing the falsified scores affected the overall analysis of math and reading test scores for the district, schools, and grade levels.

## Results: 

### - How is the district summary affected?

Removing the Thomas High School ninth grade scores didn't affect the district summary very much. The Thomas High School 9th grader count is 461, which is only 1.2% of entire school district. 

### - How is the school summary affected?

School summary before THS 9th grade scores were removed
![School_Ranking_Before](https://user-images.githubusercontent.com/64506842/95776690-ab554380-0c79-11eb-9bde-f6b37e096d3b.png)

School summary after THS 9th grade scores were removed

![School_Ranking_After](https://user-images.githubusercontent.com/64506842/95777002-36ced480-0c7a-11eb-8afd-ea36e48cde64.png)

As you can see, Thomas High School remains as the school with the second highest overall percentage passing, however, removing the 9th graders scores decreased the overall passing percentage by 0.32%. With a School that has 1,635 students, that is a decrease in 52 students passing vs not passing. The average reading score increased by 0.047152 points and the average math score decreased by 0.067412 points for Thomas High school. 

### - How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Thomas High School remained as the school with the second highest overall passing percentage when compared to other schools.

## - How does replacing the ninth-grade scores affect the following:

### Math and reading scores by grade

**Before 9th grade THS scores removed**

![ReadingScores_by_School_andGrade](https://user-images.githubusercontent.com/64506842/95773389-3aab2880-0c73-11eb-8320-1c4dc0d2c213.PNG) ![MathScores_by_School_andGrade](https://user-images.githubusercontent.com/64506842/95773398-40a10980-0c73-11eb-878f-c2b2ff8088e7.PNG)

**After 9th grade THS scores removed**

![reading_score_by_grade](https://user-images.githubusercontent.com/64506842/95772751-1b5fcb80-0c72-11eb-929c-7a56f2cd5339.PNG) ![math_scores_by_grade](https://user-images.githubusercontent.com/64506842/95772776-231f7000-0c72-11eb-89f4-0b93adb83abd.PNG)

### Scores by school spending

**Before 9th grade THS scores were removed**

![School_Spending_Before](https://user-images.githubusercontent.com/64506842/95773647-ba38f780-0c73-11eb-808f-55e789c78602.PNG)

**After 9th grade THS scores were removed**

![School_Spending](https://user-images.githubusercontent.com/64506842/95701883-92a84780-0bff-11eb-9b9a-1a4c6311d91f.PNG)

### Scores by school size

![Schools_by_size_before](https://user-images.githubusercontent.com/64506842/95777917-ef494800-0c7b-11eb-95d7-dcfa07c0ebad.PNG) ![Schools_by_size_after](https://user-images.githubusercontent.com/64506842/95777919-efe1de80-0c7b-11eb-9ba9-d780078bae2b.PNG)

Thomas High School is a "Medium" sized school. When comparing averages and grouping by school size, removing the 9th grade scores from Thomas High School did not affect the averages when grouped by School Size.

### Scores by school type

District Summary before removing 9th grade THS scores

![District_summary_before](https://user-images.githubusercontent.com/64506842/95774930-3cc2b680-0c76-11eb-9293-b277114bb178.PNG)

District summary after removing 9th grade THS scores

![District_summary_after](https://user-images.githubusercontent.com/64506842/95774931-3d5b4d00-0c76-11eb-9266-ec62a0836a8f.PNG)

As you can see in the above before and after visualizations of the district summary, there was little change after removing the 9th grade Thomas High School math and reading scores. Thomas High School is a Charter school, so we would be looking for an increase or decrease in the passing percentages, or average scores for the Charter Schools. The overall math_score average decreased by 0.008 and the reading_score average increased by 0.006 after the Thomas High School 9th graders were removed from the analysis. The overall passing percentage for Charter schools decreased by 0.04%. 

## Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

In summary, removing the reading and math scores of the 9th grade Thomas High School Students from the School District Analysis affected the percentages of students passing reading, math, and overall passing percentage for Thomas High School. It didn't affect Thomas High School's standing when compared to other schools, but it did affect the school's passing percentage by 0.32% which results in a decrease of 52 students passing for a school that size. 
