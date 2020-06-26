# Predicting-Absenteeism:Project Overview
### Absenteeism:-
absence from work during normal working hours,resulting in temporary incapacity to execute regular working activity
From a business perspective,this project will address absenteeism at a company during work time

 
 ## Information about Dataset:
 Prediction is on the basis of how many working hours an employee could be away from work based on how far they live from workplace?How many children and pets they have?
 Do they have  higher education? etc.
 
 
 ## DATA
 * ID
 * Reason for Absence
 * Distance to Work
 * Daily Workload Average
 * Absenteeism time in hours
 * Pets
 * Children
 * Body Mass  Index(BMI)
 * Education
 * Transport Expense
 * Age
 * Date 
       
 ## DATA CLEANING
 * Drop the ‘ID’ column
 * Group the reasons for absence into multiple dummy variables:-

    Group 1: Columns 1 to 14

    Group 2: Columns 15, 16, and 17

    Group 3: Columns 18, 19, 20, and 21
 
    Group 4: Columns 22 to 28

 *  Drop the ‘Reason for Absence’ column.
 * Extract the month value and the day of the week from the ‘Date’ column. Then, drop the ‘Date’ column as well.
 * Turn the data from the ‘Education’ column into binary data, by mapping the value of 0 to the values of 1, and the value of 1 to
   the rest of the values found in this column.
 ## Workflow:
 Preprocessing the data then make a logistic regression model save as separate files named Absenteesim_preprocessing.ipynb and my MODEL.ipynb and predict the absenteeism 
 for the fresh new data as Absenteeism_new_data.csv save it in Absenteeism_predictions.csv and use tableau as a visualization tool
 ## Visualizations:
 Probability that a given individual is expected to be absent from work for more than 3 hours :
 
 
()

![alt text](https://github.com/Rish59/Predicting-Absenteeism/blob/master/Images/img1.png "With Age")
![alt text](https://github.com/Rish59/Predicting-Absenteeism/blob/master/Images/img2.png "With Reasons")
![alt text](https://github.com/Rish59/Predicting-Absenteeism/blob/master/Images/img3.png "With Transportation expense and children")
