# PYTHON-CAPSTONE
Given a dataset from ABC company, consisting of 458 rows and 9 columns. The company requires a comprehensive report detailing information about their employees across various teams. Your tasks include preprocessing the dataset, analyzing the data, and presenting your findings graphically. Here's a breakdown of what you need to do:

Preprocessing:
Correct the data in the "height" column by replacing it with random numbers between 150 and 180. Ensure data consistency and integrity before proceeding with analysis. (1 mark)

Analysis Tasks:
1. Determine the distribution of employees across each team and calculate the percentage split relative to the total number of employees. 
2. Segregate employees based on their positions within the company.
3. Identify the predominant age group among employees. 
4. Discover which team and position have the highest salary expenditure.
5. Investigate if there's any correlation between age and salary and represent it visually.

The project effectively utilizes data manipulation, visualization (with Matplotlib and Seaborn), and basic statistical analysis to derive insights from the dataset.
Data Cleaning: Null values in the  columns were handled by dropping rows with missing data. The 'Height' column was replaced with random values between 150 and 180 cm, and duplicate rows were removed.
Key insights include:
1.	Team Distribution: The New Orleans Pelicans had the highest player representation (4.38%), with the Minnesota Timberwolves having the lowest (2.19%).
2.	Position Segmentation: Players were grouped by position, providing detailed lists of players in each role.
3.	Age Analysis: The predominant age group among players was 20–25 years, comprising 168 players.
4.	Salary Insights: The Miami Heat's Power Forward (PF) position had the highest total salary expenditure.
5.	Correlation Analysis: A weak positive correlation (0.16) was found between player age and salary. It is visualized using a scatter plot.

