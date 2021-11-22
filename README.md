# School_District_Analysis

## Overview of the School District Analysis

* This analysis is for assisting City School District in deciding on school budget allocation and other priorities.
* By using the Math and Reading score of the students, we analyze, report and present the data to provide performance, trends, and patterns.

As the School Board has upheld the Math and the Reading data for Thomas High School 9th Grade, So we will be comparing data with and without math and reading scores for Thomas High School 9th Grade to check how the data has been affected because of the change.

Below is the code written to change the Math and Reading score for Thomas High School 9th Grade to NaN

* student_data_df.loc[(student_data_df["school_name"] == "Thomas High School") & (student_data_df["grade"] == "9th") , 'math_score'] = np.nan
* student_data_df.loc[(student_data_df["school_name"] == "Thomas High School") & (student_data_df["grade"] == "9th") ,'reading_score'] = np.nan

## Results

## District Summary :

District Summary 
![before1](https://user-images.githubusercontent.com/92698873/142833208-05f919ad-c901-43ce-94ab-6bf4cc9d33ba.png)

District Summary after the changes ( Math and reading score for Thomas High School 9th Grade is changed to NaN)
![after2](https://user-images.githubusercontent.com/92698873/142833223-0f870fb5-003f-4b2f-8e41-2907ca2ad793.png)

From the above result, we conclude there is no major change in data, 99% match in both the data sets - % math, %reading, and %overall score.

## School Summary :

* There seems to be a major difference in the %scores in School Summary. 
* Around 30% increase in the math, reading and overall scores after the Math and reading score for Thomas High School 9th Grade is changed to NaN.

School Summary :
![before2](https://user-images.githubusercontent.com/92698873/142837151-732ca420-7f78-4641-9082-0ce22b42f177.png)

School Summary after the changes ( Math and reading score for Thomas High School 9th Grade is changed to NaN)
![after22](https://user-images.githubusercontent.com/92698873/142837143-2a145a6a-b84e-43ce-945b-5f6f5df93e8e.png)

## After effects of changes in data 

## Thomas High School’s performance 

* Before replacing the data - Thomas High School was in 8th position with 65.07 % of the overall passing score.
* After replacing the data - Thomas High School is in the 2nd position with 90.63 % of the overall passing score.

From the above analysis, the performance of Thomas High School seems to be increased significantly, so we need to notify the school District as this big difference in data cannot be ignored. 

## Math and reading scores by grade
From the below details, 9th Grade of Thomas High school data is unavailable, so it is difficult to calculate scores for 9th grade and unable to perform any analysis

Reading Scores by Grade :

![heading](https://user-images.githubusercontent.com/92698873/142846389-52c9f25f-a4c9-4dc0-b397-de365fd9a30c.png)

![3 dhwd](https://user-images.githubusercontent.com/92698873/142846448-5459d020-c593-4e65-ac97-b7da2b63bf58.png)

Math Scores by Grades

![heading](https://user-images.githubusercontent.com/92698873/142846354-9214bc7e-9dd8-4115-be8d-776d939832a9.png)

![3after](https://user-images.githubusercontent.com/92698873/142844605-dad05de8-8ff3-4a40-a68d-646c3bb9ef1a.png)

## Scores by school spending

* From the below analysis, spending per student data has been changed after the changes in the reading and Math scores.
* Data in bins - $585-629 and $630-644 has seen a small increase in average and percentage scores. 

![4head](https://user-images.githubusercontent.com/92698873/142847833-3fb98863-5d98-45f7-b2b6-57a4552214f7.png)
![4ths](https://user-images.githubusercontent.com/92698873/142847845-c4c4c58d-2635-4cd2-b915-329380b4bb9a.png)

Spending Summary :
![5before](https://user-images.githubusercontent.com/92698873/142848401-706c3fbe-984b-4b90-8f16-690167a1ad62.png)
Spending Summary after the changes :
![5after](https://user-images.githubusercontent.com/92698873/142848405-9f8f216f-8195-4276-bf08-9aba2e988931.png)

## Scores by school size

As the total number of student remains same in both the data sets, so the average and percentage by school size remains the same , before and after the math and reading score changes.  

![6yh](https://user-images.githubusercontent.com/92698873/142849787-0edf76ab-7e13-4cb8-8388-c0aabff3d81b.png)

## Scores by school type
Changes in the 9th Grade Thomas High school math and reading didnt affect the Averages and percentages by type of school - District and Charter , values remains in both the data sets

![7](https://user-images.githubusercontent.com/92698873/142850700-53b26874-7a2a-4298-ab04-548aaa70e3c1.png)

##Summary:
Below are the changes accounted after reading and math scores for 9th grade at Thomas High school has been made.

* Average math and Reading score for the school and also grade wise data will be likely be differnt
* Percentage of Math and reading score will be affected.
* Overall Pass percentage is also changed. The data has been increased by 25% - thats a huge difference in data.
* Performace cannot be determined for Thomas High School, so all other school performace rating is affected.


