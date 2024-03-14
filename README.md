## Employee Performance Analysis - INX Future Inc

-----------
## Analysis

### Univariate Analysis of categorical data:

```
1) Ratio of Male compared to Female is more.
2) Most of the people are married.
3) Employee of this company prefer travel rarely.
4) Mostly people have medium educational level which is from 3 to 5.
5) Most of the people are satisfied in job environment.
6) Mostly people are less experienced in this company.
7) Few people are prefer to do overtime.
8) Most of the people prefer to stay in this company.
9) High number of people have Medical and Life Science Educational Background.
10) Most people work in Sale, Development and R&D department.
11) Most of the people are working as developer and sales person.
```

### Univariate Analysis of Numerical datas:

```
1) Most of the Employees of this company living nearby.
2) Most of the employee have Last year salary hike was 14%.
3) Average work experience in this company upto 6 years.
```

### Bivariate Analysis of categorical datas:

```
1) Male & female have equal performance.
2) Single people performed well as compared to married and divorced people.
3) Development & Data Science have high performance as compared to other fields.
4) Finance Manager have low performance whereas business Analyst performed good.
5) Travel Rarely have low performance where as non-travellers performd well.
6) People who did overtime, performed well.
7) People who managed work life balance very well, those people performed well.
8) people who performed well, they were not prone to leave company.
```

### Bivariate Analysis of Numerical datas:

```
1) People who have long distance from company performed low.
2) People who have high salary hike performed well.
3) People who performed well, got promoted at early stage.
```

### Why use Particular Machine Learning Models:

```
1) Decision trees are easy to interpret and visualize, and give good transparency and understanding of the model.
2) Random Forest is an ensemble method that builds multiple decision trees and combines their predictions.
   This helps improve the model's generalization and reduces overfitting.
3) Gradient Boosting builds trees sequentially, with each tree correcting the errors of the previous ones.
   This sequential learning process often leads to high accuracy.
```

-------------
## Project Summary

The Data science project which is given here is an analysis of employee performance form INX Furture Inc. The project goal is to find the performance rating of the employees from each feature of their data such as total work experience, gender, department, current role, etc. The Goal and Insights of the project as follows:

```
*   Department wise performances
*   Top 3 Important Factors affecting employee performance
*   A trained model which can predict the employee performance based on factors as inputs.
*   Recommendations to improve the employee performance based on insights from analysis.
```

### Department wise performances
Employees of Development and Data Science Department have high Performance Rating compare to others.

![image](https://github.com/anjanikmr39/Employee-Performance-Report/assets/67219753/3ee2d3f6-75a4-475c-b43b-04decad5c840)


### Top 3 Important Factors affecting employee performance
We Got three Most Important feature from Extra Tree Classifier are
 
* EmpEnvironmentSatisfaction
* EmpLastSalaryHikePercent
* YearsSinceLastPromotion

![image](https://github.com/anjanikmr39/Employee-Performance-Report/assets/67219753/d1f21c99-1ffc-4c33-9662-47853457f5db)


### A trained model which can predict the employee performance based on factors as inputs.
1.   Decision Tree
2.   Random Forest
3.   Gradient Boosting

```
+-------------------+-----------------------------+----------------------------+
| Models            |   Before Hyper Parameter(%) | After Hyper Parameter(%)   |
+===================+=============================+============================+
| Decision Tree     |                       90    | 86.25                      |
+-------------------+-----------------------------+----------------------------+
| Random Forest     |                       93.33 | 93.33                      |
+-------------------+-----------------------------+----------------------------+
| Gradient Boosting |                       92.08 | NA                         |
+-------------------+-----------------------------+----------------------------+

```

For Hiring Employees, Company should use Random Forest since it have high accuracy compared to other models.

![image](https://github.com/anjanikmr39/Employee-Performance-Report/assets/67219753/5008fdcb-2eb1-45e7-815c-6119a9b39410)

--------
### Recommendations to improve the employee performance based on insights from analysis.

1. Better Employee's work-life balance improve the performance rating.
2. The promotion will help the employees to achieve more responsible and leadership qualities.
3. Improve Work Environment for Better Performance of Employees. 
4. Give good Salary Hike to Deserving Candidates for Better Performance.
5. The experience years in current role need to be revised while offering the employment to the new employees.


---------
