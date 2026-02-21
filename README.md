# CodeAlpha_Covid-Unemployeement-Analysis
This project analyzes unemployment rate data before and after the Covid-19 pandemic to understand its economic impact. The objective is to explore unemployment trends, identify regional differences, detect seasonal patterns, and generate insights that can inform economic and social policy decisions.

The analysis is performed using Python with data cleaning, exploratory data analysis (EDA), and visualization techniques.

🎯 Objectives

Analyze unemployment rate trends over time

Compare unemployment before and after Covid-19

Identify peak unemployment periods

Explore region-wise unemployment impact

Detect seasonal patterns in unemployment

Provide policy-relevant insights

🛠️ Tools & Technologies Used

Python

Pandas

NumPy

Matplotlib

Jupyter Notebook

📂 Dataset Description

The dataset contains monthly unemployment data including:

Region

Date

Estimated Unemployment Rate (%)

Estimated Employed

Estimated Labour Participation Rate (%)

The data was divided into:

Pre-Covid period

During/Post-Covid period

Both datasets were cleaned and concatenated for analysis.

🧹 Data Cleaning Steps

Removed fully null rows

Standardized column names

Handled duplicate columns after concatenation

Dropped constant columns (e.g., Frequency)

Converted Date column to datetime format

Removed unnecessary features (latitude, longitude where not required)

Reset index and ensured structural consistency

📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

1️⃣ Overall Unemployment Trend

Visualized unemployment rate over time

Identified Covid impact spike

Observed recovery patterns

2️⃣ Before vs After Covid Comparison

Compared average unemployment rates

Measured pandemic impact magnitude

3️⃣ Region-wise Analysis

Identified most affected regions

Compared regional disparities

4️⃣ Seasonal Trend Analysis

Analyzed unemployment variation by month

Detected recurring patterns

5️⃣ Correlation Analysis

Studied relationship between:

Unemployment Rate

Labour Participation Rate

Employment Count

📈 Key Insights

Unemployment rate sharply increased during early Covid months.

Certain regions were more severely impacted.

Gradual recovery observed post-pandemic peak.

Seasonal patterns exist in unemployment fluctuations.

Labour participation rate shows inverse relationship with unemployment.

💡 Policy Implications

Government job schemes should target high-risk months.

Regional employment programs should focus on heavily impacted areas.

Economic stimulus planning must consider seasonal unemployment spikes.

🚀 Future Improvements

Add interactive dashboards using Plotly or Power BI

Perform predictive modeling (Time Series Forecasting)

Build Machine Learning model to predict unemployment trends

👨‍💻 Author

Siddhesh Limje
Aspiring Data Analyst | Python • SQL • Data Visualization
Open to Data Analyst and Internship Opportunities
