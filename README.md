# Local Government Workforce Efficiency & Performance Analysis

## Project Overview
Analysis of workforce efficiency and performance metrics across multiple local government departments, examining the impact of employment duration and attendance on response times. Includes statistical insights and data visualizations to support strategic workforce management.

## Dataset Description
The dataset contains information on **366 staff members** across various local government departments with the following fields:

| Field | Description | Type |
|-------|-------------|------|
| Department | The department where the staff member works (Environment, Education, Housing, Welfare, Heritage) | Categorical |
| Length of Employment | How long the staff member has been employed (Less than 1 year, 1 year, 2 years, 3-5 years, 6-10 years, More than 10 years) | Ordinal |
| Sick Days | Number of sick days taken over the last two years (range: 0-130) | Continuous |
| Response Target | Percentage of times the staff member responded to inquiries within the 48-hour target (range: 62.8%-81.4%) | Continuous |

## Key Findings

### Departmental Distribution
- **Environment**: 127 staff (34.7%)
- **Education**: 114 staff (31.1%)
- **Housing**: 61 staff (16.7%)
- **Welfare**: 45 staff (12.3%)
- **Heritage**: 19 staff (5.2%)

### Employment Duration
- Most employees fall in the **3-5 years** category (93 staff, 25.4%)
- Significant recent hiring with 81 staff (22.1%) at **1 year** and 66 staff (18.0%) at **Less than 1 year**
- Only 18 staff (5.0%) have been employed for **More than 10 years**

### Sick Days
- Average: 29.1 days over two years
- Median: 21.5 days
- Most employees fall within 10-30 sick days
- Some outliers with 85+ sick days

### Response Target
- Mean response rate: 72.7%
- Narrow range (62.8%-81.4%) indicates consistent performance
- Most staff (215) achieve 70-75% response rate
- Only 7 staff reach 80-85% response rate

### Key Relationships
- Modest negative correlation between sick days and response target
- Positive correlation between length of employment and response target performance
- Employees with 10+ years experience show the highest response rates across all departments

## Key Visualizations

### Department Distribution
![Department Distribution](images/department_distribution.png)
*The Environment and Education departments make up over 65% of the total workforce.*

### Response Target by Employment Duration
![Response Target by Length of Employment](images/response_by_tenure.png)
*Performance improves with experience across all departments, with employees having 10+ years of experience showing the highest response rates.*

### Sick Days vs. Response Target
![Sick Days vs Response Target](images/sickdays_response.png)
*A modest negative correlation exists between sick days taken and response target performance.*

*Note: For more visualizations, see the complete analysis in the repository.*

## Conclusions
1. Experience positively correlates with better response rates across all departments
2. New employees (< 1 year) show lower and more variable performance
3. Long-term retention appears to be a challenge with few employees staying beyond 6 years
4. Sick leave has a slight negative impact on response performance


## Tools & Technologies
- Data analysis: R (statistical computing and analysis)
- Visualization: ggplot2, base R graphics
- Statistical methods: Descriptive statistics, distribution analysis, correlation analysis
  
