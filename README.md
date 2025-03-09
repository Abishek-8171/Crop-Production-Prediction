# Crop-Production-Prediction
This project analyzes agricultural data to predict crop production by examining key factors such as area harvested, crop types, and regional variations. It utilizes data visualization and machine learning models (regression) to provide accurate predictions and insights.
## Data collection
![Screenshot (39)](https://github.com/user-attachments/assets/97a2ff36-1e9e-41d6-ba6a-6077e2f9f05e)
## Data preprocessing for Exploratory Data Analysis(EDA) 
### Handling Null values
### Dropping unwanted columns
### DataFrame Transformation (Rows → Columns)
![Screenshot (41)](https://github.com/user-attachments/assets/2dbdc181-815f-43cf-8da7-0c19ab49d029)
## Transferring Data to SQL
![Screenshot (48)](https://github.com/user-attachments/assets/5d115f96-dce0-4586-9c72-000b37871116)
## Exploratory Data Analysis(EDA) 
### Analyze Crop Distribution
Crop Types: we analyze the Item column to identify the most and least cultivated crops across regions using a plotly barchart.\
Geographical Distribution: This process aims to analyze the Area column to identify the Areas that specialize in specific crops or have high agricultural activity using the scatter_geo chart.\
### Temporal Analysis
Yearly Trends & Growth Analysis: This process involves analyzing the Year column to detect trends in Area Harvested, Yield, and Production over time, as well as identifying growth patterns in specific regions using a line chart.\
### Input-Output Relationships
In this process, using a seaborn heatmap chart, the correlation between Area harvested, Yield, and Production has been analyzed.\
### Comparative Analysis
Across Crops::This process focuses on comparing the Yield of different crops (from the Item column) to identify high-yield and low-yield crops using a bar chart.\
Across Regions: This process focuses on comparing Production across different regions to identify highly productive regions using a bar chart.\
Productivity Analysis: This analysis focuses on examining Yield variations to identify high-yield crops and productive regions.\
###Outliers detection
In this process, outliers present in the Area Harvested, Yield, and Production columns were filtered and stored in a variable. all the values are a part of the whole process because these
values are correlated between each column.
### Machine Learning
## Data preprocessing for Machine Learning
# Encoding columns 
![Screenshot (42)](https://github.com/user-attachments/assets/4ed66553-a3d1-477d-a890-33d2cbc7d400)
# Data splitting
![Screenshot (43)](https://github.com/user-attachments/assets/45ce749d-c765-4a5a-90c3-ba68b2eaf67b)
# Regression models









