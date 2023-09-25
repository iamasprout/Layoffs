# Layoffs Analysis
![layoffs charts](https://github.com/iamasprout/Layoffs/assets/114030254/4c83ffd5-067e-4a14-b0b6-4527e384e0b8)
Layoffs are a difficult reality in today's business world, and they can have a significant impact on both the affected employees and the organization as a whole. 
Conducting a layoff analysis can help organizations better understand the causes and effects of layoffs, as well as identify opportunities for improvement and mitigation.
# Problem Statement
In this documentation, we will explore the key components of a layoff analysis, including the reasons for conducting one, the data sources and methods used, and 
the types of insights and recommendations that can be derived from the analysis. 
By understanding the importance of layoff analysis and how to conduct one effectively, organizations can make more informed decisions about their workforce and minimize the 
negative impact of layoffs.
## Skill Demostrated
Proficiency in Excel
Data analysis
Problem-solving
Attention to detail
Communication
## Task
* Analysis of Sales by Order
* Analysed the sales by gender
* Display the top 5 location with the highest sales
* The Channel with more revenue
* Sales by age
## Data Sourcing/Refrences:
 https://kaggle.com

---------------------
# Data Transformation
![Dataset](https://github.com/iamasprout/Florish-Stores/assets/114030254/f3f32701-721c-44c1-8767-f222873109cb)

Since the Data is clean enough for visualization i dived directly to deriving useful dependants

## derived Formula
Since the variable in age is much i decided to group them to Young, Senior and Adult
```
Agegroup=IF(E2>=50,"Senior",IF(E2>=30,"Adult","Young"))
```
![image](https://github.com/iamasprout/Florish-Stores/assets/114030254/bad62cf8-7093-454c-8cb9-0f38da93f17a)

extracting the first three letters from the month
``` 
Month=TEXT(G2,"mmm")
```
![image](https://github.com/iamasprout/Florish-Stores/assets/114030254/8a01fe70-d7cc-4bb3-9b34-2be1133b45f2)

## Data Visualization
According to what was stated earlier as the tasks we decided to crerte a pivot table 

 Order vs Sales
![image](https://github.com/iamasprout/Florish-Stores/assets/114030254/428ae503-a701-482d-93b9-63743e8f7947)


Sales by Gender

![image](https://github.com/iamasprout/Florish-Stores/assets/114030254/5045e600-1110-4792-b4fb-2d26fe349df7)

 Count by Order Status
 ![image](https://github.com/iamasprout/Florish-Stores/assets/114030254/5e2433b5-edaa-46e3-ae4c-c96763a18559)


After all has been done we need to have all present our findings in a better way

![Dashboard](https://github.com/iamasprout/Florish-Stores/assets/114030254/65776a7b-8a98-40aa-8b20-3e2f66d97ea0)

## Recommendation

Based on the findings of a layoff analysis, 
organizations can take several steps to mitigate the negative impact of layoffs. 
Some possible recommendations could include:

Providing support for affected employees, such as career counseling, 
job placement services, or financial assistance.
Communicating openly and transparently with employees about the reasons for the layoffs 
and the steps being taken to address them.
Reevaluating the organization's business strategy and operations to identify opportunities 
for cost savings and efficiency improvements that could reduce the need for future layoffs.
Developing a contingency plan for future workforce reductions, including clear criteria for 
selecting employees to be laid off and strategies for minimizing the impact on remaining 
employees.




