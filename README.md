# Excel Project

This is my first data analytic project using excel.

### Objective:

The objective is to analyze and visualize the heart disease dataset from Kaggle using excel.

### Data Source:

https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset

### Methodology

The sample data provides some key factors about heart disease. My family has heart disease history and I want to know more details about heart disease and its correlation with other factors such as age or gender. The following steps were taken in excel:
- Create tabs for column notes, editing, pivot table, dashboard and process log
- Copy raw data to editing sheet
- Remove duplicates and blank cells
- Rename column title for easier understanding to the audience
- Filter all columns and check for invalid values: 
    - Thalassemia has value 1-3, remove all values outside the range
    - Number of major vessels 0-3, remove all values outside the range
- There is a mistake of the column notes for chest pain type on Kaggle dataset, found original dataset and corrected the column notes
- Replace some numerical values with the actual information
- Create age brackets to narrow down age variable
- Delete age of 29 which has only 1 row as it will not be helpful during analysis
- Create pivot tables for data visualization
- Create interactive dashboard
- Hide sheets to make the file clear to the audience
