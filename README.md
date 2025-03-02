                                           STUDENT DEPRESSION ANALYSIS

## Objective: To conduct a comprehensive analysis of student’s data using different metrics in the dataset to find out key insights into student’s depression and visualize the same using Tableau.

## Business Requirements:
1.	Find out the correlation between academic pressure and depression.
2.	Find out the correlation between study hours and no of depressed students.
3.	Do study hours impact sleep duration and how does it in turn affect student’s mental health.
4.	Show if gender and depression have any relationship whatsoever.
5.	Check the impact of dietary habits on depression.
   
## Steps Followed:
1.	Data was imported to Microsoft SQL Server in the form of excel file.
2.	No of students present under each gender category was checked.
3.	‘Female’ was renamed to ‘F’ and ‘Male’ to ‘M’ under the gender column.
4.	Next checking was done for null and blank values under the gender column.
5.	Then the students were grouped by age and the no of students in each age was checked arranging them in descending order.
6.	New column named ‘Age Group’ was added to the table.
7.	Under Age Group column students between 18 and 24 were placed under A1 category,25 and 30 under A2 category and greater than 30 under A3 category.
8.	Then the no of students under each age group category were checked.
9.	Next the no of students was checked under each column category column wise.
10.	The datatypes of columns ‘Depression’, ’Have you ever had suicidal thoughts’ and ‘Family history of mental illness’ were changed from bit to varchar.
11.	The columns ‘depression’, ‘family history of mental illness’ and ‘have you ever had suicidal thoughts’ were modified as having ‘Yes’ when value was 1 and ‘No’ when value 
    was 0.
12.	Then the data from exported from Microsoft SQL Server to Excel.
13.	In Excel, an extra index column was added in the beginning of the dataset.
14.	Then dataset was imported to Tableau and dashboard building process was started.
15.	Firstly, a bar chart was built to show correlation between depression and academic pressure with the student count
16.	Another bar chart was plotted to show relationship between study hours and no of students with depression as the label.
17.	A third bar chart was plotted to show relationship between sleep duration and average study hours. Next a table was plotted to show correlation between sleep duration 
    and depression.
18.	A bar chart was plotted to distinguish depressed students based on gender.
19.	A pie chart was plotted to divide the students based on their dietary habits. Next a table was plotted to see the count of depressed/undepressed students under each 
    dietary category.
20.	Finally all the visualizations were brought together to build the final dashboard.
 
## Key Findings:
1.	Academic pressure and depression have a positive correlation that is as academic pressure increases depression percentage amongst students also increases.
2.	Depression and study hours are not directly related however with increase in study hours, the average sleep duration reduces and it is found that students with less 
    sleep duration are more likely depressed than students with more sleep hours.
3.	Gender doesn’t have any direct relationship with depression.
4.	Dietary habits display the strongest relationship with depression as students with unhealthy habits are way more likely to be depressed compared to students with healthy 
    ones.

   
