# School_District_Analysis

# PyCitySchools

## Purpose
The purpose of this project was to return various metrics to the school board so they can compare passing rates with school types, budget dollars and school size. The pass rate metrics were focused primarily on reading and math. The first analysis was completed with all fifteen schools, across the ninth through twelfth grade. The final report was completed to compare data after academic dishonesty was discovered among the ninth grade students at Thomas High School.
### How is the district summary affected?
The district summary after the removal of the entire Thomas High School ninth-grade didn’t change the average or passing scores by a nominal amount. The largest decrease was the percentage of students passing reading, which saw a 0.3% drop.
### How is the school summary affected?
The school summary saw insignificant changes to the passing rates in math and reading. The passing rate in reading increased by 0.2% and the passing rate in math increased by 0.1% after the removal of the suspected academically dishonest students. 

All Students:
![image](https://user-images.githubusercontent.com/89363928/137607343-9936c07c-8bba-49c6-8848-14f73f0ba8ad.png)

Modified Students:
![image](https://user-images.githubusercontent.com/89363928/137607335-508895fe-5fbe-499e-86e5-0fa6f93813c0.png)

### How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
Replacing the scores of the ninth-grade students still had Thomas High School second in the overall standing of passing rates compared to the fourteen other schools in the state. 

### How does replacing the ninth-grade scores affect the following?
 - Math and reading scores by grade
Replacing the ninth-grade scores with NaN didn’t change the data for any other grade, and only removed them from the summary calculations. Had we filled the data with 0’s the data sets would have changed significantly and skewed all the numbers for the district.
 - Scores by school spending
The scores by school spending didn’t change at all since we still included the ninth-grade students in the analysis. The reason behind that decision was because academic dishonesty doesn’t mean that the school no longer has to support those students and would still need the budgeted dollars.

![image](https://user-images.githubusercontent.com/89363928/137607358-fcc01b1a-a907-431a-8748-3bdc5988bcc9.png)

 - Scores by school size & school type
The scores by school size didn’t change with the first analysis since the total amount of students is over thirty-thousand and we only removed the scores for about four-hundred students. Once I changed the formatting to include two decimal places, we can see that Thomas High School, a medium sized school, saw a slight decrease in scores.

## Summary
I can neither confirm nor deny the suspected academic dishonesty at Thomas High School and the removal of the ninth-grade class did not change their overall standing in the district. In the school size analysis, we can see that the precent passing math decreased by 0.02% and the percentage passing reading decreased by 0.06%. The combined passing rate decreased by 0.06% after removing the ninth-grade class. The analysis by school type only changes if we review the data to the third decimal place. In this instance, we can see that the average math score decreased by 0.009% and the average reading score decreased by 0.006%. 

![image](https://user-images.githubusercontent.com/89363928/137607454-2d5cb92a-75e5-42f2-9077-ba9fbefe1c00.png)

All Students Charter Type:
![image](https://user-images.githubusercontent.com/89363928/137607387-18c7c010-bd1b-42d8-b39d-84a914a264fa.png)

Modified Students Charter Type:
![image](https://user-images.githubusercontent.com/89363928/137607378-68de4c6c-b80c-4c0f-9a19-eedc9570222d.png)

