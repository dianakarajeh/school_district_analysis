# School District Analysis
Perform a reanalysis of PyCity Schools reading and math scores for ninth graders at Thomas High School in order to address the reporting of academic dishonesty to the school board.
## Project Overview
#### Maria, the Chief Data Scientist for PyCity School District, has been notified that there has been evidence of academic dishonesty when reporting the scores of math and reading standardized tests.  A thorough analysis was already done for all the schools in the PyCity School District with regards to math and reading scores for 9-12th graders.  After figuring out about the academic dishonesty, Maria decided her team had to reanalyze the data to ensure the Thomas High School ninth grade reading and math scores are accurately reported to the school district board.
## Results
#### - When the reanalysis for Thomas High School occurred, the district summary was slightly altered for Charter school type only since Thomas High School is a Charter School. Before reanalysis the district summary is seen below:
#### <img width="720" alt="Screen Shot 2022-03-20 at 7 13 12 PM" src="https://user-images.githubusercontent.com/99656224/159190168-72a5da28-6572-4418-852f-968961a60226.png">
#### - After the reanalysis was done, the district summary for charter schools is seen below:
#### <img width="726" alt="Screen Shot 2022-03-20 at 7 13 43 PM" src="https://user-images.githubusercontent.com/99656224/159190175-96fe9e7e-e20a-4f93-9f93-8a91d31939d8.png">
#### - As seen above, before the analysis was redone to account for the academic dishonesty at Thomas High School, the average math and reading scores for Charter schools in the district was 83.473852 and 83.896421 respectively.  After the reanalysis was done, the average math and reading scores for the district were 83.465425 and 83.902315 respectively.
#### - The school summary was affected in the sense that the Thomas High School was still listed as one of the top five schools in the district but the percentages were slightly altered.  
#### - Before the reanalysis was done is seen below: 
#### <img width="987" alt="Screen Shot 2022-03-20 at 7 05 54 PM" src="https://user-images.githubusercontent.com/99656224/159190688-1778e7ff-9c06-4757-a41b-9bed38fb7cfe.png">
#### - After the reanalysis was done is seen below:
#### <img width="986" alt="Screen Shot 2022-03-20 at 7 06 21 PM" src="https://user-images.githubusercontent.com/99656224/159190699-841ba375-ea56-4885-9c67-0d931a6ebdf7.png">
#### - Percent of students passing math, passing reading, and overall passing ALL _decreased_ after reanalysis was done to account for the academic dishonesty.  Although Thomas High School is still in the top five, they seemingly fell in terms of performance in both categories.
#### - Replacing the ninth-grade scores ended up affecting more than just the district and school summary.
#### - The ninth-grade scores for math went from 83.590022 to NaN and reading scores went from 83.728850 to NaN.  This alters the data as these numbers are now taken out of the dataset and do not play a role in the overall scores of ninth grade.
#### - Since Thomas High School falls within the 630-645 spending bin, those values were altered. Before analysis is seen below:
#### <img width="848" alt="Screen Shot 2022-03-20 at 7 48 51 PM" src="https://user-images.githubusercontent.com/99656224/159191391-145a7965-4df6-4d63-b58d-1693d883286a.png">
#### - After reanalysis is done of spending scores is seen below:
#### <img width="829" alt="Screen Shot 2022-03-20 at 7 49 12 PM" src="https://user-images.githubusercontent.com/99656224/159191407-bf5cf60b-6e9b-4949-aa55-e34da0c9f6c8.png">
#### - Thomas High Schools falls under the large school Category, but even after the reanalysis was done there were no changes in scores of average math and reading scores.  Before and after the reanalysis, average math and reading scores for a large school size were both 77.7 and 81.3 respectively.
#### - Depending on whether or not the schools were charter or district schools, charter type changed values because Thomas High School is a charter school.
## Summary
#### The changes that were observed after reanalyzing the data were the school type values, ranking of Thomas High School, school summary, and overall passing rate for the entire high school.
