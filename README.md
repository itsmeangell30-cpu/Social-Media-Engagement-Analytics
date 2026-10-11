📱 Social Media Engagement Analytics Using Python

📊 Data Cleaning | Exploratory Data Analysis | Statistical Analysis | Data Visualization

📌 Project Overview

This project focuses on analyzing social media engagement data using Python to understand content performance, audience behavior, user interactions, and engagement trends.

The analysis uses the dataset social_media_engagement_5000.csv to explore metrics such as likes, comments, shares, impressions, watch time, engagement rate, and followers.

Using Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Plotly, this project transforms raw social media data into meaningful insights that can support data-driven decision-making.

🎯 Project Objectives
🧹 Clean and preprocess the dataset.
🔍 Explore the structure and quality of the data.
📊 Perform exploratory data analysis (EDA).
🔢 Calculate descriptive statistics for important metrics.
🔄 Transform data and create new analytical features.
📈 Visualize engagement patterns and relationships.
👥 Understand audience demographics and behavior.
🌎 Compare engagement across countries and content categories.
💬 Analyze sentiment and its relationship with engagement.
💡 Generate actionable insights based on the analysis.
📂 Dataset Description

Dataset name: social_media_engagement_5000.csv

The dataset contains approximately 5,000 social media records, as indicated by the provided filename.

The analysis focuses on engagement metrics, content characteristics, user demographics, and audience behavior.

📋 Key Variables
❤️ likes — Number of likes received by a post.
💬 comments — Number of comments received.
🔁 shares — Number of times content was shared.
👁️ impressions — Number of times content was displayed.
⏱️ watch_time — Time users spent watching content.
📈 engagement_rate — Engagement rate associated with a post.
👥 followers — Number of followers associated with an account.
📝 post_type — Type of social media content.
🗂️ category — Content category.
🌍 country — Country associated with the record.
😊 sentiment — Sentiment label, such as positive, neutral, or negative.
👤 gender — Gender category.
🎂 age — Age of the user.
✅ verified — Verification status of an account.
📱 device — Device type used by the audience.
#️⃣ hashtags — Hashtags associated with a post, if available.
📅 date / timestamp — Date or time of the post, if available.

Note: The exact column names may vary. Verify them using df.columns and adjust the notebook code accordingly.

🛠️ Tools and Technologies
🐍 Python — Main programming language.
🐼 Pandas — Data manipulation and cleaning.
🔢 NumPy — Numerical calculations and data transformations.
📊 Matplotlib — Creating charts and visualizations.
🎨 Seaborn — Statistical data visualization.
📈 Plotly — Interactive charts.
☁️ Google Colab — Cloud-based notebook environment.
📓 Jupyter Notebook — Interactive Python development environment.
📥 Task 1: Data Import and Setup

The dataset is imported and prepared for analysis.

📂 Import the CSV file using Pandas.
👀 Inspect the first and last few records.
📐 Check the number of rows and columns.
🏷️ Review the column names.
🔍 Inspect data types and dataset structure.
📅 Convert date and timestamp columns to datetime format.
✅ Verify that the dataset is ready for analysis.
🧹 Task 2: Data Cleaning
🔎 Missing Value Handling
Identify missing values using isnull() and isna().
Calculate the number of missing values in each column.
Remove incomplete records using dropna() when appropriate.
Fill missing numerical values using median or other suitable methods.
Fill missing categorical values using the mode.
Apply forward-fill or backward-fill when appropriate for ordered data.
Recheck missing values after cleaning.
🔁 Duplicate Handling
Identify duplicate records using duplicated().
Count duplicate rows.
Remove duplicates using drop_duplicates().
Verify the dataset after duplicate removal.
🏷️ Data Formatting
Correct inappropriate data types.
Standardize categorical labels such as gender and sentiment.
Check for inconsistent capitalization and extra spaces.
Identify unrealistic values in likes, comments, and shares.
Validate age, followers, impressions, and engagement rate.
Check numerical columns for invalid or impossible values.
#️⃣ Feature Cleaning
Extract hashtag counts from hashtag text where available.
Standardize sentiment labels.
Handle empty or invalid hashtag entries.
Ensure categorical labels are consistent.
🔍 Task 3: Data Exploration Using Pandas

