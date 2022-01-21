# School_District_Analysis

## Project Overview and Purpose
- Purpose: Maria has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.
- Overview: Manipulate the data by using Python librarys, Pandas and juptyer notebook replace the scores for math and reading at Thomas High School for ninth graders. Then we will reuse that data to repopulate the school distrcit analysis to provide the new results.
## Results
* each 7 school disctrict metrics were affected by the change 
* How is the district summary affected?
  - The school district summary was affected only by the total number of students as shown in the figures below. If the students had an affect on the district metrics it was smaller than a hundreth percent.
  - School District Summary (with Thomas High School 9th Graders)
![AVGpassing_withTHS9th](https://user-images.githubusercontent.com/93004710/150437542-2a243d92-f881-451d-87be-fb4d1dc935cd.png)



  - School District Summary (without Thomas High School 9th Graders)
![AVGpassing_withOUTTHS9th](https://user-images.githubusercontent.com/93004710/150437730-44db4fbb-3d1b-46d2-ae65-41c1422bf526.png)




* How is the school summary affected?
  - The school summary was affected by the Thomas High School 9th Graders as shown in the figures below. The percent passing for math, reading, and overall passing was higher for Thomas High School after removing the 9th graders affecting the top performing schools in the district. Percent passing math went from 66.9% to 93.18%, percent passing reading went from 69.6% to 97.01%, percent overall passing went from 65.07% to 90.63%.
  
  - School Summary (with Thomas High School 9th Graders)
![schoolsummary_withTHS9th](https://user-images.githubusercontent.com/93004710/150439185-81fa5190-f8bb-4621-83d6-b63c03a2da1e.png)  
  

  
  
  - School Summary (without Thomas High School 9th Graders)
![schoolsummary_withOUTTHS9th](https://user-images.githubusercontent.com/93004710/150439252-bc995fba-38f1-4d1c-9e12-4a5d6f3c2207.png)



* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
* With Thomas High School's 9th Graders' still being counted it dropped Thomas High School towards the bottom of the pack of schools. When the 9th Graders from Thomas High School are taken out, Thomas High School is one of the top performing schools compared to the rest. The figures below show the difference in passing math, reading and overall passing at Thomas High School once replaced.
  - Thomas High School (with 9th Graders)
![schoolsummaryTHS_withTHS9th](https://user-images.githubusercontent.com/93004710/150573671-fa1e8e11-abcf-4a93-85fe-6baf9dd57147.png)




  - Thomas High School (without 9th Graders)
![schoolsummaryTHS_withOUTTHS9th](https://user-images.githubusercontent.com/93004710/150573717-d2254dcf-3e6d-4a64-8bcb-b1d8eb5d0bcb.png)




* How does replacing the ninth-grade scores affect the following:
    - Math scores by grade


![mathscores_bygrade](https://user-images.githubusercontent.com/93004710/150575247-9efbb344-71b9-4e36-a3f5-0ae0edfe34ae.png)




    - Reading scores by grade
    
    
![readingscores_bygrade](https://user-images.githubusercontent.com/93004710/150575267-07e35ce0-19cd-46e9-a93d-fa48cfb570ee.png)



    - Thomas High Schools' 9th Grade math and reading scores are replaced with NA.

    - Scores by school spending (with Thomas High School 9th Graders)
![perschool_spending(withTHS9th)](https://user-images.githubusercontent.com/93004710/150575838-72511827-9a42-4953-8401-c2a54bcb0ecf.png)
 
 
 
 
    - Scores by school spending (without Thomas High School 9th Graders)
![perschool_spending(withoutTHS9th)](https://user-images.githubusercontent.com/93004710/150576103-ddce217c-ea6f-4598-9dba-35aca5f1a997.png) 


    - Without Thomas High School 9th Graders, Thomas High School in the $630-$644 range percent passing math went from 67 to 73, percent passing reading went from 77 to 84, and percent overall passing went from 56 to 63. 

    - Scores by school size (with Thomas High School 9th Graders)
![schoolsize_withTHS](https://user-images.githubusercontent.com/93004710/150576871-ab5de6a4-189f-492d-977a-08b907a54f16.png)
 
    
    
    
    
    - Scores by school size (without Thomas High School 9th Graders)
![schooltsize_withoutTHS](https://user-images.githubusercontent.com/93004710/150576893-97de5d0e-0200-45d2-9260-a6cdbe1e538c.png)
  
    
    
    - Without Thomas High School 9th Graders, Thomas High School in the medium range percent passing math went from 88 to 94, percent passing math went from 91 to 97, and percent overall passing went from 85 to 91.
    - Scores by school type (with Thomas High School 9th Graders)
![schooltype_withTHS](https://user-images.githubusercontent.com/93004710/150577124-1a8c4b35-ed82-481a-b9cc-12e9400b79f5.png)
    
    
    
    
    - Scores by school type (without Thomas High School 9th Graders)
![schooltype_withoutTHS](https://user-images.githubusercontent.com/93004710/150577131-03440850-3255-4955-b5de-e0212d7311b1.png)

    - Without Thomas High School 9th Graders, Thomas High School in the charter school type percent passing math went from 90 to 94, percent passing reading went from 93 to 97, and the overall percent passing went from 87 to 90.

## Summary
* After the changes to the school district analysis after reading and math scores have been replaced for Thomas High Schools' 9th Graders with N/A changes in the overall student count were affected along with percent passing math, percent passing reading, and percent overall passing throughout the analysis resulting in changing the position of Thomas High School being a top performing school in the district.
