# School_District_Analysis

## Overview of the Analysis
The purpose of this analysis was to update the school district analysis results previously obtained in our first analysis due to academic dishonesty that occurred at Thomas High School at the ninth grade level. We replaced the math and reading scores for Thomas High School while keeping the rest of the analysis intact.

## Results
- The district summary was affected very slightly:
![Module District Summary DataFrame](/Resources/Module_District_Summary.png)
![Challenge District Summary DataFrame](/Resources/Challenge_District_Summary.png)
These differences are likely due to rounding error, but you can see that the ninth graders from Thomas High School were not accounted for in the new analysis due to the number of students is lower.
- The school summary differs a bit after the new analysis, as well:
![Module School Summary DataFrame](/Resources/Module_School_Summary.png)
![Challenge School Summary DataFrame](/Resources/Challenge_School_Summary.png)
Thomas High School's numbers are slightly different after removing the ninth graders. Not much changed. Thomas is still one of the higher performing schools on the list.
- Replacing Thomas High School's ninth grade math & reading scores did not have a huge affect on their overall performance. During the first analysis, their % passing math was 93.3, % passing reading was 97.3%, and overall passing % was 90.9%. After removing the ninth grade data, their % passing math was 93.2%, % passing reading was 97.0%, and overall passing % was 90.6%. They are still a high performing school and remain the second highest performing school.
