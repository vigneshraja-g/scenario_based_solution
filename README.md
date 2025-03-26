Scenario Based Learning 
A company works with number of employees, all the works are dependents on the employees. Even 
if one of the employees resign the job immediately then assigned work will be not finished at the 
time, so delivery of the project to the clients will be delayed. Company planned to make solution for 
this, they want to know which employee may resign next. If they know previously, they can arrange 
alternative to avoid such problem. As an AI Engineer you must give Solution to this. 
A) How will you achieve this in AI? 
B) Find out the 3 -Stage of Problem Identification 
C) Name the project 
D) Create the dummy Dataset.

A) To predict which employee may resign next, we can use Machine Learning (ML) and Predictive Analytics. (Prediction -> resignation)

B) 3 -Stage of Problem Identification
   Stage 1 : Machine Learning
   Stage 2 : Supervised
   Stage 3 : Classification

C) ResignPred

D) 
EmployeeID	Age	Tenure(Yrs)	Salary	JobSatisfaction (1-10)	WorkHours/Week	PromotionLastYear	Attrition (Yes/No)
101	        32	  4	        65000	    8	                      45	              No	              No
102	        28	  2	        48000	    5	                      50	              No	              Yes
103	        45	 10	        90000	    7	                      40	              Yes	              No
104	        36	  5	        70000	    4	                      55	              No	              Yes
