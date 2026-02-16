# uber-rides-data-analysis
Uber Rides Data Analysis Project
Project Overview
This project involves a comprehensive exploratory data analysis (EDA) of Uber ride data from 2016. The primary goal is to extract meaningful insights regarding travel patterns, trip purposes, and distance distributions to better understand user behavior and ride efficiency.

Dataset Description
The analysis is performed on the UberDataset.csv, which contains 1,156 entries and 7 columns:

START_DATE: The date and time the ride began.

END_DATE: The date and time the ride ended.

CATEGORY: The type of ride (e.g., Business vs. Personal).

START: The starting location.

STOP: The destination location.

MILES: The distance traveled in miles.

PURPOSE: The reason for the trip (e.g., Meeting, Meal, Customer Visit).

Key Features & Preprocessing
To improve the quality of the analysis, the following preprocessing steps were conducted:

Handling Missing Values: Missing entries in the PURPOSE column were filled with the placeholder "NOT" to maintain data integrity.

Datetime Transformation: Converted START_DATE and END_DATE into datetime objects for precise temporal analysis.

Feature Engineering:

Extracted the specific date and hour of each trip.

Created a Day-Night categorical column, segmenting rides into 'Morning', 'Afternoon', 'Evening', and 'Night'.

Data Cleaning: Removed duplicate entries and handled null values in the location and category fields.

Analysis Highlights
The notebook explores several key business questions:

Ride Categories: Comparison between Business and Personal trips.

Top Locations: Identification of the most frequent starting and ending points (e.g., Fort Pierce, West Palm Beach).

Distance Metrics: Analysis of average miles per trip.

Temporal Patterns: Understanding how ride demand fluctuates based on the time of day and between weekdays and weekends.

Tech Stack
Python: Core programming language.

Pandas & NumPy: Data manipulation and numerical calculations.

Matplotlib & Seaborn: Data visualization and plotting.
