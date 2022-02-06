# Pewlett-Hackard-Analysis

# Written report on the employee database analysis


## 1.	Overview of the analysis: Explain the purpose of this analysis.
The purpose of this analysis was to find out who where the employees that were close to retirement. What departments they work under. And to see if they are eligible to participate in a mentorship program that will help the replacement employees take over those roles.
## 2.	Results: Provide a bulleted list with four major points from the two analysis deliverables. Use images as support where needed.
o	From the data provided, we see that there are going be a significant number of employees that will be retiring soon. 
o	As shows on Retiring Titles, we see that there are 7 tittles ranging from senior to junior rolls that have employees retiring soon.
o	Initially when we pulled the retirement data into the Retirement Titles we saw there were 133,777 rows of possible retirees. 

![Retirement Title example](https://user-images.githubusercontent.com/92958939/152667248-ec774bea-b51c-4304-b41a-150c4f750fb4.png)

After noticing that most of them showed the same employees multiple times due to past rolls they had, we filtered the data to show the most recent roll for each employee under Unique Titles. We saw there were 72,459 rows instead. 

![Unique Titles example](https://user-images.githubusercontent.com/92958939/152667253-a14148c6-c0fb-4c60-bb43-16c72513d649.png)


o	This shows that the majority of the employees retiring have been with the company for a long time that they moved to different branches of the company or were able to be promoted to different rolls. 
## 3.	Summary: Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
**o	How many roles will need to be filled as the "silver tsunami" begins to make an impact?**

•	If we look at the data from Retiring Titles, we see that the majority of the future retirees are coming from senior positions. Senior Engineer have 25,916 employees retiring, and Senior Staff have 24,926 employees retiring.

![retiring_titles](https://user-images.githubusercontent.com/92958939/152667312-bc61b1d4-e810-4183-807e-6d1a163e61b8.png)


**o	Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?**

The only department that is low in retirement-ready employees is Manager. That department only has two employees retiring soon. But with that role, there will be more people that will apply to take over that position that it will be easy to fill those two role. 
There is enough retirement-ready employees in most of the departments. The problem we see happening is that there is not enough employees to take over all the positions that will be retiring soon. 
In order to fill those roles, we will have to recruit employees from the junior position. For example, Engineer and Staff titles, to participate in the mentorship program. But even if we add the junior positions for the engineer department, 1,090 for Assistant Engineer and 9,285 for engineer that only makes 10,375 and we have 25,916 roles to fill. We also have to consider that not all the junior employees will either be ready or recommended for the senior position. 
If we count the amount of total employees curently in the company we get 300,024. That is a lot of employees, but like we stated, not all will be considered for the rolles that need to be filled once those employees retire.

![Employees count](https://user-images.githubusercontent.com/92958939/152667532-5245c031-92f8-4db3-ab54-c605ca695590.png)

We also have to consider that not all retirement-ready employees will want to participate in the mentorship program. 
We suggest for management to take a look at all the rolls and determine if all of them are needed to be filled. Some rolls might be able to be combined with similar positions. But this will take time to determine what rolls can be combined so the quality of the work does not go down due to the new employee being overworked in trying to handle too much. If this is an option, this will make the process of filling all those positions a bit more manageable. 
Due to the high amount of retirees coming, we would suggest outsourcing the junior positions after those employees take over the senior roles. But we also suggest to promote as much as possible within the company before outsourcing the other necessary positions.  
