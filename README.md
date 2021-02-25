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


## Summary

* The dataset does not feature any missing or erroneous data values, and all features are of the correct data type.
* The strongest positive correlations with the target features are: Performance Rating, Monthly Rate, Num Companies Worked, Distance From Home.
* The strongest negative correlations with the target features are: Total Working Years, Job Level, Years In Current Role, and Monthly Income.
* The dataset is imbalanced with the majoriy of observations describing Currently Active Employees.
* Several features (ie columns) are redundant for our analysis, namely: EmployeeCount, EmployeeNumber, StandardHours, and Over18.

## Observations
* Single employees show the largest proportion of leavers, compared to Married and Divorced counterparts.
* About 10% of leavers left when they reach their 2-year anniversary at the company.
* Loyal employees with higher salaries and more responsbilities show lower proportion of leavers compared to their counterparts.
* People who live further away from their work show higher proportion of leavers compared to their counterparts.
* People who travel frequently show higher proportion of leavers compared to their counterparts.
* People who have to work overtime show higher proportion of leavers compared to their counterparts.
* Employee who work as Sales Representatives show a significant percentage of Leavers in the submitted dataset.
* Employees that have already worked at several companies previously (already "bounced" between workplaces) show higher proportion of leavers compared to their counterparts.


## Concluding Remarks
### Risk Category

As the company generates more data on its employees (on New Joiners and recent Leavers) the algorithm can be re-trained using the additional data and theoritically generate more accurate predictions to identify high-risk employees of leaving based on the probabilistic label assigned to each feature variable (i.e. employee) by the algorithm.

Employees can be assigning a "Risk Category" based on the predicted label such that:

* Low-risk for employees with label < 0.6
* Medium-risk for employees with label between 0.6 and 0.8
* High-risk for employees with label > 0.8

### Strategic Retention Plan
#### The stronger indicators of people leaving include:

* Monthly Income: people on higher wages are less likely to leave the company. Hence, efforts should be made to gather information on industry benchmarks in the current local market to determine if the company is providing competitive wages.
* Over Time: people who work overtime are more likelty to leave the company. Hence efforts must be taken to appropriately scope projects upfront with adequate support and manpower so as to reduce the use of overtime.
* YearsWithCurrManager: A large number of leavers leave 6 months after their Current Managers. By using Line Manager details for each employee, one can determine which Manager have experienced the largest numbers of employees resigning over the past year. Several metrics can be used here to determine whether action should be taken with a Line Manager:
*    number of employees under managers showing high turnover rates: this would indicate that the organisation's structure may need to be revisit to improve efficiency
*    number of years the Line Manager has been in a particular position: this may indicate that the employees may need management training or be assigned a mentor (ideally an Executive) in the organisation
*    patterns in the employees who have resigned: this may indicate recurring patterns in employees leaving in which case action may be taken accordingly.
* Age: Employees in relatively young age bracket 25-35 are more likely to leave. Hence, efforts should be made to clearly articulate the long-term vision of the company and young employees fit in that vision, as well as provide incentives in the form of clear paths to promotion for instance.
* DistanceFromHome: Employees who live further from home are more likely to leave the company. Hence, efforts should be made to provide support in the form of company transportation for clusters of employees leaving the same area, or in the form of Transportation Allowance. Initial screening of employees based on their home location is probably not recommended as it would be regarded as a form of discrimination as long as employees make it to work on time every day.
* TotalWorkingYears: The more experienced employees are less likely to leave. Employees who have between 5-8 years of experience should be identified as potentially having a higher-risk of leaving.
* YearsAtCompany: Loyal companies are less likely to leave. Employees who hit their two-year anniversary should be identified as potentially having a higher-risk of leaving.



A strategic "Retention Plan" should be drawn for each Risk Category group. In addition to the suggested steps for each feature listed above, face-to-face meetings between a HR representative and employees can be initiated for medium- and high-risk employees to discuss work conditions. Also, a meeting with those employee's Line Manager would allow to discuss the work environment within the team and whether steps can be taken to improve it.
