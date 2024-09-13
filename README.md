# Student_Result-data-Analysis
Objective:

To analyze student data to understand factors influencing academic performance, identify trends in student behavior, and provide insights for educational improvement.

Data Cleaning and Transformation:

Remove Unnamed Column:

Removed the unnamed column if present.

Replace Values:

Replaced "05-Oct" with "5-10" in the "WklyStudyHours" column to ensure consistent date formatting.
Data Analysis:

Gender Distribution:

Used seaborn's countplot to visualize the distribution of genders in the dataset.

Relationship between Parents Education and Student Score:

Created a heatmap to explore the correlation between parents' education levels and students' scores.

Relationship between Parents Marital Status and Student Score:

Employed a heatmap to analyze the relationship between parents' marital status and students' scores.

Subject Difficulty Analysis:

Utilized box plots for each subject to identify outliers and potential areas of difficulty for students.

Libraries Used:

Pandas: For data manipulation and analysis.

NumPy: For numerical operations.

Matplotlib: For creating static visualizations.

Seaborn: For statistical visualizations.
