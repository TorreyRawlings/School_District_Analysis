# School_District_Analysis
#### The purpose of this analysis was to give the school district an overview of their budget, the amount of students, and the overall passing along with some other specific statistics. While doing this overview we found we needed some adjustments made as the 9th grade class of Thomas High School scores could no longer be considered valid so we needed to adjust accordingly. 

### Overview of what was found after removing Thomas High School 9th grade scores: 

  - It looks like the District Summary was only slightly altered removing the Thomas High School 9th graders. The _Overall Passing_ percentage was only .3% lower. The _Passing Math_ percentage was .2% lower and the _Passing Reading_ percentage was .1% lower. 
  - For the School summary it looks like Thomas High School still resides in the top 5 even after the data was changed, it even kept it's place as #2 highest school in the district.
  - When doing the averages for 9th graders after removing their scores it seemed to drop it down to under 70% passing but once we only considered 10th, 11th, and 12th graders this brought the aveages back up. Thomas High School Still is comparable to the other top 5 schools in the percentage passing math, reading, and overall passing percentage. 
  - Replacing the 9th graders scores made the following differences in our datasets: 
    - _For Math and Reading Scores by Grade_: This made no signficant difference since the 10th-12th graders data would stay the same. The only large difference is that the 9th grade data shows as NaN and as such we cannot compare.
    - _Scores by School Spending_ did not change significantly by replacing these scores. The spending range is the same and as mentioned above the percentage passing each section was only slightly modified.
      - I will state that it does seem as schools with a smaller budget per student had overall higher math & reading scores as well as a higher overall passing percentage. This is not to say that there should be less spending budgets but that there may be another factor playing into these students getting better scores that isnt directly coorelated with money.
    - _Scores by School Size_ had no noticable diffferences in scores from removing the 9th graders from Thomas High School. 
      - To note in this section it seems once we get to over 2000 students per school the overall passing drops significantly.  
    - _Scores by School Type_ also had no noticable differences in scores from removing the 9th graders from Thomas High School.
      - It seems charter schools do significantly better in having kids who are passing math and reading. 

### Summary of Analysis: 
It doesn't look like removing the 9th graders from Thomas High School had much of a significant overall impact to the datasets we were analyzing for the district. There is still a lot of beneficial information to take away from this data though regardless but any concern that the 9th graders of Thomas High skewed too much of the data can be dismissed. 
