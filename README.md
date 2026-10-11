📱 Social Media Engagement Analytics Using Python

📊 Data Cleaning | EDA | Statistical Analysis | Visualization

🎯 Project Overview

This project analyzes social media engagement data using Python.

🧹 Clean and preprocess raw data.

📊 Analyze likes, comments, shares, and impressions.

👥 Explore audience behavior and demographics.

📈 Visualize trends and engagement patterns.

💡 Generate data-driven insights.

📂 Dataset

File: social_media_engagement_5000.csv

The dataset contains approximately 5,000 records.

❤️ likes — Likes received by posts.

💬 comments — Comments received.

🔁 shares — Content shares.

👁️ impressions — Content views or displays.

⏱️ watch_time — Time spent watching content.

📈 engagement_rate — Engagement rate.

👥 followers — Follower count.

📝 post_type — Type of post.

🗂️ category — Content category.

🌍 country — Country.

😊 sentiment — Sentiment label.

🎂 age — User age.

📱 device — Device type.

✅ verified — Account verification status.



🛠️ Tools and Technologies

🐍 Python

🐼 Pandas

🔢 NumPy

📊 Matplotlib

🎨 Seaborn

📈 Plotly

☁️ Google Colab

📓 Jupyter Notebook


🧹 Task 1: Data Import and Cleaning

📥 Import the CSV file using Pandas.

🔍 Inspect rows, columns, and data types.

📅 Convert date columns to datetime.

🧩 Detect and handle missing values.

🔁 Identify and remove duplicates.

🏷️ Standardize categorical values.

✅ Correct invalid numerical values.

#️⃣ Extract hashtag counts where available.


🔎 Task 2: Exploratory Data Analysis

👀 Use head() and tail().

📐 Check dataset dimensions using shape.

🏷️ Inspect columns using columns.

🔍 Review data using info() and dtypes.

📊 Generate statistics using describe().

🗂️ Explore categories using value_counts().

🔢 Identify unique values using unique() and nunique().

🌡️ Calculate numerical correlations.

📈 Summarize data using groupby().


🔄 Task 3: Data Wrangling

🔗 Combine datasets using merge(), concat(), or join().

➕ Create an engagement_score feature.

#️⃣ Calculate hashtag counts.

📉 Apply log transformations when appropriate.

🌍 Group metrics by country.

📝 Compare post types and sentiment groups.


📐 Task 4: Statistical Analysis

Analyze likes, comments, shares, watch time, engagement rate, and followers.


📊 Mean and median.

🏷️ Mode.

📉 Standard deviation and variance.


📏 Percentiles.

📈 Skewness and kurtosis.


📊 Task 5: Data Visualization

📈 Matplotlib

🔗 Scatter plot: Likes vs. impressions.

📅 Line chart: Daily engagement trends.

🗂️ Bar chart: Posts by category.

🥧 Pie chart: Gender distribution.

🎂 Histogram: Age distribution.

📦 Box plot: Engagement rate.


🎨 Seaborn

🚻 Count plot: Post type.

❤️ Bar plot: Average likes by category.

🎻 Violin plot: Followers vs. sentiment.

🔍 Pair plot: Numerical features.

🌡️ Heatmap: Correlation matrix.

📱 Swarm plot: Engagement vs. device.


🖱️ Plotly

📈 Create an interactive line, bar, bubble, or scatter chart.

🔎 Explore data points using interactive hover information.


💡 Task 6: Key Business Questions

🏆 Which post types have the highest engagement?

🗂️ Which category receives the highest average likes?

🌍 Which countries have the highest average engagement rate?

🎂 How does age relate to engagement?

✅ Do verified accounts perform differently?

⏰ When are impressions highest?

📱 How does device type affect watch time?

😊 Which sentiment group has the highest engagement?



📦 Project Deliverables

📓 Complete Python notebook with code and outputs.

🧹 Data cleaning and preprocessing.

📊 Statistical analysis and visualizations.

📝 Explanations for code and charts.

💡 One-page summary of findings.

🔗 Notebook shared with View access, if required.

🚀 Installation and Usage

Install the required libraries:

pip install pandas numpy matplotlib seaborn plotly jupyter


Import the libraries and load the dataset:

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px

df = pd.read_csv("social_media_engagement_5000.csv")
print(df.head())

📁 Project Structure
Social-Media-Engagement-Analytics/
├── data/
│   └── social_media_engagement_5000.csv
├── notebooks/
│   └── Social_Media_Engagement_Analytics.ipynb
├── outputs/
├── reports/
├── requirements.txt
└── README.md

🏁 Conclusion

This project demonstrates data cleaning, exploratory data analysis, statistical analysis, and visualization using Python.

It explores social media content performance, audience behavior, engagement trends, and sentiment.

The final findings will help identify patterns and support data-driven recommendations.

👨‍💻 Author
👤 Name: Angel