The dataset is explored using Pandas functions.

head() — Display the first five records.
tail() — Display the last five records.
shape — Check the number of rows and columns.
columns — Display column names.
info() — Inspect column types and non-null counts.
dtypes — Review data types.
describe() — Generate descriptive statistics.
value_counts() — Analyze categorical distributions.
unique() — Identify distinct category values.
nunique() — Count unique values.
corr() — Calculate correlations between numerical variables.
groupby() — Summarize metrics across categories.
📊 Grouping and Aggregation
❤️ Calculate average likes by post type.
👁️ Compare impressions across countries.
📈 Calculate average engagement rates by category.
💬 Summarize comments and shares by sentiment.
👥 Compare engagement metrics across demographic groups.
📱 Analyze watch time by device type.
🔄 Task 4: Data Wrangling and Feature Engineering

Data wrangling prepares the dataset for deeper analysis.

🔗 Use merge(), concat(), or join() if multiple DataFrames are available.
➕ Create an engagement_score feature using suitable engagement metrics.
#️⃣ Calculate hashtag counts from hashtag text.
📉 Apply logarithmic transformations to highly skewed metrics when useful.
📊 Group data by post_type, country, and sentiment.
🧮 Aggregate metrics using mean, sum, count, and median.
🧹 Validate newly created features.

Example engagement score:

engagement_score = likes + comments + shares

This is a simple interaction score. It does not replace engagement rate, and the formula should be adapted if the assignment specifies a different definition.

📐 Task 5: Statistical Analysis

Descriptive statistics are calculated for the following variables:

❤️ Likes
💬 Comments
🔁 Shares
⏱️ Watch time
📈 Engagement rate
👥 Followers
🔢 Statistical Measures
📊 Mean — Average value.
📍 Median — Middle value.
🏷️ Mode — Most frequent value.
📉 Standard deviation — Measures variability.
🔢 Variance — Measures squared deviations from the mean.
📏 Percentiles — Describe the distribution at selected thresholds.
📈 Skewness — Measures distribution asymmetry.
🔔 Kurtosis — Describes distribution tails and concentration.

These measures help identify typical engagement levels, variation, and unusual observations.

📊 Task 6: Data Visualization

The project includes visualizations using Matplotlib, Seaborn, and Plotly.

📈 Matplotlib Visualizations

1. 🔗 Scatter Plot — Likes vs. Impressions

Examines the relationship between likes and impressions.
Helps determine whether greater visibility is associated with more likes.

2. 📅 Line Chart — Daily Engagement Trend

Tracks engagement over time.
Identifies increases, decreases, and possible patterns.

3. 🗂️ Bar Chart — Posts by Category

Compares the number of posts in each category.
Identifies frequently used content categories.

4. 🥧 Pie Chart — Gender Distribution

Displays the distribution of gender categories.
Helps summarize the demographic composition of the dataset.

5. 🎂 Histogram — Age Distribution

Shows the distribution of user ages.
Identifies common age ranges and potential outliers.

6. 📦 Box Plot — Engagement Rate

Displays the median and spread of engagement rates.
Highlights possible outliers.
🎨 Seaborn Visualizations

7. 🚻 Count Plot — Post Type

Compares the number of records for each post type.
Shows the distribution of content formats.

8. ❤️ Bar Plot — Average Likes by Category

Compares average likes across content categories.
Helps evaluate category-level performance.

9. 🎻 Violin Plot — Followers vs. Sentiment

Compares follower distributions across sentiment groups.
Shows differences in distribution shape and spread.

10. 🔍 Pair Plot — Numerical Features

Explores pairwise relationships between numerical variables.
Helps identify patterns, correlations, and outliers.

11. 🌡️ Heatmap — Correlation Matrix

