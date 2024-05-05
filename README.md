# CollegeRecords-SQLProject
## Introduction
Once a student is passed out from a Institute or College, he/she is known as Alumni of the Institute. Alumni’s career growth plays important role in Institute’s ranking and other networking activities. In this project, career choices of alumni of two Universities will be analyzed with respect to their passing year as well as the course they completed. 
## Dataset: Six .csv file (Alumni record of College A and College B) Higher Studies, Self Employed and Service/Job record 
College_A_HS ~ Higher Studies Record of College A
College_A_SE ~ Self Employed Record of College A
College_A_SJ ~ Service/Job Record of College A
College_B_HS ~ Higher Studies Record of College B
College_B_SE ~ Higher Studies Record of College B
College_B_SJ ~ Higher Studies Record of College B
## Tasks to be performed
Create new schema as alumni
Import all .csv files into MySQL
Perform data cleaning on table College_A_HS and store cleaned data in view College_A_HS_V, Remove null values. 
Perform data cleaning on table College_A_SE and store cleaned data in view College_A_SE_V, Remove null values.
Perform data cleaning on table College_A_SJ and store cleaned data in view College_A_SJ_V, Remove null values.
Perform data cleaning on table College_B_HS and store cleaned data in view College_B_HS_V, Remove null values.
Perform data cleaning on table College_B_SE and store cleaned data in view College_B_SE_V, Remove null values.
Perform data cleaning on table College_B_SJ and store cleaned data in view College_B_SJ_V, Remove null values.
Make procedure to use string function/s for converting record of Name, FatherName, MotherName into lower case for views (College_A_HS_V, College_A_SE_V, College_A_SJ_V, College_B_HS_V, College_B_SE_V, College_B_SJ_V) 
Write a query to create procedure get_name_collegeA using the cursor to fetch names of all students from college A.
 Write a query to create procedure get_name_collegeB using the cursor to fetch names of all students from college B.
Calculate the percentage of career choice of College A and College B Alumni
-- (w.r.t Higher Studies, Self Employed and Service/Job)
Note: Approximate percentages are considered for career choices.
Contact Information
For inquiries or support regarding this project, please contact Arsh Zehra at zehrarsh@gmail.com.

