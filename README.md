# School_District_Analysis

## Overview
The purpose of this School District Analysis is to introduce a scenario that would alter our data analysis performed on the School District data: academic dishonesty amongst 9th graders from Thomas High School, a very particular cohort. As instructed by our supervisors, we are to remove math and reading scores for all 9th graders from Thomas High School and replace them with null values (NaN) so they will not figure into our calculations. Our responsibility is to determine how this will affect our District Summary and School Summary data.

## Results
While this academic dishonesty scandal from this cohort of 9th graders from Thomas High School directly affects scores for Thomas High School, it clearly will not affect scores from other schools. However, it affects our analyses in the following ways:
### District Summary, School Summary, and Thomas High School Performance
* The district summary scores were only slightly affected, given that there are still more than 38,000 test scores (observations) in the data. We see that the overall passing rate slightly decreased from 65.2% to 64.9%. The reading passing rate fell from 85.8% to 85.7%, and the math passing rate fell from 75.0% to 74.8%. Average reading scores stayed roughly around the same (given that scores were formatted to fit one decimal point) and average math scores fell from 79.0 to 78.9. This makes sense given that Thomas High School was ranked as one of the top 5 performing schools in our analysis.

 <img width="944" alt="Screen Shot 2021-11-30 at 11 13 25 AM" src="https://user-images.githubusercontent.com/92702922/144158919-d233df0c-46d7-432d-b0a6-dc13246b8e64.png">

 <img width="928" alt="Screen Shot 2021-11-30 at 11 13 55 AM" src="https://user-images.githubusercontent.com/92702922/144158944-3fab306b-b462-47cf-a75d-403e83f26987.png">

* As stated previously, the academic dishonesty scandal only affects scores for Thomas High School. In the school summary, all other schools remain with the same data except Thomas High School since we remove the math and reading scores for 9th graders. Therefore, we see that all the percentages (the overall passing rate, the math passing rate, and the reading passing rate) all decrease when replacing the THS 9th grade scores, but by less than a percentage point. As for the averages, the average math score decreases by less than 0.1 percentage points, while the average reading score increases by a similar amount when THS 9th grade scores are replaced.

 <img width="993" alt="Screen Shot 2021-11-30 at 11 24 43 AM" src="https://user-images.githubusercontent.com/92702922/144159685-dfcd8ab5-11d9-4cf4-9d5d-79df695ad823.png">
 
 <img width="1000" alt="Screen Shot 2021-11-30 at 8 49 29 PM" src="https://user-images.githubusercontent.com/92702922/144163051-901ba177-a79e-4848-aa1f-ac3115e96b23.png">

* Replacing the 9th graders' math and reading scores doesn't affect Thomas High School's performance relative to other schools. When obtaining the top 5 performing schools by overall passing rate, Thomas High School is still ranked as the 2nd best school after 9th grade scores are replaced, as can be seen below. This is despite the decrease in several of these testing score metrics previously mentioned. 

 <img width="999" alt="Screen Shot 2021-11-30 at 8 42 04 PM" src="https://user-images.githubusercontent.com/92702922/144162526-544a5999-51c8-4bb6-955c-5147da6ca31b.png">

### Scores by Grade, Spending Range, School Size, and School Type
* In the breakdown of math and reading scores by grade, THS scores for 9th grade show up as nullified (NaN) and we have no score for this cohort. All    other grades remain the same. 

 <img width="300" alt="Screen Shot 2021-11-30 at 8 44 03 PM" src="https://user-images.githubusercontent.com/92702922/144162616-6cfd1a7c-f47a-4475-9a64-2bfbcf837c10.png">

* We see that Thomas High School spends $630-644 per student in our analysis on budget spending ranges per student. When we categorize schools based on the different spending ranges, we see that the test scores for the $630-644 spending bin are altered since Thomas High School falls in this category. Similar to other results, the overall passing rate, math passing rate, and reading passing rate decreased by less than a tenth of a percentage point. Average math scores also fell by a similar amount, and average reading scores increased by a similar amount. Generally speaking, these metrics remained relatively stable.

 <img width="813" alt="Screen Shot 2021-11-30 at 5 47 52 PM" src="https://user-images.githubusercontent.com/92702922/144146195-e32c8206-0e6f-4785-a73d-1d3538268a4b.png"> 
 <img width="808" alt="Screen Shot 2021-11-30 at 5 50 02 PM" src="https://user-images.githubusercontent.com/92702922/144146414-5149ff59-5872-41d3-964f-7ba39dccaabd.png"> 
 
* When schools are sorted by their size (number of students), the exclusion of Thomas High School 9th grade scores affect the *Medium* category, which includes schools that have between 1000-2000 students. Again, only the average reading score increases slightly. Average math score, passing math rate, passing reading rate, and the overall rate all decrease slightly.

 <img width="768" alt="Screen Shot 2021-11-30 at 6 54 30 PM" src="https://user-images.githubusercontent.com/92702922/144152115-f849040e-3a68-43f8-ae87-a112b8bde018.png">
 <img width="753" alt="Screen Shot 2021-11-30 at 6 56 16 PM" src="https://user-images.githubusercontent.com/92702922/144152148-e70ba71b-1971-4182-889e-52317f772ba1.png"> 

* When looking at test scores grouped by school type, we see that the charter school category is affected since Thomas High School is a charter school. The trend remains similar. Only the average reading score increases slightly. Average math score, passing math rate, passing reading rate, and the overall rate all decrease slightly as a result of the THS 9th grade score exclusion.

 <img width="703" alt="Screen Shot 2021-11-30 at 7 03 53 PM" src="https://user-images.githubusercontent.com/92702922/144152835-032dfc6b-b070-4f26-9c20-355cb0ddf2a0.png">  
 <img width="710" alt="Screen Shot 2021-11-30 at 7 04 41 PM" src="https://user-images.githubusercontent.com/92702922/144152901-666eddf8-c6f2-4d14-91bc-c245368cc29e.png"> 

## Summary
Four notable changes in the school district analysis as a result of the academic dishonesty scandal within Thomas High School were changes to the math passing rate, reading passing rate, average math score, and average reading score. The former three decrease very slightly whenever Thomas High School is part of the cohort we are observing, and the latter increases slightly. Our results don't drastically change given the high number of students we are observing, and when the cohort is larger (for example, when we look at scores for all schools), the amount of THS 9th graders is small compared to the more than 38,000 students whose scores remain the same. When isolating the scores for Thomas High School, and despite removing about one-quarter of their scores, we can see that each individual grade level is reflective of the general trend of math and reading scores, so their removal does not alter our general results significantly.








