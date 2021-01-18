# School_District_Analysis

## Overview of the Analysis
The purpose of our updated analysis was to update the school district analysis results previously obtained due to academic dishonesty that occurred at Thomas High School at the ninth grade level. We replaced the math and reading scores for Thomas High School while keeping the rest of the analysis intact.

## Results
- The district summary was affected very slightly:

Module District Summary:
![Module District Summary DataFrame](/Resources/Module_District_Summary.png)
Challenge District Summary:
![Challenge District Summary DataFrame](/Resources/Challenge_District_Summary.png)

These small differences are likely due to rounding error, but you can see that the ninth graders from Thomas High School were not accounted for in the new analysis (the number of students is lower).

- The school summary differs a bit after the new analysis, as well:

Module School Summary:
![Module School Summary DataFrame](/Resources/Module_School_Summary.png)
Challenge School Summary:
![Challenge School Summary DataFrame](/Resources/Challenge_School_Summary.png)

Thomas High School's numbers are slightly different after removing the ninth graders. Not much changed, as the school remains one of the highest performing of the list.

- Replacing Thomas High School's ninth grade math & reading scores did not have a huge affect on their overall performance. During the first analysis, their percentage passing math was 93.3%, percentage passing reading was 97.3%, and overall passing percentage was 90.9%. After removing the ninth grade data, their percentage passing math was 93.2%, percentage passing reading was 97.0%, and overall passing percentage was 90.6%. Removing the ninth grade grades data resulted in a drop in each passing percentage, but a very slight one.

Our analysis had an affect on the overall data in the following ways:
- Math & reading scores by grade: removing Thomas High School's math & reading scores for ninth grade only had an affect on their ninth grade results. We replaced all grades with NaN in our analysis so that they were not taken into affect when we performed our calculations. This had an overall affect on the data due to these grades were not taken into consideration when comparing data for ninth grade across schools.
- Scores by school spending, scores by school size, and scores by school type all remained the same as prior to removing the ninth grade results from Thomas High School. This could have been due to the fact that only less than 500 grades were removed from the data, so it didn't have much of an affect on the overall calculations. This could have also been due to human error made in our analysis.

## Summary
By replacing Thomas High School's math & reading grades with NaN, this led to a less accurate snapshot of that individual school's performance. This could definitely cause issues for the individual school in terms of budgeting, or how they plan to address providing support for ninth grade students in math & reading subjects. As far as the district analysis as a whole, I only saw slight changes in the overall numbers by removing this data. I think this could be either due to the fact that such a small number of student grades were removed from the overall grade total (less than 500 ninth graders at Thomas High School), or due to error while performing the analysis. Even with removing the ninth grade student grades from the analysis, Thomas High School remained one of the highest performing schools.
