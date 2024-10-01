# Titanic Dataset EDA and Visualization

# Project Overview

This project involves performing data cleaning and exploratory data analysis (EDA) on the Titanic dataset from Kaggle. The objective is to explore relationships between variables and identify patterns and trends in the data.

#Problem Statement

The goal is to analyze the Titanic dataset to:

Explore the distribution of variables like age, gender, and class.
Understand survival rates based on various factors such as gender, passenger class, and family size.
Visualize relationships between variables to identify significant patterns.

# Key Analyses and Visualizations
Age Distribution: Visualized the distribution of ages among passengers.
Survivors vs Non-Survivors: Compared survival outcomes based on multiple factors.
Survival Rate by Gender: Analyzed how survival rates differed between male and female passengers.
Survival Rate by Passenger Class: Explored the survival rates across different passenger classes (1st, 2nd, 3rd).
Survival by Family Size: Investigated the relationship between family size and survival chances.
Correlation Heatmap: Created a heatmap to examine the correlation between numerical variables in the dataset.
Fare vs Survival: Analyzed whether higher ticket fares led to higher survival rates.

# Libraries Used
pandas: For data manipulation and cleaning.
matplotlib: For creating static visualizations.
seaborn: For advanced visualizations and plots.
numpy: For numerical operations.

# Install required libraries:
bash
Copy code
pip install pandas matplotlib seaborn numpy

# Run the analysis and visualizations:
bash
Copy code
python analysis.py
Files Included
analysis.py: The script containing the EDA and visualizations.
titanic.csv: The dataset used for analysis (optional if dataset not included).
output/: Directory with images of generated visualizations.

# Conclusion
Through EDA, we uncovered interesting trends such as the higher survival rates of women and first-class passengers, and we visualized important relationships between key variables in the Titanic dataset.

# Glimps of Data Analysis and Visualisation 

![Survival Rate by Gender](https://github.com/user-attachments/assets/8447e980-efaf-4634-868e-9ba9f9c56710)

![Survival Rate by Passenger Class (Pclass)](https://github.com/user-attachments/assets/5d6b86b3-b3f0-4c76-b598-4f658559dfab)

![survival_by_embarked](https://github.com/user-attachments/assets/44967f77-43c0-446c-bd9a-f4a905ec6710)

![survival_by_family_size](https://github.com/user-attachments/assets/ca71bd8a-1755-4d87-9670-793f07691720)

![age_distribution_survivors_vs_non_survivors](https://github.com/user-attachments/assets/0471e511-21df-4a49-9ba8-8851d557cb09)

![correlation_heatmap](https://github.com/user-attachments/assets/06cf0a8a-16db-41c9-888c-b8ac8dc355ae)

