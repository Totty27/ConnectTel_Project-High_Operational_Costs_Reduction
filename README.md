# ConnectTel_Project-High_Operational_Costs_Reduction

## Company or Project Overview

ConnectTel is one of the top telecom provider in South Africa. The company is currently facing high operational costs in its customer call centre department. The management suspects that this could be caused by the inefficiencies in how calls are handled and how teams are managed.

The company have hired me as a Business Analyst to conduct a diagnostic to uncover opportunities to reduce costs without hurting the customer experience.

## Project Objectives

The objectives for this project is to analyse the given data and prepare a short client-ready presentation that serve the following:

- Identifies the key issues causing inefficiences.
- Suggests potential improvements with impact estimates.
- Present practical, data-backed recommendations and limitations.

## Data Sources

- The dataset for this project was provided in an Excel  spreadsheet(ConnectTel_CallCenterDataset.xlsx):
    - [Dataset](ConnectTel_CallCenterDataset.xlsx)

## Analysis Tools

- Microsoft Excel
- Visual Paradigm


## Data Cleaning or Preparation

After downloading and opening the dataset, my first step was cleaning it by performing the following general data cleaning and inspecting activities:

- I started by copying the given dataset and pasting it in a new worksheet titled “Data Cleaning”, I did this to save time in case I made a mistake while cleaning the data. I do not have to download the new dataset.
- Making sure that there are no hidden rows and columns by unhiding them, this helps assure that all data is visible and there are no empty rows or cells.
- After unhiding the rows and columns, I then searched for any blank/ empty rows columns and deleting them. For this dataset there were no blank rows/ columns.
- Cleaned the “Experience” column as it was containing texts values, but the “experience” is supposed to be a numeric value, for example it was written “2-3 months” or “5 months”. I did this using the search/find “months” and replace “nothing/blank” method.
- Then finally, I used data formatting to add 2 decimal places for every numeric/ integer value in the dataset, and to remove extra spaces.


## Exploratory Data Analysis

After assuring that the call centre data clean and is ready for analysis, I started exploring the data to answer the following key questions:

- What might be causing the high costs?
- What key questions should we answer using the data?
- What part of the data will help us conduct an effective analysis?

## Data Analysis
To perform my data analysis, I applied the following functions: 

1. AVERAGE()
   
Purpose: Calculate the average value of key metrics.

- Average Call Duration
- Average Escalation Rate
- Average Cost per Call
- Average CSAT Score
  
### Example:
  
 ``` Excel
=AVERAGE(E2:E500)
```

2. SUM()
   
Purpose: Calculate total values.

- Total Calls Handled
- Purpose: Calculate total values.

### Example:
  
``` Excel
=SUM(D2:D500)
```

3. SUMIF()
   
Purpose: Sum values based on a condition.

- Total Calls Handled per team
- Total Overtime per team
  
### Example:

``` Excel
=SUMIF(A:A,"Team B",I:I)
```

4. MAX()
   
   Purpose: Identify the highest values.

- Maximum Call Duration
- Highest Cost per Call
- Highest Overtime Hours

### Example:

  ``` Excel
=MAX(J2:J500)
```

5. AVERAGEIF()
   
   Purpose: Calculate averages based on specific conditions.

- Average Cost per Call per team
- Average Call Duration per day
- Average Cost for agents with overtime

### Example:

``` Excel
=AVERAGEIF(A:A,"Team A",J:J)
```
## Results or Findings

1. Long Average Call Duration
- The average call duration is about 6.5 minutes, with some calls exceeding 10 minutes.
- There is a strong positive relationship between call duration and cost per call.
- Longer calls mean agents spend more time per customer, increasing operational costs.
  
### Conclusion:
Long call handling time is one of the main drivers of high cost per call.

2. Overtime Hours Increase Costs
- Overtime hours show a strong relationship with higher call costs.
- Some agents work up to 3 hours of overtime.
- Overtime typically involves higher wage rates, increasing the cost of each handled call.
  
### Conclusion:
High overtime usage is another major contributor to the rising call costs.

3. Escalation Rate Impact
- The average escalation rate is about 11%.
- When calls are escalated to supervisors or higher-level support, they increase call duration and resource use.
  
### Conclusion:
Escalations indirectly increase operational costs.

4. First Call Resolution (FCR) Opportunities
- Higher FCR rates reduce repeat calls, but the data suggests room for improvement.
- When issues are not resolved on the first call, customers may call again, increasing total cost.
  
### Conclusion:
Lower FCR can increase the total volume of calls and operational costs.

5. Workload Distribution
- Calls handled vary significantly across agents.
- Some agents handle fewer calls but spend more time on them.
  
### Conclusion:
Possible differences in agent efficiency or experience.

## Recommendations

1. Reduce Average Call Duration
- Provide better training for agents on efficient call handling.
- Implement call scripts or knowledge bases to resolve issues faster.
- Use AI or automated responses for simple queries.
  
### Impact:
Shorter calls will directly reduce cost per call.

2. Minimize Overtime Usage
•	Improve workforce planning and scheduling.
•	Adjust staffing levels during peak call periods.

### Impact:
Reduced overtime will lower labour costs.

4. Improve First Call Resolution (FCR)
- Provide agents with better problem-solving tools and system access.
- Improve training on complex customer issues.

### Impact:
Higher FCR reduces repeat calls and operational load.

5. Reduce Escalations
- Train agents to resolve more issues independently.
- Improve knowledge documentation and troubleshooting guides.

### Impact:
Fewer escalations will reduce call handling time and resource usage.

6. Monitor Agent Performance
This can be done by paying attention to the following metrics:
- Calls handled
- Average call duration
- CSAT score
- FCR rate
- Identify top-performing agents and replicate their practices.
  
### Impact:
Improves overall team efficiency and productivity.

## Limitations

1. Limited Time Scope
- The dataset represents a specific period of operations.
- Seasonal or long-term trends may not be captured.
  
2. Missing Operational Context
The dataset does not include:
- Type of customer issues or call complexity
- As these factors may influence call duration and costs.
  
3. Agent Skill Differences
- The analysis assumes agents perform similarly.
- Differences in experience, training, or specialization may affect results.




