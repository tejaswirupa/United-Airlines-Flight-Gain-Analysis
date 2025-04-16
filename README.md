Analyzing United Airlines Flights from NYC: Efficiency & Gain Insights

📌 Overview:
This project explores the time efficiency of United Airlines (UA) flights departing from New York City using the nycflights13 dataset. The main objective is to quantify gain per flight — the time recovered or lost — using exploratory data analysis, hypothesis testing, and confidence intervals.

🎯 Objectives:
Analyze the difference in net gain for flights that departed on time vs. late.

Identify the top 5 destination airports for UA flights and compare gain distributions.

Calculate gain per hour for late vs. on-time, very late vs. not very late, and short vs. long flights.

Use statistical inference (t-tests, CIs) to validate findings.

🧪 Methods:
Data Wrangling & Feature Engineering (e.g., net_gain, gain_per_hour)

Visualizations (boxplots, bar plots)

Confidence Intervals & Hypothesis Testing

Group-wise Comparisons (late vs. on-time, flight duration groups)

🗂️ Key Insights:
Significant gain differences were observed between late and on-time departures.

Shorter flights showed significantly higher average gain per hour compared to longer ones.

Top destinations like SFO and ORD had the highest average gain, but CIs overlapped.

📂 Tools Used:
R, tidyverse, nycflights13

Statistical analysis using t.test()

Visualizations using ggplot2
