## College Attendance Analytics System

This project is made to analyze college attendance data using Python.
It calculates attendance percentage, finds low attendance students, and shows the result using a bar chart.
A simple UI is created using Gradio.

## What this project does

-> Takes attendance data in CSV file
-> Calculates attendance percentage
-> Finds students with attendance below 75%
-> Shows attendance trend using bar chart
-> Uses Roll Number on X-axis 
-> Provides a simple user interface using Gradio

## Technologies Used

-> Python
-> Pandas
-> Matplotlib
-> Gradio

## Dataset Format

RollNo,Name,Total_Classes,Attended_Classes
101,Aarav Sharma,180,165
102,Vivaan Verma,180,140

## Visualization

-> Bar Chart
  -> X-axis → Roll Number
  -> Y-axis → Attendance Percentage
-> Helps to easily see attendance trends
-> Low attendance students can be identified clear

## Algorithm Used

Threshold-Based Attendance Analysis Algorithm
Formula Used
 -> Attendance % = (Attended_Classes / Total_Classes) × 100

## How to Run the Project

Step 1: Install libraries
-> pip install pandas matplotlib gradio

Step 2: Run the program
-> interface.launch()

Step 3:Visualization
-> Upload the attendance CSV file
-> View results, low attendance list, and bar chart

-------------------------------------------------------------------------------------------------THANK YOU-----------------------------------------------------------------------------------------------------------
