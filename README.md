# Employee Analysis Report 

## Table of Contents
-	[Project Overview](#project-overview)
-	[Data Source](#data-source)
-	[Tools](#tools)
-	[Data Cleaning and Preparation](#data-cleaning-and-preparation)
-	[Exploratory Data Analysis](#exploratory-data-analysis)
-	[Data Analysis](#data-analysis)
-	[Insights](#insights)

### Project Overview

ABC Company requires a comprehensive report detailing information about its employees across various teams. This project involves,preprocessing the dataset, analyzing the data, and presenting the findings graphically. 

We will also identify the key  patterns and trends and provide necessary recommendations based on analysis.
    

### Data Source
The primary dataset used is ‘employee_details.csv’ which contains 458 rows and 9 columns. It includes the details such as position,team,height,weight,age,college,salary etc.


### Tools
The analysis was conducted using Python 3.x [Download here](#http://python.org/)
with the following libraries: 

-     Pandas
       
  - Installation: ‘pip install pandas’.
    
-	    NumPy
  
  - Installation:  ‘pip install numpy’.
    
-	   Matplotlib
  
  - Installation:  ‘pip install matplotlib’.
    
-	   Seaborn
  
  - Installation: ‘pip install seaborn’.

### Data Cleaning and Preparation
In the initial data preparation, the following tasks were performed:
1. Loading data and inspecting the dataset.
2. Checking basic information (column types, number of rows, missing values, etc.).
3. Handling missing values:
     - The "College" column had 84 missing values, which were filled with "Unknown". 
     - The "Salary" column had 11 missing values, which were imputed with the median salary.
4. Checking duplicate rows.
5. Datatype conversion.
6. Correcting Inconsistency:
    -The "Height" column contained inconsistent data and was standardized by replacing it with random integers between 150 and 180 for consistency.

### Exploratory Data Analysis
EDA involved exploring data to answer the key questions such as:

1. What is the distribution of employees across each team and calculate the percentage split relative to the total number of employees?

2. How are employees segregated based on their positions within the company?
   
3. Which the predominant age group among employees?
   
4. Which team and position have the highest salary expenditure?
   
5. Is there a correlation between age and salary? if so, represent visually. 

### Data Analysis
Analysis was performed using following libraries :
-  Pandas : For data manipulation and analysis.
-  NumPy: For numerical computations.
- Matplotlib :For Data Visualization.
- Seaborn : For additional visualization and styling.

### Insights/Findings

The analysis revealed the following insights:

1. Highest number of employees belong to Team New Orleans Pelicans, which is of 4.15% of total employee.
   
2. Minnesota Timberwolves and Orlando Magic have  the least number of employees,each contributing 3.06%.

3. Most common job role is Shoot Guard (SG) , while least is Centre.

4. The majority of employees fall within the 26-35 age group, while:
   
     •	The Shooting Guard role likely has a high number of employees in this age band.
   
     •	The Center position likely has more employees in the 36-45 age group, given its lower total count.

5. The highest salary expenditure is for Team Los Angeles Lakers, ie for the Small   Forward (SF) position.
   
6. The second-highest salary expenditure is for Team Miami Heat.

7. There is a slight positive correlation of 0.209 between age and salary meaning salary increases with age.



