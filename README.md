# School_District_Analysis

## Overview of the Analysis
The purpose of this analysis was to update the school district analysis results previously obtained in our first analysis due to academic dishonesty that occurred at Thomas High School at the ninth grade level. We replaced the math and reading scores for Thomas High School while keeping the rest of the analysis intact.

## Results
The district summary was affected very slightly:

![Module District Summary DataFrame](/Resources/Module_District_Summary.png)
![Challenge District Summary DataFrame](/Resources/Challenge_District_Summary.png)

These differences are likely due to rounding error, but you can see that the ninth graders from Thomas High School were not accounted for in the new analysis due to the number of students is lower.

The school summary differs a bit after the new analysis, as well:

![Module School Summary DataFrame](/Resources/Module_School_Summary.png)
![Challenge School Summary DataFrame](/Resources/Challenge_School_Summary.png)

Thomas High School's numbers are slightly different after removing the ninth graders. Not much changed. Thomas is still one of the higher performing schools on the list.

Replacing Thomas High School's ninth grade math & reading scores did not have a huge affect on their overall performance. During the first analysis, their % passing math was 93.3, % passing reading was 97.3%, and overall passing % was 90.9%. After removing the ninth grade data, their % passing math was 93.2%, % passing reading was 97.0%, and overall passing % was 90.6%. They are still a high performing school and remain the second highest performing school.

Our analysis had an affect on the overall data in the following ways:
- Math & reading scores by grade: removing Thomas' math & reading scores for ninth grade only had an affect on their ninth grade results. We replaced all grades with NaN in our analysis so that they were not taken into affect.
- Scores by school spending, scores by school size, and scores by school type all remained the same as they were prior to removing the ninth grade results. This could have been due to the fact that only less than 500 grades were removed from the data, so it didn't have much of an affect on the overall calculations. This could have also been due to error in our analysis.

## Summary
