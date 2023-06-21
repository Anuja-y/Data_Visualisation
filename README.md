# Data_Visualisation

In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

**Prepared the Data**

Merged the mouse_metadata and study_results DataFrames into a single DataFrame. Displaying the number of unique mice IDs in the data, and then checking for any mouse ID with duplicate time points. Displaying the data associated with that mouse ID, and then creating a new DataFrame where this data is removed. 

**Generated Summary Statistics**

Created a DataFrame of summary statistics. 
- A row for each drug regimen. 
- A column for each of the following statistics: mean, median, variance, standard deviation, and SEM of the tumor volume.

**Bar Charts and Pie Charts**
  
- Generated two identical bar charts displaying the total total number of rows (Mouse ID/Timepoints) for each drug regimen throughout the study.
    - Created a bar chart with the Pandas DataFrame.plot() method.
    - Created a second bar chart with Matplotlib's pyplot methods.
- Generated two identical pie charts displaying the distribution of female versus male mice in the study.
    - Created a pie chart with the Pandas DataFrame.plot() method.
    - Created a pie chart with Matplotlib's pyplot methods.
  
**Quartiles, Find Outliers, and Create a Box Plot**

- Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Then, calculated the quartiles and IQR, and determine if there are any potential outliers across all four treatment regimens by useing following substeps:
    - Created a grouped DataFrame that shows the last (greatest) time point for each mouse. Merged this grouped DataFrame with the original cleaned DataFrame.
    - Created a list that holds the treatment names as well as a second, empty list to hold the tumor volume data.
    - Looped through each drug in the treatment list, locating the rows in the merged DataFrame that correspond to each treatment. Appended the resulting final tumor volumes for each drug to the empty list.
    - Determined outliers by using the upper and lower bounds, and displayed the results.
      
- Using Matplotlib, generated a box plot that shows the distribution of the final tumor volume for all the mice in each treatment group. Highlighting any potential outliers in the plot by changing their color and style.

**Line Plot and Scatter Plot**

- Selected a single mouse that was treated with Capomulin, and generate a line plot of tumor volume versus time point for that mouse.
- Generated a scatter plot of mouse weight versus average observed tumor volume for the entire Capomulin treatment regimen.

**Correlation and Regression**

 - Calculated the correlation coefficient and linear regression model between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen.
 - Plotting the linear regression model on top of the previous scatter plot.


**Resources**
- YouTube
- https://www.w3schools.com/
- learnpython.com
- www.geeksforgeeks.org
- flexiple.com
- www.simplilearn.com


Please do not hesitate to contact me if you need further information.
