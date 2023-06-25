#Data Visualization

**Analyzing Drug Regimens and Tumor Development**

In this study, I conducted a comprehensive analysis of 249 mice with SCC tumors, focusing on the effectiveness of different drug regimens. Over a period of 45 days, I closely observed and measured tumor development. The main objective was to compare the performance of Capomulin, a drug of interest from Pymaceuticals, against other treatment regimens.


**Data Preparation:**

Merged the mouse_metadata and study_results DataFrames into a consolidated DataFrame, ensuring data integrity.
Identified the number of unique mice IDs in the dataset, and meticulously checked for any mouse IDs with duplicate time points.
Detected the data associated with the mouse ID in question and created a new DataFrame by eliminating this data, ensuring accuracy and reliability.
Summary Statistics Generation:


**Developed a summary statistics DataFrame with the following features:**
A row for each drug regimen.
Columns representing key statistics: mean, median, variance, standard deviation, and SEM of the tumor volume.
Bar Charts and Pie Charts:


**Produced two visually appealing bar charts that showcase the total number of rows (Mouse ID/Timepoints) for each drug regimen throughout the study.**
Utilized both the Pandas DataFrame.plot() method and Matplotlib's pyplot methods to create the bar charts.
Constructed two informative pie charts that illustrate the distribution of female versus male mice in the study.
Employed both the Pandas DataFrame.plot() method and Matplotlib's pyplot methods to generate the pie charts.


**Quartiles, Outliers, and Box Plot Creation:**

Calculated the final tumor volume for each mouse across four promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.
Computed the quartiles and Interquartile Range (IQR) to identify potential outliers across all four treatment regimens.
Created a grouped DataFrame displaying the last (greatest) time point for each mouse, merged it with the original cleaned DataFrame.
Employed a systematic approach to determine outliers by establishing upper and lower bounds and showcased the results.
Utilizing Matplotlib, designed an illustrative box plot representing the distribution of final tumor volumes for all mice in each treatment group, highlighting any potential outliers with distinct color and style.



**Line Plot and Scatter Plot:**

Selected a specific mouse treated with Capomulin and generated a visually compelling line plot depicting the tumor volume's progression over time for that mouse.
Developed an insightful scatter plot illustrating the relationship between mouse weight and the average observed tumor volume for the entire Capomulin treatment regimen.


**Correlation and Regression:**

Calculated the correlation coefficient and derived a linear regression model between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen.
Plotted the linear regression model on top of the previous scatter plot, providing a clear visual representation of the relationship.


**Resources**

Throughout the development of these analyses, I referenced various resources such as YouTube tutorials, reputable websites like w3schools.com, learnpython.com, geeksforgeeks.org, flexiple.com, and simplilearn.com. This reflects my commitment to continuous learning and staying up-to-date with the latest techniques and practices.

Please do not hesitate to reach out if you require further information or have any questions.
