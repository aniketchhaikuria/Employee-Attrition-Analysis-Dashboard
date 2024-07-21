# Power BI: Employee Attrition Analysis Dashboard

![image](https://github.com/user-attachments/assets/5c7c87e6-b911-464e-bec8-cf661a91c040)

## Project Overview
XYZ company, established a few years ago, has been experiencing a 15% attrition rate over the past couple of years. This high attrition rate is significantly affecting the company. To understand the reasons behind employee departures and to help reduce the attrition rate, XYZ company has sought the help of an HR analytics consultancy. As an HR analyst, you have built a Power BI dashboard to provide data-driven insights.

## Interact with Dashboard
[Power BI Dashboard Link](https://app.powerbi.com/view?r=eyJrIjoiMDNmMmRjYzUtOWU5Yy00OWQ0LWFhYjItZTkxMzgxOTBiZWJjIiwidCI6IjI3ZjE2MzIxLTMzNzctNGI2Mi1iNjBjLWU5ZGEyMzg2NTVhNyJ9)

## Goals
- Analyze the factors contributing to employee attrition.
- Provide actionable insights to help reduce the attrition rate.
- Create an interactive dashboard for easy exploration of the data.

## Tools and Technologies
- **Data Source:** Attrition data provided by Unified Mento.
- **Dataset Link:** [View Google Drive File](https://drive.google.com/file/d/1xZ98oGm8FDK8uTu8yqsVjc2PrfGt7B6z/view)
- **Tool:** Excel, Power BI
- **Language:** DAX for creating measures

## Dataset
The dataset contains the following columns:
### Dataset Columns
| Column Name              | Column Name                | Column Name                 |
|--------------------------|----------------------------|-----------------------------|
| Employee ID              | Education                  | Num Companies Worked        |
| Age                      | Education Field            | Over 18                     |
| Attrition                | Employee Count             | Percent Salary Hike         |
| Business Travel          | Gender                     | Standard Hours              |
| Department               | Job Level                  | Stock Option Level          |
| Distance From Home       | Job Role                   | Total Working Years         |
| Monthly Income           | Marital Status             | Training Times Last Year    |
| Years At Company         | Years Since Last Promotion | Years With Curr Manager     |
| Environment Satisfaction | Job Satisfaction           | Work Life Balance           |
| Job Involvement          | Performance Rating         |                             |

# Key Insights
## Employee Attrition Analysis

### 1. Attrition by Years at Company
The analysis of employee attrition by years at the company shows the following attrition percentages across different tenure groups:

| Years at Company | Attrition Count | Total Count | Attrition Percentage |
|------------------|------------------|-------------|-----------------------|
| 1-2 years        | 264              | 1272        | 20.75%                |
| 2-4 years        | 373              | 1792        | 20.79%                |
| 4-6 years        | 312              | 1419        | 22.02%                |
| 6-10 years       | 256              | 1452        | 17.64%                |
| 10+ years        | 242              | 1485        | 16.29%                |

- **1-2 Years**: Highest attrition rate at 20.75%, indicating significant turnover early in employment.
- **2-4 Years**: Slightly lower attrition rate at 20.79%, showing that turnover remains high but stabilizes somewhat.
- **4-6 Years**: Highest attrition rate at 22.02%, suggesting peak turnover during this period.
- **6-10 Years**: Attrition rate drops to 17.64%, reflecting decreased turnover as employees stay longer.
- **More than 10 Years**: Lowest attrition rate at 16.29%, indicating greater stability and lower turnover among long-term employees.

### 2. Attrition by Job Role

| Job Role                  | Attrition Count | Total Count | Attrition Percentage |
|---------------------------|------------------|-------------|-----------------------|
| Research Director         | 57               | 240         | 23.75%                |
| Research Scientist        | 159              | 876         | 18.15%                |
| Sales Executive           | 165              | 978         | 16.87%                |
| Laboratory Technician     | 126              | 777         | 16.22%                |
| Healthcare Representative | 57               | 393         | 14.50%                |
| Sales Representative      | 36               | 249         | 14.46%                |
| Manager                   | 42               | 306         | 13.73%                |
| Human Resources           | 21               | 156         | 13.46%                |
| Manufacturing Director    | 48               | 435         | 11.03%                |

- **Research Director** has the highest attrition rate at 23.75%, indicating a significant portion of employees in this role have left the company.
- **Research Scientist** and **Sales Executive** also show relatively high attrition rates, at 18.15% and 16.87% respectively.
- The role of **Manufacturing Director** has the lowest attrition rate at 11.03%.

### 3. Attrition by Education Field

| Education Field | Attrition Count | Total Count | Attrition Percentage |
|-----------------|------------------|-------------|-----------------------|
| Human Resources | 33               | 81          | 40.74%                |
| Life Sciences   | 303              | 1818        | 16.67%                |
| Medical         | 225              | 1392        | 16.16%                |
| Marketing       | 75               | 477         | 15.72%                |
| Other           | 30               | 246         | 12.20%                |
| Technical Degree| 45               | 396         | 11.36%                |

- **Human Resources** has the highest attrition percentage at 40.74%.
- **Life Sciences** and **Medical** fields also show notable attrition rates at 16.67% and 16.16% respectively.

### 4. Attrition by Age Group

| Age Group | Attrition Count | Total Count | Attrition Percentage |
|-----------------|------------------|-------------|-----------------------|
| 55 and above    | 49               | 201         | 24.38%                |
| 45-54           | 102              | 726         | 14.05%                |
| 35-44           | 258              | 1479        | 17.44%                |
| 25-34           | 248              | 1648        | 15.05%                |
| Under 25        | 40               | 288         | 13.89%                |

- The highest attrition rate is observed in the **"55 and above"** age group, with an attrition percentage of 24.38%.
- The next highest attrition rate is in the **"blank"** age group with 20.59%.
- The **"35-44"** age group also has a significant attrition rate of 17.44%.

### 5. Attrition by Salary Category

| Salary Category | Attrition Count | Total Count | Attrition Percentage |
|-----------------|------------------|-------------|-----------------------|
| 15k-30k         | 198              | 1128        | 17.55%                |
| 30k-60k         | 258              | 1557        | 16.57%                |
| 10k-15k         | 9                | 57          | 15.79%                |
| 60k+            | 246              | 1668        | 14.75%                |

- **15k-30k** salary category has the highest attrition percentage at 17.55%.
- The **30k-60k** salary category has the next highest attrition rate at 16.57%.
- The **10k-15k** salary category also has a notable attrition rate of 15.79%.
- The **60k+** salary category has the lowest attrition rate at 14.75%.

### 6. Attrition by Department

| Department           | Attrition Count | Total Count | Attrition Percentage |
|----------------------|------------------|-------------|-----------------------|
| Human Resources      | 57               | 189         | 30.16%                |
| Research & Development | 453            | 2883        | 15.71%                |
| Sales                | 201              | 1338        | 15.02%                |

- **Human Resources** has the highest attrition rate at 30.16%, indicating a significantly higher turnover compared to other departments.
- **Research & Development** and **Sales** departments have relatively lower attrition rates at 15.71% and 15.02%, respectively.

### 7. Analysis of Attrition by Gender

| Gender | Attrition Count | Total Count | Attrition Percentage |
|--------|------------------|-------------|-----------------------|
| Male   | 441              | 2646        | 16.67%                |
| Female | 270              | 1764        | 15.31%                |

- The attrition rate among **male** employees is 16.67%, compared to 15.31% for **female** employees.
- Despite the slightly lower attrition percentage among female employees, the overall count of attrition is higher in the male category.

# Conclusion
The Employee Attrition Analysis Dashboard provides a comprehensive view of the factors contributing to employee attrition at XYZ company. By addressing the identified issues, the company can take data-driven actions to reduce the attrition rate and improve employee retention.
