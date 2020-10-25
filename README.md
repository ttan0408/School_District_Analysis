# School_District_Analysis


## Project Overview
School District want to understand the inside performance of students from student funding and student standadize test score data. We helped them using Jupyter Notebook to analyze these data set. The key metrics we are focusing on are : 
 _ Percentage passing math score
 _ Percentage passing reading score
 _ Percentage overall passing score
 _ Speding range per student

## Results
There are 15 schools in district from 9th to 12th grade. Total analyzed data we have to use are 39170. Our task was to QC the data before going to details analysis
At the begining, the Thomas High School has very low spassing score with the table summary below :

https://github.com/ttan0408/School_District_Analysis/blob/main/Challenge_Before_Replace_9th_grade.PNG

We have to go back and look at the data again and found out that at 9th grade appear to have been altered. We remove the 9th grade data so that it will not affected the over score for Thomas High School. After we re-calculated the new percentage score, Thomas High School become top 5 school performance 

https://github.com/ttan0408/School_District_Analysis/blob/main/Challenge_After_Replace_9th_grade.PNG

Top Five School with Thomas High School as 2nd

https://github.com/ttan0408/School_District_Analysis/blob/main/Top_Five_School.PNG

Before remove 9th grade scores, Thomas High School has low performance passing with around 60 plus percentage passing in the spending size of $630-$644 . This may mis leading to the Board which indicates even high speding size but results in lower performance. 

After replacing 9th grade, the Score School Spending for Thomas is  

https://github.com/ttan0408/School_District_Analysis/blob/main/Challenge_After_Replace_9th_grade_Spending_Range.PNG

In additional , score by school size result is :

https://github.com/ttan0408/School_District_Analysis/blob/main/Challenge_After_Replace_9th_grade_School_Size.PNG

Score by District

https://github.com/ttan0408/School_District_Analysis/blob/main/Challenge_After_Replace_9th_grade_School_Score_by_District.PNG

The Jupyter Notebook Coding :









