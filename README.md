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

Student data after replacing the ninth graders’ math and reading scores with NaN
 
 <img width="1402" alt="Screen Shot 2022-01-21 at 11 56 40 AM" src="https://user-images.githubusercontent.com/72629108/150622440-cae5d10b-b5a9-4f14-b19f-999f1c6190e8.png">
  
 Student data which shows Thomas high school 9th graders' 

<img width="1212" alt="Screen Shot 2022-01-21 at 8 04 43 PM" src="https://user-images.githubusercontent.com/72629108/150622551-35a3f8df-9801-4a7c-9763-a000b512b0ce.png">

  
  *District summary
    You can see slight difference in the overall pass percent in the district summary after replacing the ninth graders’ math and 
    reading scores.
    
    District summary after adding NaN 
   
   <img width="1286" alt="Screen Shot 2022-01-21 at 1 06 53 PM" src="https://user-images.githubusercontent.com/72629108/150623304-d091161d-c5bb-4a2e-997d-e4d18fed7c33.png">

District summary before adding NaN 
    <img width="1276" alt="Screen Shot 2022-01-21 at 11 58 01 AM" src="https://user-images.githubusercontent.com/72629108/150622016-75c1bda7-180c-44f8-a6a6-a407b2e6ad02.png">

 
 *Per school summary
    The per school summary hasn’t changed for other schools after adding nan to 9th graders of Thomas high school. You can see a 
    drastic change in the overall pass percentage of Thomas high school in the school summary. After replacing the ninth graders’ 
    math and reading scores, Thomas High School’s performance has decreased.
    
   <img width="1187" alt="Screen Shot 2022-01-21 at 8 08 32 PM" src="https://user-images.githubusercontent.com/72629108/150623349-7f130b76-e732-4522-bdb8-c0d62f482d38.png">
   
   Then we calculated the the percentage of 10th-12th grade students percentage of passing math,percentage of passing reading,(overall passing percentage ) passing math and reading  from Thomas High School replaced the values with newly calculated values. Now the dataframe is like
    
   <img width="1187" alt="Screen Shot 2022-01-21 at 8 17 23 PM" src="https://user-images.githubusercontent.com/72629108/150623364-c6e94de2-2649-4979-a10b-4d2906fa1e46.png">

 <img width="1202" alt="Screen Shot 2022-01-21 at 8 38 53 PM" src="https://user-images.githubusercontent.com/72629108/150623408-023e6fec-f3f9-4620-acbc-e32e7f617cfa.png">

 *Math and reading scores by grade
    We created a dataframe with Math and reading scores by grade and we got NaN values for 9th grade students of Thomas high 
    school
    <img width="1181" alt="Screen Shot 2022-01-21 at 8 19 22 PM" src="https://user-images.githubusercontent.com/72629108/150622937-81f63fb7-ac5a-4f10-b655-4e09de481732.png">

<img width="1181" alt="Screen Shot 2022-01-21 at 8 19 35 PM" src="https://user-images.githubusercontent.com/72629108/150622947-cab804aa-ca88-418b-b906-87e62be5b80c.png">

  
  *Scores by school spending
    There is not much difference we can see in the values of Scores by school spending by replacing the ninth-grade scores. We can 
    also see that those schools which spend less per student have better overall passing percent
  
  <img width="1294" alt="Screen Shot 2022-01-21 at 12 44 01 PM" src="https://user-images.githubusercontent.com/72629108/150622990-6f495ecf-1d80-4945-bcf4-31e3df64c87d.png">

  *Scores by school size
    Scores by school size, larger School size adversely affected the overall passing percent. But smaller and medium sized 
    schools has almost similar overall passing percent. Replacing the ninth-grade scores hasn’t affected Scores by school size
  
  <img width="1267" alt="Screen Shot 2022-01-21 at 12 44 58 PM" src="https://user-images.githubusercontent.com/72629108/150622998-d67b5b27-01f6-434b-be72-a3b9ef6e13ca.png">

  *Scores by school type
    Charter schools have more passing percent when compared to district schools. Replacing the ninth-grade scores hasn’t affected 
    Scores by school type
   
   <img width="1266" alt="Screen Shot 2022-01-21 at 12 45 33 PM" src="https://user-images.githubusercontent.com/72629108/150623019-ac298986-801d-4459-8b07-508bf17c4308.png">

  ##Summary
  After replacing the ninth graders' scores with NaN these are the changes,

  • There is a slight decrease in overall passing percent of students in District summary
  • When we look into per school summary, you can see a drastic decrease in the overall passing percent of Thomas High School and 
    it doesn’t affect other schools in any possible ways
  • This has popped out Thomas High School from Top 5 Schools.But we calculated the the percentage of 10th-12th grade students percentage of passing math,percentage     of passing reading,(overall passing percentage ) passing math and reading  from Thomas High School replaced the values with newly calculated values.That brought     the Thomas High School to second position in the list. 
  • When we looked into the average math score for each grade level from each school, we can see that Thomas High School 9th
    graders' scores have nan instead of a value. We can confirm that the changes worked as expected as we can see NaN in the result


  
   
  
