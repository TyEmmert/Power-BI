# Title: Population of students that received tutoring and their grade for that trimester

### Cleaning Methods for Data

Removed pass/fail grades.  
Added column for grade points (A = 4, B = 3, ...).  
Joined Cohort with studentID in English Grades  
Vlookup Dosage Marking Period to English Grades Table with studentID.  
Vlookup English Program to English Grades Table with studentID.  

### Program/Website Used

Power BI

### Filters

Trimester 1:  
Filtered for Engish Program - "Tutoring: Literacy"  
Filtered for Dosage Marking Period - "Trimester 1"  

Trimester 2:  
Filtered for Engish Program - "Tutoring: Literacy"  
Filtered for Dosage Marking Period - "Trimester 2"  

Trimester 3:  
Filtered for Engish Program - "Tutoring: Literacy"  
Filtered for Dosage Marking Period - "Trimester 3"  

### Parameters

x-axis: Entered Grade
y-axis: Count of Entered Grade
Legend (colors): Grade Cohort

### Description

These 3 charts show the amount of students tutored in any given trimester. It also shows the grade they received for that trimester. The colors represent the the different cohorts that were tutored during that trimester.

### Important thoughts

The data doesn't show how many sessions each student got in order to receive that grade. There could be students in the data that received 1 tutoring session, and then never returned. This isn't an indicator to show a relationship between receiving tutoring, and getting a good grade. It is more to show the type of population of students that were received in each quarter and their respective grades.

### Key Findings

Grades 3-5 only received services in trimester 1 and 2.
Grades K-2 received most of their services in Trimester 2 and 3.

### Next Steps

Check how grade 3-5's grades based on sessions received for the first two trimesters.
Check how the K-2 students performed overall based on their sessions with intervention.