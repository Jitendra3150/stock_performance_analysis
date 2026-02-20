📈 Stock Market Performance Analysis Dashboard
📌 Project Overview

This project focuses on analyzing historical stock market data to understand price trends, returns, and risk. The analysis was performed using Python for data processing, MySQL for structured data storage, and Power BI for interactive visualization.

The project converts raw stock data into meaningful insights to support better understanding of stock performance.

🎯 Objectives

Analyze historical stock price movements

Calculate daily, monthly, and yearly returns

Measure stock volatility and risk

Store processed data in MySQL

Create an interactive Power BI dashboard

Present financial insights in a visual format

🛠️ Tools & Technologies

Python (Pandas, NumPy, Matplotlib, seaborn)

MySQL (Database Management)

Power BI (Dashboard Development)


📊 Dataset

Source: Kaggle

Format: CSV

Time Period: 1977 – 2020

Columns:

Date

Open

High

Low

Close

Adjusted Close

Volume

🗄️ Database Implementation (MySQL)

A MySQL database was created to store cleaned stock data.

Tables were designed with appropriate data types.

Data was inserted into MySQL .

SQL queries were used for filtering and aggregation.

This helped in managing data efficiently and improving accessibility.

🐍 Data Analysis (Python)

Using Python, the following steps were performed:

Data loading and preprocessing

Handling missing values

Date conversion and sorting

Feature creation:

Daily Returns

Moving Averages (MA20, MA50)

Volatility

Exploratory Data Analysis (EDA)

Example:

df['Daily_Return'] = df['Adj Close'].pct_change() * 100
df['MA20'] = df['Adj Close'].rolling(20).mean()
📈 Dashboard Development (Power BI)

The Power BI dashboard includes:

🔹 KPIs

Average Daily Return

Volatility

Average Trading Volume

🔹 Visualizations

Price Trend with Moving Averages

Monthly Returns Analysis

Yearly Returns Analysis


🔹 Features

Date slicer for filtering


📌 Key Insights

Identified long-term bullish and bearish trends

Highlighted high-risk periods

Observed seasonal performance patterns

Analyzed relationship between price and volume



📄 Results

Developed a complete stock analysis system

Generated meaningful financial indicators

Built an interactive dashboard

Improved understanding of stock performance and risk

🔮 Future Scope

Add multiple stock comparison

Automate data updates

Implement prediction models

Cloud database integration

👤 Author

Jitendra Walunj
GitHub: https://github.com/Jitendra3150
