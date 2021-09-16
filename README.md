# DS5220-Employee-TurnOver-Prediction

**Overview**

According to LinkedIn, the average yearly employee turnover rate around the world is 10.9 percent. Employee turnover should be kept to a minimum of 10%, however most companies' turnover rates are between 12% and 20%. Because of the nature of the work, several industries have greater staff turnover rates. The total percentage of employees that leave an organization and are replaced by new employees is referred to as employee turnover. It is quite expensive for businesses, with costs such as separation, vacancy, recruitment, training, and replacement. Organizations spend an average of four weeks to three months training new staff. We worked on a simulated HR data from Kaggle to build a classifier that helps us predict what kind of employees will be more likely to leave given some attributes. Such classifier would help an organization predict employee turnover and be pro-active in helping to solve such costly matter. We’ll restrict ourselves to use the most common classifiers: Random Forest, Gradient Boosting Trees,K-Nearest Neighbors etc. This predictive study is used by a company to determine how many employees they will require if potential employees quit. This predictive research can also be used to improve the environment for employees by identifying the root causes of high turnover.

**Dataset Description**

The data has 15000 samples. We have a total of 10 columns,
with the 9 input and 1 output feature.

Input Features:
1. last_evaluationTime: Time since last performance evaluation (in years).
2. number_project: Number of projects completed while at
work.
3. average_montly_hours: Average monthly hours at workplace.
4. time_spend_company: Number of years spent in the company.
5. Work_accident: Whether the employee had a workplace
accident.
6. promotion_last_5years: Whether the employee was promoted in the last five years.
7. Department: Department the employee works for.
8. salary: Relative level of salary {low, medium, high}.

Output Feature:
1. left: Whether the employee left the workplace or not
{0,1}.

**Conclusion**

I have done data cleaning and feature engineering. Then I have implemented some classification algorithms and the best f1-score is given by random forest algorithm. The top 5 important features to be focused by the organizations are:

1.Satisfaction_level.

2.time_spend_company.

3.average_monthly_hours.

4.number_project.

5.last_evaluation.
