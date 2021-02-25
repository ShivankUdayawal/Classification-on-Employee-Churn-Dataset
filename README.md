# Classification-on-Employee-Churn-Dataset
Performing classification Technique on Employee Churn Dataset

## Problem Definition
### Project Overview

* Employee turn-over (also known as "employee churn") is a costly problem for companies. The true cost of replacing an employee can often be quite large. A study by the Center for American Progress found that companies typically pay about one-fifth of an employee’s salary to replace that employee, and the cost can significantly increase if executives or highest-paid employees are to be replaced.
* In other words, the cost of replacing employees for most employers remains significant. This is due to the amount of time spent to interview and find a replacement, sign-on bonuses, and the loss of productivity for several months while the new employee gets accustomed to the new role.


## Problem Statement

* Understanding why and when employees are most likely to leave can lead to actions to improve employee retention as well as possibly planning new hiring in advance. I will be usign a step-by-step systematic approach using a method that could be used for a variety of ML problems. This project would fall under what is commonly known as "HR Anlytics", "People Analytics".

In this study, we will attempt to solve the following problem statement is:

* What is the likelihood of an active employee leaving the company?
* What are the key indicators of an employee leaving the company?
* What policies or strategies can be adopted based on the results to improve employee retention?


Given that we have data on former employees, this is a standard supervised classification problem where the label is a binary variable, 0 (active employee), 1 (former employee). In this study, our target variable Y is the probability of an employee leaving the company.

In this case study, a HR dataset was sourced from IBM HR Analytics Employee Attrition & Performance which contains employee data for 1,470 employees with various information about the employees. I will use this dataset to predict when employees are going to quit by understanding the main drivers of employee churn.

#### Data has various data points on our employees, but you are most interested in whether they’re still with my company or whether they’ve gone to work somewhere else. And you want to understand how this relates to workforce attrition.

* Education : 1 = 'Below College' , 2 = 'College' , 3 = 'Bachelor', 4 = 'Master' , 5 = 'Doctor'
* Environment Satisfaction : 1 = 'Low', 2 = 'Medium', 3 = 'High', 4 = 'Very High'
* Job Involvement : 1 = 'Low' , 2 = 'Medium', 3 = 'High' , 4 = 'Very High'
* Job Satisfaction : 1 = 'Low' , 2 = 'Medium' , 3 = 'High' , 4 = 'Very High'
* Performance Rating : 1 = 'Low' , 2 = 'Good' , 3 = 'Excellent' , 4 = 'Outstanding'
* Relationship Satisfaction : 1 = 'Low' , 2 = 'Medium' , 3 = 'High' , 4 = 'Very High'
* WorkLife Balance : 1 = 'Bad' , 2 = 'Good' , 3 = 'Better' , 4 = 'Best'

## Data Visualization 

![](https://github.com/ShivankUdayawal/Classification-on-Employee-Churn-Dataset/blob/main/Data%20Visualizing/dist.jpg)

![](https://github.com/ShivankUdayawal/Classification-on-Employee-Churn-Dataset/blob/main/Data%20Visualizing/Age.jpg)

![](https://github.com/ShivankUdayawal/Classification-on-Employee-Churn-Dataset/blob/main/Data%20Visualizing/Age1.jpg)

![](https://github.com/ShivankUdayawal/Classification-on-Employee-Churn-Dataset/blob/main/Data%20Visualizing/gender.jpg)

![](https://github.com/ShivankUdayawal/Classification-on-Employee-Churn-Dataset/blob/main/Data%20Visualizing/maritalstatus.jpg)

![](https://github.com/ShivankUdayawal/Classification-on-Employee-Churn-Dataset/blob/main/Data%20Visualizing/jobrole.jpg)

![](https://github.com/ShivankUdayawal/Classification-on-Employee-Churn-Dataset/blob/main/Data%20Visualizing/yearatcompany.jpg)

![](https://github.com/ShivankUdayawal/Classification-on-Employee-Churn-Dataset/blob/main/Data%20Visualizing/Department.jpg)

![](https://github.com/ShivankUdayawal/Classification-on-Employee-Churn-Dataset/blob/main/Data%20Visualizing/departmentwithattrition.jpg)

![](https://github.com/ShivankUdayawal/Classification-on-Employee-Churn-Dataset/blob/main/Data%20Visualizing/ducationfield.jpg)

![](https://github.com/ShivankUdayawal/Classification-on-Employee-Churn-Dataset/blob/main/Data%20Visualizing/educationfieldwithattrition.jpg)

![](https://github.com/ShivankUdayawal/Classification-on-Employee-Churn-Dataset/blob/main/Data%20Visualizing/education.jpg)

![](https://github.com/ShivankUdayawal/Classification-on-Employee-Churn-Dataset/blob/main/Data%20Visualizing/ducationwithattrition.jpg)

![](https://github.com/ShivankUdayawal/Classification-on-Employee-Churn-Dataset/blob/main/Data%20Visualizing/monthlyincomewithdailyrate.jpg)

![](https://github.com/ShivankUdayawal/Classification-on-Employee-Churn-Dataset/blob/main/Data%20Visualizing/correlation.jpg)

![](https://github.com/ShivankUdayawal/Classification-on-Employee-Churn-Dataset/blob/main/Data%20Visualizing/attrition.jpg)

![](https://github.com/ShivankUdayawal/Classification-on-Employee-Churn-Dataset/blob/main/Data%20Visualizing/decisiontreewithentropy.jpg)


![](https://github.com/ShivankUdayawal/Classification-on-Employee-Churn-Dataset/blob/main/Data%20Visualizing/decisiontreewithgini.jpg)


![](https://github.com/ShivankUdayawal/Classification-on-Employee-Churn-Dataset/blob/main/Data%20Visualizing/Roc.jpg)

![](https://github.com/ShivankUdayawal/Classification-on-Employee-Churn-Dataset/blob/main/Data%20Visualizing/features.jpg)


