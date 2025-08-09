# TITANIC-DATA-ANALYSIS-PROJECT
Titanic Dataset – Data Cleaning & Exploratory Data Analysis Report
Dataset Source: Kaggle Titanic Competition
Objective: Clean the dataset, explore variable relationships, and identify patterns and trends related to passenger survival.

1. Data Cleaning Process
Missing Values:

    The cabin column dropped due to excessive missing values (77% missing).

    Age missing values filled with the median age.

    Embarked missing values filled with mode (most frequent port).

Data Types:

    Verified numeric and categorical columns.

    Converted Survived to categorical for analysis purposes.

2. Exploratory Data Analysis (EDA) Findings
    Survival Rate Overview
    Overall Survival: ~38% of passengers survived, while ~62% did not.

Key Relationships
Gender

    Females had a much higher survival rate (~74%) than males (~19%).

    Gender was one of the strongest predictors of survival.

Passenger Class (Pclass)

    1st Class: Highest survival rate (~63%).

    3rd Class: Lowest survival rate (~24%).

    Wealthier passengers had better survival chances.

Age

    Children had a slightly better chance of survival than adults.

    The majority of deaths occurred in adults aged 20–40.
Fare

    Higher ticket fares correlated with higher survival rates.

    1st Class tickets were more expensive, and passengers in these cabins survived more often.

Embarkation Port (Embarked)

    Passengers who boarded at Cherbourg (‘C’) had the highest survival rate (~55%).

    Southampton (‘S’) passengers had the lowest (~34%).

3. Correlation Insights
   
    Sex and Pclass showed the strongest correlation with the Survived variable.

    Fare had a positive correlation with survival.

    Age had a weak negative correlation with survival.

4. Conclusion
   The analysis highlights socio-economic status, gender, and point of embarkation as major factors influencing survival on the Titanic. These findings align with historical accounts that women, children, and        first-class passengers were prioritized during evacuation.
