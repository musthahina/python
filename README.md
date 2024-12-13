## Project Overview
This project involves analyzing employee data for ABC Company. The dataset consists of 458 rows and 9 columns, representing information about employees across various teams. The goal is to preprocess the dataset, perform detailed analysis, and present the findings graphically. 

---

## Objectives

### 1. **Preprocessing**
- Corrected the "height" column by replacing its values with random numbers between 150 and 180.
- Ensured data consistency and integrity by handling missing or null values and verifying dataset cleanliness.

### 2. **Analysis Tasks**
1. **Team Distribution:** Determined the distribution of employees across teams and calculated percentage splits.
2. **Position Breakdown:** Segregated employees based on their positions.
3. **Predominant Age Group:** Identified the most common age group among employees.
4. **Salary Expenditure:** Found the team and position with the highest salary expenditure.
5. **Age-Salary Correlation:** Investigated the correlation between age and salary.

### 3. **Graphical Representation**
Created visualizations for each analysis task to enhance the understanding of the dataset:
- Bar chart for team distribution.
- Bar chart for segregating employees based on positions
- Pie chart for Age group analysis
- Bar charts for salary expenditure among different Teams and Positions.
- Heatmap for correlation analysis between Age and Salary.

### 4. **Data Story**
Developed insights highlighting key trends, patterns, and correlations:
- **Team Trends:** Highlighted teams with the highest employee count and expenditure.
- **Age Insights:** Showed predominant age groups and their salary patterns.
- **Position-Salary Dynamics:** Identified positions with maximum salary allocation.
- **Correlation Observations:** Explored age and salary relationships.

---

## Dataset
- The dataset contains 458 rows and 9 columns, including fields such as Name, Team	Number, Position, Age, Height, Weight, College, Salary
- **Preprocessed Dataset:** Included in the repository for transparency and reproducibility.

---

## Tools and Libraries
- **Python:** For data manipulation and analysis.
- **Libraries:**
  - Pandas and NumPy for preprocessing and analysis.
  - Matplotlib and Seaborn for graphical representation.

---

## Insights
1.The 'New Orleans Pelicans' has the highest number of employees, slightly exceeding others.
2.The 'Minnesota Timberwolves','Orlando Magic' have the lowest employee count compared to other teams.
3.The distribution of employees appears fairly even across all teams, with slight variations. Most teams have a similar number of employees (around 15).
4.The 'SG' position has the highest number of employees, with a count above 100. This suggests it is the most common role in the organization.
5.The 'C' position has the lowest employee count at 79. This could indicate a smaller demand for this role.
6.The majority of employees (346) belong to the age group '20-30'. This indicates that the organization primarily employs younger individuals, possibly early-career professionals.
7.The age group '30-40' has 91 employees, significantly lower than the 20-30 group. This may indicate a trend where employees in this age range move on to other roles or organizations.
8.No employees are represented in the '40-50' and '50-60' age groups. This could indicate a lack of senior-level professionals or a focus on hiring younger talent.
9.The 'Cleveland Cavaliers' is top team with the highest salary expenditures.
10.The Philadelphia 76ers have the lowest salary expenditure among the teams
11.Position 'C' appears to have the highest total salary.
12.Position 'SG' appears to have the lowest total salary
13.The value between Age and Salary is 0.21, indicating a weak positive correlation.
14.This means that as age increases, salary tends to increase slightly, but the relationship is not strong.

---

