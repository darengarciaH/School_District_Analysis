# School_District_Analysis
## Overview
The purpose of this School District Analysis is to introduce a scenario that would alter our data analysis performed on the School District data: academic dishonesty amongst 9th graders from Thomas High School, a very particular cohort. As instructed by our supervisors, we are to remove math and reading scores for all 9th graders from Thomas High School and replace them with null values (NaN) so they will not figure into our calculations. Our responsibility is to determine how this will affect our District Summary and School Summary data.
## Results
While this academic dishonesty scandal from this cohort of 9th graders from Thomas High School directly affects scores for Thomas High School, it clearly will not affect scores from other schools. However, it affects our analyses in the following ways:
  * The district summary scores were only slightly affected, given that there are still more than 38,000 test scores (observations) in the data. The picture below shows our district summary with THS 9th graders included:
<img width="944" alt="Screen Shot 2021-11-30 at 11 13 25 AM" src="https://user-images.githubusercontent.com/92702922/144095071-45c01816-442f-443f-a434-124e03687bd2.png">
Now, here is the updated district summary without THS 9th grader test scores:
<img width="928" alt="Screen Shot 2021-11-30 at 11 13 55 AM" src="https://user-images.githubusercontent.com/92702922/144095250-eba7199d-6707-4b25-bf23-0466b056b34b.png">
We see that the overall passing rate slightly decreased from 65.2% to 64.9%. The reading passing rate fell from 85.8% to 85.7%, and the math passing rate fell from 75.0% to 74.8%. Average reading scores stayed roughly around the same (given that scores were formatted to fit one decimal point) and average math scores fell from 79.0 to 78.9. This makes sense given that Thomas High School was ranked as one of the top 5 performing schools in our analysis.
 * As stated previously, the academic dishonesty scandal only affects scores for Thomas High School. In the school summary, all other schools remain with the same data except Thomas High School since we remove the math and reading scores for 9th graders. Here are the scores for THS with 9th grader scores *included*:
<img width="993" alt="Screen Shot 2021-11-30 at 11 24 43 AM" src="https://user-images.githubusercontent.com/92702922/144096846-d7cba852-68c4-4a06-b805-9f9902b4d3db.png">
Here are THS scores with 9th grader scores *excluded*:
<img width="996" alt="Screen Shot 2021-11-30 at 11 26 56 AM" src="https://user-images.githubusercontent.com/92702922/144097183-7aa5636a-cdeb-4d26-9cda-b3964a3bff50.png">

