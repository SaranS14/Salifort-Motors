# <p style = "text-align: center;"> **Salifort Motors employee retention analysis** </p>

Salifort Motor's HR department contacted their Data analyst team so that they can get some assistance in regards to figuring out why employees are leaving the company. The HR department collected data from several employees however, they are unsure what to do with the data and are hoping the data analyst team can study the data. Their main concern is: **Why are employees leaving Salifort Motors?**. 

The HR department is hoping that the data analyst team can identify the factors into why employees are leaving so that they can make the appropriate changes. This is due to the fact that it is expensive and time-consuming to find, interview and hire new employees.

We are going to create a binomial logistic model that will predict whether or not an employee will leave the company. If we can predict whether or not an employee is likely to leave, we may look into the factors of why they left and make adjustments accordingly. We want to make sure the Salifort's HR team understands why employees are leaving the company so they can implement changes within the company to retain these employees. 

Below is a table of the data with the listed variables and their descriptions. 

##### **Dataset**
| Variable      | Description |
| ----------- | ----------- |
| satisfaction_level      | A score determining employee's satisfaction level [0-1] |
| last_evaluation   | A score of employee's last performance review [0-1] |
| number_project | Number of projects an employee contributed to |
| average_monthly_hours | Average number of hours an employee worked per month |
| time_spend_company | Number of years employee has been with the company | 
| Work_accident | Whether or not an employee experienced a work-related accident |
| left | Whether or not an employee left the company |
| promotion_last_5years | Whether or not an employee received a promotion within the last 5 years |
| Department | The department the employee is under | 
| salary | Whether or not the employee received a low, medium or high salary (U.S. Dollars) |

( The project is centered around EDA (Exploratory Data Analysis) and binomial logistic regression. I made sure to clean the data set and as well as to check variable outliers and distributions for each variable before I 
constructed any data visualizations or binomial logistic regression models(Logistic regression assumptions were also checked as well).)
