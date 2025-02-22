# Bolt-Ride_Analysis
Project Overview
This project aims to analyze Bolt ride data to understand various aspects of ride usage, such as the distribution of rides across different categories, purposes, months, days, and times. The analysis is visualized using a dashboard to provide insights into ride patterns and help make data-driven decisions.
Files in the Project
1.	Bolt Ride Data set.csv: The original dataset containing raw Uber ride data.
2.	BoltDatasetCleaned.csv: The cleaned dataset after preprocessing.
3.	Bolt Dashboard.png: An image file showing the dashboard visualizing the analysis results.
4.	Bolt_Rides_Data_Analysis_Documentation_and_Recommendations.docx: A document containing detailed documentation of the analysis steps and recommendations based on the analysis.
Analysis Steps
1.	Importing Libraries:
o	Used pandas for data manipulation, numpy for numerical operations, matplotlib.pyplot and seaborn for data visualization.
2.	Loading the Dataset:
o	Loaded the Bolt dataset from a CSV file and displayed the first 10 rows to understand its structure.
3.	Basic Data Exploration:
o	Generated summary statistics, concise data summary, checked for missing values, duplicate rows, and unique values in each column.
4.	Handling Missing Values:
o	Filled missing values in the 'PURPOSE' column using forward fill method.
5.	Converting Date Columns:
o	Converted 'START_DATE' and 'END_DATE' columns to datetime format.
6.	Extracting Date and Time Components:
o	Extracted date, time, month, and year from 'START_DATE' and 'END_DATE' columns and added these as new columns.
7.	Dropping Original Date Columns:
o	Dropped 'START_DATE' and 'END_DATE' columns and rearranged the remaining columns.
8.	Handling Missing Values in 'Month' and 'Year' Columns:
o	Filled missing values in the 'month' and 'year' columns using the mode and converted them to integer type.
9.	Extracting Hour and Minute Components:
o	Extracted hours and minutes from 'start_time' and 'end_time' columns and added them as new columns.
10.	Calculating Duration:
o	Calculated the duration of each trip in minutes and added it as a new column.
11.	Plotting Data:
o	Visualized the data using various plots like heatmap for correlations, count plots, bar plots, and distribution plots to understand the patterns and distributions in the data.
12.	Saving Cleaned Data:
o	Saved the cleaned and processed DataFrame to a new CSV file.
Dashboard Insights
The dashboard visualizes key insights from the analysis:
1.	Count of CATEGORY by CATEGORY: Shows the distribution of rides by business and personal categories.
2.	Count of Month by Month: Displays the number of rides each month.
3.	Count of Month and Sum of MILES by Month: Combines the count of rides and the total miles traveled each month.
4.	Count of Day by Day: Shows the distribution of rides across different days of the week.
5.	Count of PURPOSE by PURPOSE and CATEGORY: Displays the purpose of rides and categorizes them by business and personal use.
6.	Sum of MILES by Day Time: Shows the total miles traveled during different times of the day.
Recommendations
Based on the analysis, the following recommendations are made:
1.	Optimize Ride Allocation During Peak Months.
2.	Target Marketing Campaigns by Purpose.
3.	Improve Services During Peak Hours
4.	Monitor and Reduce Trip Duration.
5.	Enhance Services in High-Demand Categories.
6.	Seasonal Promotions.
7.	Analyze High-Mileage Trips.
8.	Focus on Popular Routes and Destinations.
9.	Customer Feedback Integration.
10.	Driver Training Programs.
By implementing these recommendations, Bolt can enhance its operational efficiency, improve customer satisfaction, and increase overall ridership.
How to Use This Project
1.	Load the provided CSV files (Bolt ride Data set.csv and BoltDatasetCleaned.csv) into a pandas DataFrame.
2.	Follow the documented steps to understand the data cleaning and preprocessing process.
3.	Review the dashboard (Dashboard.png) to gain insights from the visualized data.
4.	Refer to the recommendations document (Bolt_Rides_Data_Analysis_Documentation_and_Recommendations.docx) for detailed documentation and suggestions for improvement.
Collaborator
•	RijuKoshy – koshyriju@gmail.com
Feel free to reach out to any of the collaborators for questions or further information regarding the project.
Steps for Cloning the Project
1.	Clone the Repository:
2.	git clone https://github.com/rijukoshy/Bolt-Ride_Analysis
3.	Navigate to the Project Directory:
4.	cd Bolt-Rides-Analysis
5.	Install the Required Libraries:
6.	pip install -r requirements.txt
7.	Run the Jupyter Notebook:
8.	jupyter notebook Bolt_Rides_Analysis.ipynb
9.	Review the Documentation and Recommendations:
o	Open and review the Bolt_Rides_Data_Analysis_Documentation_and_Recommendations.docx for detailed documentation and insights.
