# Big-Query-Projects
This project involves the development of an Exam Analysis and Performance Tracking System using BigQuery to process and analyze educational data. The system calculates the actual marks for students in each exam session, classifies them based on their performance (Pass/Fail), ranks the top performers and tracks their performance trends across exams.
# Exam Analysis and Performance Tracking System

## Project Overview
This project aims to analyze and track student performance in exam sessions using BigQuery. By processing data from two main tables (`exams` and `exam_sessions`), the system calculates actual student marks, classifies results, ranks top performers, and tracks performance trends across exams.

## Key Features
- **Actual Marks Calculation**: Compute actual marks based on correct and incorrect answers.
- **Pass/Fail Classification**: Determine if a student passes or fails based on the calculated marks and pass mark.
- **Top Performers**: Rank the top 5 students based on actual marks for each exam.
- **Performance Trend**: Track performance improvements or declines for each student across multiple exams.

## Technologies Used
- **Google BigQuery**: For querying and analyzing the data.
- **SQL**: To perform data operations like joins, calculations, and window functions.
- **Google Sheets**: Used for easy data handling and uploading into BigQuery.
