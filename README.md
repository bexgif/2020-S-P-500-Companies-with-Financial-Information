# 2020-S-P-500-Companies-with-Financial-Information

This project is a Jupyter Notebook-based financial data analysis tool, focusing on exploring and analysing financial statistics for a collection of companies. The notebook reads financial data from a CSV file and uses popular data analysis and visualisation libraries, including Pandas, Matplotlib, and Seaborn, to derive insights. Below is a summary of the key functionalities and analyses included in the project.

### Overview
The project begins by loading a dataset containing financial metrics for various companies, such as stock prices, earnings, and market capitaliastion. The data is imported from a CSV file and presented in a tabular format for preliminary inspection. The dataset includes columns such as "Symbol," "Name," "Sector," "Price," "Price/Earnings," "Dividend Yield," "52 Week Low," "52 Week High," "Market Cap," and "EBITDA."

### Key Features
Data Summary: The first step in the analysis involves generating a summary of the dataset's statistics using descriptive statistics functions. This provides an overview of central tendencies, variability, and the range for key metrics, such as stock prices, earnings per share, and market capitalization.

Price-to-Sales Distribution: A histogram is created to illustrate the distribution of the Price/Sales ratio across different companies. This helps identify whether most companies have similar Price/Sales ratios or if there is significant variability in the data.

Dividend Yield Analysis: Another histogram is generated to show the distribution of dividend yields. This analysis also highlights the companies offering the highest dividend yields, making it easy to identify high-dividend-paying stocks.

52-Week High and Low Comparison: The project calculates the percentage difference between the current stock price and the 52-week high and low. This comparison allows for the identification of companies trading close to their yearly peaks or troughs, which could indicate potential buying or selling opportunities.

### Technologies Used
Pandas: For data manipulation and analysis.
Matplotlib and Seaborn: For data visualization, creating histograms, and other charts.
Jupyter Notebook: As the environment for writing and executing Python code.