Visualizes correlations between numerical variables.
Highlights positive and negative relationships.

12. 📱 Swarm Plot — Engagement vs. Device

Compares engagement values across device types.
Shows individual observations and their distribution.
📈 Plotly Interactive Visualization

13. 🖱️ Interactive Chart

Create an interactive line, bar, bubble, or scatter chart using Plotly.

🔎 Explore data points interactively.
🖱️ Hover over observations to view values.
📊 Compare metrics across categories.
📈 Investigate engagement patterns dynamically.

Note: The assignment requires at least eight plots. The visualizations listed above provide a broader plan that covers the requested chart types.

💡 Task 7: Final Insights and Business Questions
📝 Content Performance
🚀 Which post types have the highest engagement?
🗂️ Which content category receives the highest average likes?
🌍 Which countries have the highest average engagement rates?
👁️ How are impressions related to likes and shares?
👥 User Trends
🎂 How does age relate to engagement?
✅ Do verified accounts show different engagement patterns?
👥 How does follower count relate to post performance?
📱 Do audience characteristics vary across devices?
🕒 Behavioral Insights
⏰ What time of day is associated with the highest impressions?
📱 How does device type relate to watch time?
🔁 Which content receives more shares?
💬 What patterns appear in comments and other interactions?
😊 Sentiment Analysis
😊 Which sentiment group has the highest average engagement?
😐 How do neutral posts perform?
😞 How do negative-sentiment posts perform?
💬 Does sentiment relate to likes, comments, and shares?

The answers should be based on actual calculations and visualizations rather than assumptions.

📌 Task 8: Key Findings and Recommendations

The final report should summarize the most important results.

🏆 Identify content formats associated with stronger engagement.
📊 Highlight categories with higher average likes.
🌎 Compare engagement rates across countries.
👥 Describe differences between verified and unverified accounts.
⏰ Identify time periods associated with higher impressions, if timestamp data is available.
📱 Summarize differences in watch time by device.
😊 Compare engagement across sentiment groups.
💡 Recommend potential improvements to content strategy based on the observed data.

Important: Populate this section with measured results after running the analysis. Do not report a category, country, sentiment, or device as the best performer without supporting evidence.

📦 Deliverables
📓 Complete Python notebook (.ipynb).
🧹 Data cleaning and preprocessing code.
🔍 Exploratory data analysis.
📐 Statistical analysis and calculations.
📊 Required visualizations with outputs.
📝 Explanations for code and charts.
💡 A one-page summary of findings.
🔗 A shareable notebook link with View access, if required.
📁 A GitHub repository containing the project files.
🚀 How to Run the Project
Option 1: Google Colab
Open Google Colab.
Upload the assignment notebook.
Upload social_media_engagement_5000.csv.
Run the notebook cells in sequence.
Review the outputs, visualizations, and findings.
Share the notebook with View access if required.
Option 2: Jupyter Notebook
Clone or download the GitHub repository.
Place the dataset in the appropriate folder.
Open Jupyter Notebook.
Install the required libraries.
Open the .ipynb file.
Execute the cells in order.
Save the notebook with outputs.
📦 Installation

Install the required Python libraries using:

pip install pandas numpy matplotlib seaborn plotly jupyter


Note: Adjust the folder names and filenames to match your actual repository. Avoid uploading sensitive or restricted data.

🏁 Conclusion

This project demonstrates a complete Python-based data analysis workflow, from data import and cleaning to statistical analysis and visualization.

By examining engagement metrics, audience demographics, content types, geographic patterns, device usage, and sentiment, the project helps explain how social media performance can be evaluated using data.

The project provides practical experience with Pandas, NumPy, Matplotlib, Seaborn, and Plotly while developing skills in exploratory data analysis, feature engineering, visualization, and evidence-based reporting.

👨‍💻 Author
👤 Name: Angel 
Project: Social Media Engagement Analytics Using Python

📊 Domain: Data Analytics

🐍 Language: Python
