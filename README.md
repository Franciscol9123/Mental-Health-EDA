# Mental Health Indicators Analysis

## Project Overview

This project aims to analyze the relationship between mental health indicators—specifically symptoms of depressive disorder, anxiety disorder, and a combination of both—and various demographic factors such as education level, state, and age group. The analysis utilizes data from the U.S. Census Bureau's Household Pulse Survey.

## Objectives
The key objectives of this project are:

- To investigate the correlation between mental health indicators and demographic factors.
- To visualize trends and patterns in mental health conditions across different states, age groups, and education levels.
- To provide insights that could help policymakers, mental health professionals, and researchers understand the distribution of mental health issues in the U.S. population.

## Dataset Information
The dataset is sourced from the U.S. Census Bureau's Household Pulse Survey

## Data Fields
- Indicator: The type of mental health condition (e.g., Symptoms of Depressive Disorder, Symptoms of Anxiety Disorder, Symptoms of Anxiety Disorder or Depressive Disorder).
- Group: The demographic category used to group data (e.g., By Education, By State, By Age).
- Subgroup: Specific subcategories within each Group (e.g., various states, age ranges, education levels).
- Value: The percentage of respondents reporting symptoms of the specified mental health condition.
- State: The U.S. state in which respondents reside.
- Age Group: The age range of respondents.
- Education Level: The highest level of education completed by respondents.

## Data Cleaning and Preparation
The data required extensive cleaning to ensure accuracy and relevance for the analysis. Below are the key steps undertaken:

- Loading Data: The dataset was imported using Pandas, and the initial inspection was performed to understand its structure and content.
- Handling Missing Data: Missing values were identified and filled with 0s or excluded where necessary to maintain data integrity.
- Data Type Conversion: Certain fields, particularly the Value column, were converted to numeric types to facilitate calculations and visualizations.
- Filtering Data: The dataset was filtered to focus on specific mental health indicators and demographic subgroups relevant to the study’s objectives.
- State and Age Group Adjustments: The dataset was adjusted to include or exclude certain states or age groups based on the analysis requirements.
- Visualizations
- The project includes four primary visualizations, each targeting a different aspect of the dataset to uncover insights into how mental health conditions vary across different demographic groups.

## Visualization 1: Bar Plot of Mental Health Indicators by Education Level
- Description: This bar plot visualizes the relationship between education levels and the prevalence of mental health disorders (depression, anxiety, or both). Education levels analyzed include "Less than a high school diploma," "High school diploma or GED," "Some college/Associate's Degree," and "Bachelor's degree or higher."

- Purpose: To determine whether educational attainment is associated with different levels of mental health issues.

### Findings

- Individuals with lower education levels tend to report higher percentages of mental health symptoms.
- There is a noticeable decrease in reported symptoms as the level of education increases, suggesting a possible protective factor of higher education against mental health issues.

## Visualization 2: Box Plot of Mental Health Indicators by State
- Description: This box plot illustrates the distribution of mental health indicators across various U.S. states. It provides a visual comparison of how mental health conditions vary by state, showing the range, median, and outliers.

- Purpose: To identify states with higher variability or outliers in mental health symptom reporting.

### Findings

- Some states show a wider range of mental health symptom reporting, with significant outliers indicating pockets of populations with either very high or very low symptom prevalence.
- The median values differ across states, highlighting regional differences in mental health outcomes.

## Visualization 3: Box Plot of Mental Health Indicators by Age Group
- Description: This box plot focuses on mental health indicators distributed across different age groups. Age groups include ranges such as "18-29," "30-39," "40-49," "50-59", "60-69," "70-79," and "80 years and older"

- Purpose: To explore the relationship between age and mental health, identifying which age groups are most affected by depressive or anxiety symptoms.

### Findings

- Younger age groups, particularly those aged 18-29, show a higher median percentage of reported mental health symptoms compared to older age groups.
- The spread of the data within each age group suggests that younger populations are more vulnerable to mental health issues during the pandemic.

## Visualization 4: Radar Map of Mental Health Indicators by Sex
- Description: This radar map compares mental health indicators between Male's and Female's, offering a multi-dimensional perspective. The radar map format allows for the simultaneous comparison of multiple variables, making it easier to spot trends and correlations.

- Purpose: To identify how Male's and Female's compare and are affected by mental health disorders.

### Findings

- The radar map reveals distinct patterns where Female's consistently have a steady, higher percentage of mental health disorders 
then Male's. 
## Visualization 5: Age histograms
- Description: These three histograms show the distribution of age groups by indicators.
- Purpose: To identify distributions of each invidividual age group

### Findings
- The histograms show some outliers along with a trend of younger age groups being affect by depression and/or anexity the most.
  
## Visualization 6: Age Linear Regression lines
- Description: These show the negative correlation between the age groups and frequency of reported means.
- Purpose: To confirm the correlation hypothesized results

### Findings
- There indeed is a correlation between the data indicating that the older you are results in less reported symptoms.
  
## Visualization 7: Race/Ethnicity histograms
- Description: These three histograms show the distribution of racial groups by indicators.
- Purpose: To identify distributions of each invidividual racial group

### Findings
- The histograms show some outliers along with a trend of multi racial groups being affected by depression and/or anexity the most.
  
## Visualization 8: Race Stacked Bar Chart
- Description: These bar charts displays the reported symptoms by racial group over the three main indicators.
- Purpose: To compare each indicator and race over a single chart.

### Findings
- The bar graphs show that single racial group often report less than multi-racial or ethnic groups
- 
## Conclusion
- This analysis demonstrates that mental health outcomes are influenced by a combination of demographic factors including education level, state of residence, age group, and sex. The findings underscore the need for targeted mental health interventions that consider these demographic factors to effectively address the mental health crisis.
- There is a correlation between age and reported symptoms. 18-50 affected more significantly than older reporters.
- Races are affected differently: Asians reported less, multi-racial and latinos reported the most.
- Some states reported higher frequency of symptoms. Higher density states had higher reports in all indicators. Southern states reported higher as well.
- Sexes may report at a different frequency. Men might not be as likely to report.
- Higher education leads to less reports, likely because of the less stressful life and evironment.  
 


