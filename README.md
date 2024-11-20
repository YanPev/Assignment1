# Assignment 1: Animal Data Analysis

Welcome to Assignment 1! This assignment is designed to help you practice data analysis and processing. 
You will answer a series of questions by implementing the required functions in the provided template file.


# Objectives
	1.	Analyze and process data using Python.
	2.	Apply statistical methods to extract insights.

# Dataset
The dataset for this assignment is located at data/BDL_2023_EX1.mat. This .mat file contains:
	•	Headers: The column names of the dataset.
	•	Data Table: Animal attributes such as weight, height, and cuteness score.
	•	Animal Type Table: Categories of animals.
	•	Animal Names: Names of the animals.

 # Questions to Solve
	1.	Remove the Outlier:
Identify the outlier we discussed in class and provide its serial number.
	2.	Mean and Variance:
Calculate the mean and variance of the weights for animals with a cuteness score of 4.
Output Format: <mean weight>, <variance> (no units).
	3.	Median and MAD:
Calculate the median weight and median absolute deviation (MAD) for animals with a cuteness score of 4.
Output Format: <median weight>, <MAD> (no units).
	4.	Gender Analysis:
Determine whether there are more males or females among animals with a cuteness score of 3 or lower.
	•	Males = 0, Females = 1, Others = 2.
	5.	Animal Type with Highest Cuteness:
Identify the animal type with the highest average cuteness score.
Output Format: Write the name of the category, not the index.
	6.	Closest to Mean Weight:
Find the name of the animal whose weight is closest to the mean. If there are two, write the one with the higher serial number.
	7.	Shortest Animal:
Identify the shortest animal and write its name.
	8.	Add a New Animal:
Add a new animal to the dataset. Provide its name, type, weight, and height.
	9.	Comparison to Mean:
Compare the new animal’s weight to the original mean (difference in tons and standard deviations).
Output Formats:
	•	<difference in tons>
	•	<difference in standard deviations>
	10.	Height Comparison:
Compare the new animal’s height to the original median height (in centimeters).
	11.	Suggest New Data:
Suggest two new types of categorical and numerical data to collect about the animals.
	12.	Correlation:
Calculate the correlation (rho) between:
	•	Height and weight.
	•	Height and cuteness score.

# Instructions
