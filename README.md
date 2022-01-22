# School_District_Analysis
Pycity schools with Pandas
  ##Introduction
    Maria is a chief data scientist of city schools. In this project School district analysis, we were helping Maria on analyzing 
    student funding and students’ standardized test data. We aggregated the data and illustrated the trends of school performance. 
    Then school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic 
    dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. So Maria 
    has asked us to replace the 9 th grade math and reading scores for Thomas High School with NaNs while keeping the rest of the 
    data unharmed. Then perform the analysis and find out the fluctuations in overall analysis

 ##Results
  
  *District summary
    You can see slight difference in the overall pass percent in the district summary after replacing the ninth graders’ math and 
    reading scores
 
 *Per school summary
    The per school summary hasn’t changed for other schools after adding nan to 9th graders of Thomas high school. You can see a 
    drastic change in the overall pass percentage of Thomas high school in the school summary. After replacing the ninth graders’ 
    math and reading scores, Thomas High School’s performance has decreased

 *Math and reading scores by grade
    We created a dataframe with Math and reading scores by grade and we got NaN values for 9th grade students of Thomas high 
    school
  
  *Scores by school spending
    There is not much difference we can see in the values of Scores by school spending by replacing the ninth-grade scores. We can 
    also see that those schools which spend less per student have better overall passing percent
  
  *Scores by school size
    Scores by school size, larger School size adversely affected the overall passing percent. But smaller and medium sized 
    schools has almost similar overall passing percent. Replacing the ninth-grade scores hasn’t affected Scores by school size
  
  *Scores by school type
    Charter schools have more passing percent when compared to district schools. Replacing the ninth-grade scores hasn’t affected 
    Scores by school type
   
  ##Summary
  After replacing the ninth graders' scores with NaN these are the changes,

  • There is a slight decrease in overall passing percent of students in District summary
  • When we look into per school summary, you can see a drastic decrease in the overall passing percent of Thomas High School and 
    it doesn’t affect other schools in any possible ways
  • This has popped out Thomas High School from Top 5 Schools
  • When we looked into the average math score for each grade level from each school, we can see that Thomas High School 9th
    graders' scores have nan instead of a value


  
   
  