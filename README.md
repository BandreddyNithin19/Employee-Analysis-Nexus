# Employee Analysis 

## Tools Used
- PowerBI
- GoogleColab

## Summary of CSV

### Education
- Most individuals have a Bachelor's degree (3601 out of 4653).

### JoiningYear
- Individuals joined between the years 2012 and 2018.
- The average joining year is around 2015.

### City
- Most individuals are from Bangalore (2228 out of 4653).

### PaymentTier
- Payment tier ranges from 1 to 3, with an average of approximately 2.7.

### Age
- Age of individuals ranges from 22 to 41, with an average age of approximately 29.4.

### Gender
- Most individuals are male (2778 out of 4653).

### EverBenched
- Most individuals have never been benched (4175 out of 4653).

### ExperienceInCurrentDomain
- Experience in the current domain ranges from 0 to 7, with an average of approximately 2.9.

### LeaveOrNot
- The average of this column is approximately 0.34, indicating that about 34% of the individuals are likely to leave.

## Summary of Tasks

### Task - 1: Descriptive Statistics
- Average Age: 29.39 years
- Average Experience in Current Domain: 2.91 years
- Average Years Since Joining: 7.94 years

### Task - 2: City-wise Distribution
- Bangalore: 2228
- Pune: 1268
- New Delhi: 1157

### Task - 3: Gender Distribution
- Male: 2778
- Female: 1875

### Task - 4: Most Common Degree
- Most Common Degree: Bachelors
- Count: 3601

### Task - 5: Salary Tier Distribution
- Tier 3: 3492
- Tier 2: 918
- Tier 1: 243

### Task - 6: Visualizations
- Scatter Plot of Age vs. Leave Decision
  - X-Axis: Age (ranging from 22.5 to 40)
  - Y-Axis: Leave Decision (labeled as 0 and 1)
- Box Plot of Experience for Leave Decision
  - X-Axis: Leave Decision (categorized as 0 and 1)
  - Y-Axis: Experience (specifically for experience = 1 and leave_or_not = 0)
- Grouped Bar Chart of Leave Decision by Gender
  - X-Axis: Gender
  - Y-Axis: Count of Leave Decision
- Correlation Heatmap
  - Heatmap displaying correlation coefficients between age, experience, and leave_or_not
  - Values:
    - Age vs. Experience: -0.13
    - Age vs. Leave_or_Not: -0.051
    - Experience vs. Leave_or_Not: -0.031

The summary provides an overview of descriptive statistics, distributions, and visualizations related to age, experience, leave decisions, city, gender, education, and salary tiers. It gives a comprehensive view of employee characteristics and their relationships within the dataset.

## Instructions for Running the Analysis
1. Ensure you have PowerBI and GoogleColab installed.
2. Open the provided CSV file in PowerBI for basic data analysis.
3. Use GoogleColab for any additional data analytics and visualization tasks.
4. Execute the code in GoogleColab to generate the specified visualizations.
5. Explore the insights gained from the analysis to better understand the employee dataset.
