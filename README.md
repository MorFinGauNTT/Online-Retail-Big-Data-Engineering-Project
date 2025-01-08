# Online Retail Big Data Engineering Project


# Introduction
This project presents a detailed analysis of an online retail dataset obtained from Kaggle. Using Apache Spark and PySpark in Google Colab, we explored the dataset to uncover key insights about sales performance. The main goals of this project are:

Identifying the top 10 most sold products.
Determining the top 10 countries with the highest sales.
Visualizing these insights using Pandas and Matplotlib.
The project demonstrates how Big Data tools like Apache Spark can efficiently process and analyze large datasets, alongside Python libraries for visualization.

# Data Overview
The dataset is a transactional record of online retail operations and includes:

InvoiceNo: Unique identifier for invoices.
StockCode: Product code.
Description: Product description.
Quantity: Number of units sold.
InvoiceDate: Date and time of the transaction.
UnitPrice: Price per unit.
CustomerID: Unique customer identifier.
Country: Country of the customer.
# Key Findings
1. Top 10 Most Sold Products
Identified the most popular products based on their total quantity sold.
Visualized results using a bar chart for easy interpretation.
2. Top 10 Countries by Sales
Analyzed the dataset to find countries with the highest total sales volume.
Visualized the distribution of sales across the top countries using a bar chart.
# Visualizations
The project includes clear and informative visualizations:

Bar Chart: Showcasing the top 10 most sold products.
Bar Chart: Displaying the top 10 countries by sales volume.(You can reach to graphs via report.pdf)
These visualizations help highlight the key insights obtained from the dataset.

# Implementation Details
Environment: Google Colab with Apache Spark and PySpark for Big Data processing.
Libraries:
PySpark: Data manipulation and analysis.
Matplotlib: Creating visualizations.
Pandas: Data wrangling and exploration.
# Workflow:
Loaded the dataset into a PySpark DataFrame.
Conducted transformations and aggregations to derive insights.
Exported results to Pandas for visualization with Matplotlib.
# Conclusion
This project showcases how Big Data tools like Apache Spark can efficiently analyze large datasets and uncover valuable business insights. The combination of PySpark for data processing and Python libraries for visualization demonstrates the power of hybrid approaches in data analysis.

# Author
Osman Altunbağ

# Acknowledgements
Special thanks to Kaggle for providing the dataset and to all the contributors to the open-source tools used in this project.
