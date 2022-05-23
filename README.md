# School_District_Analysis

# Project Overview:

For This Analysis We'll be helping Maria who is the Chief Data Scientist for a city school district to analyze all standardize test data for analysis, reporting and presentation to provide insights about performance trends and patterns. These insights are used to make a decision at the school district level. Our task will be analyzing data on student funding and students’ standardized test scores. This analysis will be school board and superintendent in making decisions regarding the school budgets and priorities. 

# Resources:

-Software: Python 3.9.7, Anaconda 4.10.3, Jupyter Notebook 6.4.5 
-Resources: Data used for this project are insured of the Resources folder

# Results: 

The school district discovered that there might be a potential academic dishonesty by the ninth-grade students of Thomas High School. As a result, this analysis was complete twice. In the first trial, the full set of student data. In the second trial of this analysis, the ninth-grade students of Thomas High School had their scores omitted from the calculations. The entire ninth grade class of Thomas High School have had their scores replaced with NaN. The change of adding Nan to all grade 9 and Thomas High School math and reading scores did not have a large impact on the district analysis. 
- The overall passing percentage for Thomas High School fell to 65%
- The overall passing percentage for the entire district fell to 64.9%

-For reference, there are only 461 students in grade 9 at Thomas High School, and given the total student count is 39,170, the grade 9 students only make up 1.2% of the total student count

![Thomas_High_school](https://user-images.githubusercontent.com/101952961/168734397-7ff212c4-b1bb-4c90-a45f-1d9d0468adc1.PNG)

![Overall_Score_for_School_District](https://user-images.githubusercontent.com/101952961/168734071-414de7fb-81eb-411d-803b-e10ff4294ec6.PNG)

# Summary:
When reviewing the School Spending summary, this data change did not impact the spending ranges for either the average math scores or average reading scores. However, school types have an impact on performance. Charter schools generally performed better than District schools in this analysis. The top five schools with the highest overall passing percentages are all Charter schools, whereas the bottom five are all District Schools. Charter schools in this dataset were typically characterized as "Small" and "Medium" size schools. 
