#  AI Sales Intelligence Dashboard

An end-to-end **Sales Analytics and Demand Forecasting** project built using Python. This project analyzes retail sales data to uncover business insights, identify profitable products, evaluate customer behavior, measure operational performance, and predict future product demand using Machine Learning.

##  Project Overview

Businesses generate massive amounts of sales data every day. Turning this data into actionable insights helps organizations improve profitability, optimize inventory, reduce returns, and make better strategic decisions.

This project performs comprehensive exploratory data analysis (EDA), business intelligence reporting, and demand forecasting on an Amazon retail sales dataset.

##  Objectives

* Analyze sales performance over time.
* Identify seasonal sales trends.
* Discover high-performing and low-performing product categories.
* Compare sales and profit across states and cities.
* Analyze customer segments and shipping modes.
* Study product return patterns.
* Predict future product demand using Machine Learning.

##  Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

##  Dataset

The dataset contains Amazon retail sales information, including:

* Order Date
* Ship Date
* Sales
* Profit
* Quantity
* State
* City
* Category
* Sub-Category
* Customer Segment
* Ship Mode
* Payment Mode
* Returns

##  Project Workflow

### 1. Data Cleaning

* Checked missing values
* Removed duplicate records
* Validated shipping dates
* Converted date columns into datetime format
* Renamed inconsistent column names

### 2. Exploratory Data Analysis

Performed analysis on:

* Monthly Sales Trend
* Yearly Sales Trend
* Seasonal Heatmap
* Product-wise Sales & Profit
* State-wise Sales
* City-wise Sales
* Product Return Analysis
* Region-wise Returns
* Customer Segment Profitability
* Shipping Mode Profitability
* Payment Mode Analysis

##  Machine Learning

### Demand Forecasting

A Random Forest Regressor was trained to forecast future monthly demand using historical sales information.

### Features Used

* Month
* Previous Month Demand (Lag-1)
* Lag-2
* Lag-3
* Rolling Mean (3 Months)

##  Key Business Insights

### Sales Trends

* Strong seasonal demand observed during September, November, and December.
* Phones remained consistently strong sellers throughout the year.
* Binder sales increased significantly toward year-end.

### Product Performance

* Chairs generated high revenue but comparatively low profit.
* Tables showed negative profitability.
* Copiers produced high profit despite relatively lower sales volume.

### Geographic Analysis

* California generated the highest sales.
* New York ranked second in revenue.
* Top-performing cities included:

  * Los Angeles
  * New York City
  * San Francisco
  * Seattle
  * Chicago

### Returns Analysis

* Binders recorded the highest number of returns.
* Copiers maintained strong sales with relatively low returns.
* California experienced the largest number of returned orders.

### Customer Analysis

* Customer segments contributed differently to total profit.
* Standard shipping generated the highest overall profit.
* Same-day shipping produced comparatively lower profitability.

##  Business Recommendations

* Increase inventory before festive seasons.
* Focus marketing efforts on high-performing states and cities.
* Re-evaluate pricing strategy for low-profit products such as Tables.
* Reduce return rates for Binders through quality checks.
* Promote Standard Shipping whenever possible to improve profitability.
* Expand sales of high-margin products like Copiers.

##  Visualizations

This project includes visualizations such as:

* Line Charts
* Heatmaps
* Bar Charts
* Pie Charts
* Comparative Sales vs Profit Charts

##  Repository Structure

```
AI-Sales-Intelligence-Dashboard/
│
├── ai_sales.ipynb
├── Amazon Store Sales Data.xlsx
├── README.md
├── requirements.txt
├── images/
│   ├── monthly_sales.png
│   ├── yearly_sales.png
│   ├── heatmap.png
│   ├── sales_by_state.png
│   ├── returns.png
│   └── demand_prediction.png
└── insights_report.pdf
```

##  Installation

```bash
git clone <repository-link>

cd AI-Sales-Intelligence-Dashboard

pip install -r requirements.txt
```

##  Run the Project

Open the notebook:

```bash
jupyter notebook ai_sales.ipynb
```

Run all cells sequentially.

##  Future Improvements

* Interactive Power BI Dashboard
* Tableau Dashboard
* Time Series Forecasting using Prophet or LSTM
* Customer Segmentation using RFM Analysis
* Sales Recommendation System
* Inventory Optimization

##  Conclusion

This project demonstrates how exploratory data analysis and machine learning can be combined to transform raw retail sales data into actionable business intelligence. The insights generated can support strategic decisions related to inventory planning, product management, logistics, customer targeting, and demand forecasting.

##  Author

**Snigdha**

Data Analytics | Machine Learning | Python 
