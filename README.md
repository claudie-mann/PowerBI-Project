# Data Professionals Survey - Full PowerBI Project
Full PowerBI project using data collected from 700+ data professionals on social media platforms. 

Credit: https://github.com/AlexTheAnalyst/Power-BI/blob/30d9e66e34a15900c5a191e76372e96bf4acf43a/Power%20BI%20-%20Final%20Project.xlsx

## 📝Premise
The goal of completing this project is to consolidate and showcase PowerBI skills. The entire project was completed on PowerBI only, therefore, data cleaning was performed with consideration of Power Query's limitations in comparison to Excel or SQL. 

## 🪜Process

### 1. Import & Transform - Power Query
- Deleted empty columns from 'Browser' to 'Refer' inclusive
- Standardised answers to Q1, Q4, Q5, and Q11 by performing split column by respective delimiter
- Transform answers to Q3 (yearly salary) to numeric value by splitting the column and calculate the medium as new column 'Average Salary'
- Change data type of column from text to int

### 2. Visualisation Building
- Added titled to dashboard
- Added cards for displaying key numerics: number of participants and their average age
- Generated stacked bar chart to display average annual salary by job title
- Generated staked column chart for favourite programming language by job title
- Created tree map of average salary by country
- Used gauges to visualise the average scores rated by survey takers when asked "How happy are you with work/life balance?" and "How happy are you with your current salary?" respectively
- Generated doughnut charts for answers describing the difficulty of getting into data, and whether or not the participant switched from another job to their current data profession

### 3. Tidying Up
- Adjusted sizes of all displayed graphs/charts
- Formated and shortened titles and legend titles
- Applied a preset theme

## ✅Final Look
<img width="1908" height="1082" alt="image" src="https://github.com/user-attachments/assets/0e1f2b65-ac20-41fb-9ca1-f400b439b41e" />


## 🏁Summary & Findings
I've had a lot of fun completing this simple project, from cleaning data in PowerBI (which doens't happen a lot in real-life scenarios) to doing the final touch-ups. Sacrifices were of course made during the data cleaning process as I avoided using another platform. For instance, I was not able to explore all types of job titles or every country of residence of the participants, and that they were compiled into 'other'. It is a small amount of data retrieved through conducting a digital survey to a small number of audiences. Albeit the scale, a variety of demographics was engaged, which allowed me to extract some really interesting insights. For example, 

### Python is overwhelmingly popular among participants across all job titles. 
Following by R and 'other' types of programming language, which were dwarved by the amount of votes Python received. 

<img width="978" height="420" alt="image" src="https://github.com/user-attachments/assets/bba076be-0c54-41cd-a40e-643ab03be528" />

### More than half of the participants switched to a data job from something else. 
<img width="481" height="437" alt="image" src="https://github.com/user-attachments/assets/9b2740dc-aa86-46d6-b65e-81923c5dbaf8" />

### While being the highest earners, only 24% of data scientists started their career in Data, and 76% of them switched careers from something else. 
### Those who found it 'very difficult' and 'difficult' to break into Data were mostly located in the United States, which is also where participants who voted for 'easy' and 'very easy' are based. 






