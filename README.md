# Amazon-Data-Analysis
"Amazon Sales Data Analysis and Predictive Modeling"
This project involves analyzing Amazon sales data and developing predictive models to forecast future sales.
Based on the document provided, here's a summary of the project involving data analysis using Python in 3 key points:

1. Data Preprocessing and Exploratory Data Analysis (EDA):
   - The project used Python libraries like Pandas, NumPy, Matplotlib, and Seaborn for data manipulation and visualization.
   - It involved importing data, handling null values, changing data types, and adding new columns for analysis.
   - EDA included creating box plots to detect outliers in Total Profit, Total Cost, and Total Revenue, as well as generating bar charts and calculating correlations between key variables.

2. Predictive Analytics:
   - The project implemented label encoding for categorical variables like Item Type, Sales Channel, and Order Priority to prepare the data for model training.
   - It utilized the PyCaret library, an open-source machine learning library in Python, to build, compare, and deploy machine learning models efficiently.
   - The analysis included plotting residuals and prediction errors for a Lasso Least Angle Regression model.

3. Linear Regression Implementation:
   - The project involved selecting independent variables and a target variable, splitting the data into training and testing sets, and standardizing the dataset.
   - A Linear Regression model was applied to the training data, and its performance was evaluated using mean squared error.
   - The results were visualized using a kernel density estimate plot and by plotting predicted values against actual values to assess the model's fit.
