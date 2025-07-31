# -Blinkit-Data-Analysis-project-Python
Blinkit Data Analysis
This repository hosts a comprehensive data analysis project focused on Blinkit's sales performance, customer satisfaction, and inventory distribution. Developed using Python, this project aims to extract actionable insights and visualize key trends, which can then be integrated into a Power BI dashboard for strategic decision-decision-making.

Project Overview
The primary goal of this project is to conduct an in-depth analysis of Blinkit's operational data. By examining sales, customer feedback, and inventory metrics, the project seeks to identify critical patterns, performance drivers, and areas for optimization. The insights derived from this analysis are designed to inform business strategies and enhance overall efficiency.

Business Requirements
The project was guided by specific business requirements to ensure the analysis addressed key operational questions. These requirements included the calculation of essential Key Performance Indicators (KPIs) and the creation of targeted data visualizations.

KPI Requirements:

Total Sales: Calculate the aggregate revenue generated from all items sold.

Average Sales: Determine the average revenue per individual sale transaction.

Number of Items: Ascertain the total count of distinct items that have been sold.

Average Rating: Compute the average customer satisfaction rating across all products.

Chart Requirements:
The following visualizations were specifically requested to provide clear insights into different aspects of the business:

Total Sales by Fat Content: To analyze the impact of an item's fat content (e.g., 'Low Fat', 'Regular') on its total sales.

Total Sales by Item Type: To identify which categories of items (e.g., 'Fruits and Vegetables', 'Snack Foods') contribute most significantly to total sales.

Fat Content by Outlet for Total Sales: To compare sales performance across different outlet locations, specifically segmenting by the fat content of items sold.

Total Sales by Outlet Establishment Year: To evaluate how the age of an outlet (its establishment year) correlates with its total sales performance.

Sales by Outlet Size: To analyze the relationship between an outlet's physical size (e.g., 'Small', 'Medium', 'High') and its total sales volume.

Sales by Outlet Location Type: To assess the geographical distribution of sales, categorizing outlets by their location tiers (e.g., 'Tier 1', 'Tier 2', 'Tier 3').

Data and Methodology
The project utilizes a dataset (blinkit_data.csv) containing various attributes related to Blinkit's sales. The data processing pipeline involved:

Data Loading: Importing the .csv file into a Pandas DataFrame.

Initial Inspection: Reviewing the first and last few rows, checking data dimensions (df.shape), column names (df.columns), and data types (df.dtypes). The dataset contains 8,523 rows and 12 columns.

Data Cleaning: A critical step involved standardizing the 'Item Fat Content' column. Inconsistent entries like "LF", "low fat", and "reg" were mapped to "Low Fat" and "Regular" to ensure data uniformity and accurate categorical analysis.

KPI Calculation: Calculating the required business KPIs (Total Sales, Average Sales, Number of Items Sold, Average Rating) directly from the cleaned dataset.

Visualization Generation: Creating various charts using matplotlib.pyplot and seaborn to graphically represent the data and insights, adhering to the specified chart types.

Key Findings (KPIs)
The initial analysis of the dataset yielded the following overall performance metrics:

Total Sales: $1,201,681.5

Average Sales: $141.0

Number of Items Sold: 8,523

Average Rating: 4.0

Technologies Used
Python: The primary programming language for data analysis.

Pandas: Used for data manipulation and analysis.

Numpy: Utilized for numerical operations.

Matplotlib: Employed for creating static, animated, and interactive visualizations.

Seaborn: A data visualization library based on matplotlib, providing a high-level interface for drawing attractive and informative statistical graphics.
