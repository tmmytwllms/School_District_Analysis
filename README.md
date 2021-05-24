# School_District_Analysis

## Resources
- Data:
  -students_complete.csv
  -schools_complete.csv
- Software:
  -Python 3.7.8
  -Jupyter Notebook
  -Pandas
  -Numpy
  -Microsoft Excel 2019
<br/>
<br/>

## Overview
The purpose of this project was to determine the average grades and percentage of students passing math and reading for 15 high schools, grades 9-12. This project used a combination of python, pandas, jupyter notebook, and numpy in order to calculate the average grades and percentage of students passing math, reading, and both. Additionally, this project determined math and reading scores and percentages based on grade level, school budget, size, and school type.

Afterwards, new information was obtained that the Thomas High School 9th grade math and reading scores were dishonest, and these values were replaced with NaN values using numpy. The code was then further refactored and formatted to reflect these changes, and provide the aforementioned statistics based on the new data.

## Results
### District Summary:
The district summary saw very little change after replacing the Thomas High School math and reading scores were replaced with NaNs. The original student count was 39,170, and after refactoring the code it was 38,709, which was roughly a one percent difference from the original count.
<br/>
Original District Scores  
![original_district](https://user-images.githubusercontent.com/82389466/118375258-af8a6c00-b58e-11eb-8c29-4b16ef7913e8.png)
<br/>
Challenge District Scores
![challenge_district](https://user-images.githubusercontent.com/82389466/118375263-bdd88800-b58e-11eb-8190-6082243fbb22.png)
<br/>
<br/>
### Per School Summary
Similar to the district summary, the amount of 9th graders at Thomas High School relative to their total number of students, made little difference in the overall scores and passing percentages. Initially, after removing the 9th grade scores altogether, the score averages and percentage had much lower values due to the number of null grades. After further refactoring of the code, the average scores and percentages for Thomas High School were updated and replaced to reflect the scores of grades 10-12.
<br/>
Shown below is a comparison of the two Per School Summary dataframes, which 
<br/>
Original Per School Summary
![original_per_school](https://user-images.githubusercontent.com/82389466/118375552-4572c680-b590-11eb-81af-7a9652f5c927.png)![challenge_per_school](https://user-images.githubusercontent.com/82389466/118375557-4e639800-b590-11eb-99b5-3aa05db23ad5.png)
<br/>
Challenge Per School Summary
![Uploading challenge_per_school.png…]()
<br/>
<br/>
### Thomas High School Performance
After the district summary and per school summaries were completed, a analysis to rank the schools based on overall passing percentage was completed. Once again, removing the 9th grade student scores had little to no effect. However, the scores and percentages did see an increase in the tenths decimal place. Thomas High School remains the second highest performing high school based off of overall passing percentage.
<br/>
Original Top 5
![original_topbottom](https://user-images.githubusercontent.com/82389466/118378770-eae36580-b5a3-11eb-996b-9cddd2061a84.png)
<br/>
Challenge Top 5
![challenge_topbottom](https://user-images.githubusercontent.com/82389466/118378776-f46ccd80-b5a3-11eb-94cf-0b0d86dd8e66.png)
<br/>
<br/>
### Additional Changes
- Math and reading scores by grade did not see a significant change either, but did see an increase less than a percent for both math and reading in the percentage passing.
- The NaN values also had no affect on the average scores by their spending per student, size, and type.
![challenge_scores_spending](https://user-images.githubusercontent.com/82389466/118379146-883f9900-b5a6-11eb-9e94-b1d6c4dd84f5.png)
![challenge_size_scores](https://user-images.githubusercontent.com/82389466/118379152-8a095c80-b5a6-11eb-8ff4-bc3f2c7f1106.png)
![challenge_type_scores](https://user-images.githubusercontent.com/82389466/118379161-8bd32000-b5a6-11eb-9472-337f201d2721.png)
<br/>
<br/>
## Summary
Changes Observed
1. All reading and math averages for 9th grade students at Thomas High School were replaced with NaN values.
2. Overall passing percentages in reading and math for Thomas High School increased slightly.
3. Initially, without recalculating passing percentages based on new student counts, the passing percentages dropped into the 60% range.
4. Overall average grades for Thomas High School increased slightly.
