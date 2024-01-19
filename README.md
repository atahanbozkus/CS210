# CS210 - Data Analysis/Exploration Project

## Overview

In this project, I discussed the data I obtained from the gym application I use and the impact of this data on the time I spend in the gym after school starts, homework, projects and exams.

- Atahan Bozkuş - 28471

## Data

1) before.csv:
- There are 4 columns in total in this csv file: Day+D6A1:D102, Time Spent, Check-In Time, Check-Out Time.
2) after.csv:
- There are 7 columns in total in this csv file: Day+D6A1:D102, Time Spent, Check-In Time, Check-Out Time, Number of Project Deadline, Number of Homework Deadline, Number of Exam.

## Methodology

1) Library Imports and Data Loading
- First, various Python libraries were imported into the project. Then the data loading process takes place. Typically, data was enclosed in a DataFrame using a line like pd.read_csv('file_path.csv'). This phase is the foundation of any data analysis project.

2) Data Preprocessing
- In the data preprocessing phase, data is cleaned and made ready for analysis. Operations performed at this stage may include checking for missing data (isnull()), editing data types (astype()), or removing unnecessary columns (drop()). These steps affect the accuracy of the analysis by improving the quality of the data.

3) Data Analysis
- In the data analysis part, various calculations and operations are performed on the data. For example, while data is grouped and summarized according to certain categories with the groupby() function, basic statistical properties of the data can be quickly examined with the describe() function.

4) Visualization
- Data visualization is used to present the results in a clear and effective way. Libraries such as matplotlib or seaborn are used to create various types of plots (e.g. bar charts, pie charts). Visualization makes findings easily understandable, especially in large data sets or complex analyses.

5) Modeling and Evaluation
- Modeling is done using libraries such as sklearn and includes the stages of splitting the data into training and test sets (train_test_split()), training the model (fit()) and testing (predict()). Various metrics (such as accuracy_score, confusion_matrix) are used to evaluate the performance of the model.
  

## Result
- According to my analysis, there is a significant decrease in the time I do sports during the school term. This decrease is especially evident during busy periods such as exams and homework. The pie chart shows that the time spent on sports during the school year decreases as a percentage. While the average exercise time is 1 hour on normal days, this decreases to 20 minutes on busy days. While my daily exercise time before school is 70 minutes on average, it decreases to 65 minutes during school term and 20 minutes on busy days. While more sports are done on weekends than during the week, this difference decreases after school.

----------------------------

Detailed graphics and anaylsis is in the Report.pdf file.

