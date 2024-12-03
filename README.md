# Introduction-to-Machine-Learning-Team-Project-Fall-2024

Preprocessing Steps
1. Feature Selection
Removed columns vin and saledate as they do not directly contribute to price prediction.
2. Handling Missing Values
Numeric columns: Missing values replaced with column mean.
Columns: year, condition, odometer, mmr, sellingprice.
Categorical columns: Missing values replaced with "unknown".
3. Encoding Categorical Data
Converted all object-type columns into numerical values using Label Encoding.
Data Visualization
The following visualizations were used to understand the data distribution and relationships:

Histogram: Visualized the distribution of selling prices.
Scatter Plot: Displayed the relationship between odometer readings and selling prices.
Correlation Matrix: Analyzed relationships between numeric features.
Box Plot: Highlighted central tendencies and outliers for selling prices.
Usage
This dataset can be used to:

Predict car prices using machine learning algorithms.
Analyze the factors influencing car prices.
Acknowledgments
This preprocessing and analysis were performed as part of the CSE4288 Data Science Course Project, Group 11, Fall 2024.

For questions or further details, refer to the accompanying report
************************************************************************************************************
