# School_District_Analysis
## Overview of this Project 

In this project, we analyzed the data for every school district to provide visual analysis (Data Frames) of the students' overall testing performances for math and reading as well as funding for every school mentioned in the dataset. Our school district summary consists of the summzarization of the key metrics:

- Total number of students
- Total number of schools
- Total budget
- Average math score
- Average reading score
- Percentage of students who passed math
- Percentage of students who passed reading
- Overall passing percentage

Moreover, we had to perform this analysis twice as officials noticed academic dishonesty for the math and reading scores for Thomas High School to determine if the changes in this report had affected the overall analysis. 

## Results 

We started this analysis by setting the ninth graders' scores to NaN. Once the ninth graders' scores are replaced by NaN, we updated the district summary data frame to see what is the overall passing percentage for the entire district now. The Data Frame below in Figure 1 displays the district's overall passing percentage to 64.9%. In relation to just Thomas High School's overall percentage, it went from 90% to 65% once we removed the ninth graders. Adding onto that, our analysis also revealed that Thomas High School is no longer in the top 5 performing schools. 

*Figure 1: w/ ninth graders' performance data*

<img width="994" alt="Screen Shot 2022-07-13 at 10 33 20 PM" src="https://user-images.githubusercontent.com/106577074/179100953-9885ae92-3008-4498-b89a-7aac1b4ed495.png">

*Figure 2: w/out ninth graders' data = NaN*

<img width="585" alt="Screen Shot 2022-07-14 at 3 48 13 PM" src="https://user-images.githubusercontent.com/106577074/179101052-bb21b945-c69e-4046-a337-b0cdf2952383.png">

### Aftermath of Removing Ninth-Graders' Scores 

- math and reading scores by grade: THS is still passing in their overall percentage -> math: 93.2% & reading: 97.1% & overall percentage: 90.6% 

*Figure 3* 

<img width="746" alt="Screen Shot 2022-07-14 at 4 44 07 PM" src="https://user-images.githubusercontent.com/106577074/179119207-dfd8b778-f8ba-424b-8a6f-812add838130.png">

- scores by school spending: for the spending range of $630-$644, it seems the overall passing percentage decreased by 0.1%

*Figure 4*

<img width="745" alt="Screen Shot 2022-07-14 at 4 43 50 PM" src="https://user-images.githubusercontent.com/106577074/179119237-6589e4c7-63cf-44e0-b056-896683a09f85.png">

- scores by school size: for schools with a large student population, range from 2000-5000, the overall passing percentage was 58%. So the bigger the school population, the less the overall passing percentage.

*Figure 5*

<img width="753" alt="Screen Shot 2022-07-14 at 4 43 25 PM" src="https://user-images.githubusercontent.com/106577074/179119263-5dbfb9f5-58a9-4501-a88f-bb129885a85c.png">

- scores by school type: Overall, Charter schools did a lot better than District school type by an overall difference of ~44%. 

*Figure 6*

<img width="778" alt="Screen Shot 2022-07-14 at 4 43 19 PM" src="https://user-images.githubusercontent.com/106577074/179119314-6a634b0c-900d-4bb9-9d83-ee43dfceffa7.png">

## Summary 

Overall, it's difficult to determine how much academic dishonesty was included in our dataset and how it could've skewed our analysis. As we don't know which indiviudal had commited fraud with their tests, we had to remove the entire ninth graders' test scores from our overall analysis. 

Therefore, when we replaced Thomas High School's ninth graders' scores with NaN in our data frame, the district and Thomas High School itself had their overall percentages decrease and THS was no longer part of the top 5 performing schools. Moving forward, when we gathered the student count for THS and excluded the ninth graders, THS regained its position as one of the top 5 performing schools and their math/reading scores as well as overall percentage had increased once again. 
