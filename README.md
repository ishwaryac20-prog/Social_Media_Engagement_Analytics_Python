# 📊 Social Media Engagement Data Analysis Using Python

## 📌 Project Overview

This project presents an end-to-end **Social Media Data Analysis** using Python. The analysis focuses on understanding social media content performance, audience engagement, user behavior, posting patterns, device usage, and sentiment.

The project uses **Pandas, NumPy, Matplotlib, Seaborn, and Plotly** to perform data import, cleaning, exploratory data analysis, data wrangling, statistical analysis, and visualization.

The objective is to transform raw social media data into meaningful insights that can support **data-driven content and audience analysis**.

---

## 🎯 Objectives

The main objectives of this project are to:

* 📥 Import and inspect the social media dataset
* 🧹 Clean and preprocess the data
* 🔎 Explore numerical and categorical variables
* 🔄 Perform data wrangling and feature engineering
* 📈 Perform statistical analysis
* 📊 Create meaningful visualizations
* 💡 Identify important social media engagement patterns
* 📱 Analyze device-wise user behavior
* 😊 Analyze sentiment-based engagement
* ⏰ Identify posting times associated with higher impressions
* 📝 Generate a final summary of key dataset findings

---

## 🛠️ Technologies & Libraries Used

| Technology      | Purpose                        |
| --------------- | ------------------------------ |
| 🐍 Python       | Programming and analysis       |
| 🐼 Pandas       | Data manipulation and analysis |
| 🔢 NumPy        | Numerical operations           |
| 📊 Matplotlib   | Data visualization             |
| 🎨 Seaborn      | Statistical visualization      |
| 📈 Plotly       | Interactive visualizations     |
| ☁️ Google Colab | Notebook execution environment |

---

# 📂 Assignment Tasks

## 🟢 Task 1 — Data Import & Setup

The dataset is imported using Pandas and initially inspected to understand its structure.

### Activities Covered

* Import CSV dataset
* Display initial records
* Check dataset shape
* Check column names
* Inspect data types
* Identify date/time columns
* Convert valid date columns to datetime
* Ensure numerical fields remain numeric

---

## 🟢 Task 2 — Data Cleaning

Data cleaning is performed to improve data quality and prepare the dataset for analysis.

### Activities Covered

* Detect missing values using:

  * `isnull()`
  * `isna()`
* Analyze missing-value counts
* Handle missing values using appropriate methods
* Identify duplicate records
* Remove duplicate records
* Correct incorrect data types
* Standardize categorical values
* Clean sentiment labels
* Correct unrealistic values in:

  * Likes
  * Comments
  * Shares
* Extract hashtag counts from post content
* Preserve watch-time/duration fields as numeric values

---

## 🟢 Task 3 — Data Exploration Using Pandas

Exploratory Data Analysis is performed to understand the characteristics of the dataset.

### Pandas Exploration

The following methods are used:

```python
head()
tail()
shape
columns
info()
dtypes
describe()
```

### Categorical Analysis

Categorical variables are explored using:

```python
value_counts()
unique()
nunique()
```

### Correlation Analysis

A correlation matrix is generated to understand relationships between numerical variables.

### GroupBy Analysis

Group-based summaries are performed for areas such as:

* Average likes by post type
* Engagement by category
* Impressions by country
* Engagement by sentiment
* Device-wise watch time

---

# 🟢 Task 4 — Data Wrangling

Data wrangling is performed to prepare the dataset for deeper analysis.

### Activities Covered

* Create derived analytical columns
* Calculate **Engagement Score**
* Calculate **Hashtag Count**
* Extract posting hour where a valid time field is available
* Group data by:

  * Post Type
  * Category
  * Country
  * Sentiment
  * Device
* Combine DataFrames where required using merge/concat/join concepts

### 📌 Engagement Score

An engagement score is created using available social-media interaction metrics such as:

* Likes
* Comments
* Shares

The derived metric provides a consolidated measure for comparing content engagement.

---

# 🟢 Task 5 — Statistical Analysis

Descriptive statistical analysis is performed on the available numerical metrics.

### Metrics Analyzed

* ❤️ Likes
* 💬 Comments
* 🔄 Shares
* ⏱️ Watch Time
* 📈 Engagement Rate
* 👥 Followers

### Statistical Measures

The analysis includes:

* Mean
* Median
* Mode
* Standard Deviation
* Variance
* Percentiles
* Skewness
* Kurtosis

These measures help understand the central tendency, variability, and distribution of social media metrics.

---

# 🟢 Task 6 — Data Visualization

Multiple visualization techniques are used to identify trends and relationships in the dataset.

## 📊 Matplotlib Visualizations

The project includes visualizations such as:

1. 🔵 Likes vs Impressions — Scatter Plot
2. 📈 Daily Engagement Trend — Line Plot
3. 📊 Posts by Category — Bar Chart
4. 🥧 Gender Distribution — Pie Chart
5. 📊 Age Distribution — Histogram
6. 📦 Engagement Rate Distribution — Box Plot

---

## 🎨 Seaborn Visualizations

The project includes:

1. 📊 Post Type Distribution — Count Plot
2. 📊 Average Likes by Category — Bar Plot
3. 🎻 Followers vs Sentiment — Violin Plot
4. 🔗 Numeric Feature Relationships — Pair Plot
5. 🔥 Correlation Matrix — Heatmap
6. 📱 Engagement vs Device — Swarm Plot

---

## 📈 Plotly Visualizations

Interactive Plotly charts are also included where the required fields are available.

Examples include:

* Interactive engagement trends
* Interactive category comparisons
* Interactive likes/impressions analysis
* Bubble/scatter visualizations

---

# 💡 Final Insights

The final analysis summarizes important findings from the dataset.

### 🎯 Content Performance

The analysis identifies:

* Highest-engagement post type
* Best-performing category
* Highest-average-engagement country
* Engagement differences across content types

### 👥 User Trends

The analysis explores:

* Age and engagement relationship
* Verified vs non-verified account performance
* Follower-related engagement patterns

### ⏰ Behavioral Analysis

The project investigates:

* Best time of day for impressions
* Device-wise watch-time behavior
* Posting-time patterns
* Engagement behavior across devices

### 😊 Sentiment Analysis

The analysis compares:

* Positive sentiment
* Neutral sentiment
* Negative sentiment

and identifies differences in engagement across sentiment categories.

---

# 📋 Final Summary Table

The notebook generates a final summary table containing dataset-based findings such as:

| Analysis Area                      | Dataset Finding        |
| ---------------------------------- | ---------------------- |
| Highest-engagement post type       | Generated from dataset |
| Best-performing category           | Generated from dataset |
| Highest-average-engagement country | Generated from dataset |
| Highest-engagement sentiment       | Generated from dataset |
| Highest-watch-time device          | Generated from dataset |
| Best time of day for impressions   | Generated from dataset |

The findings are calculated dynamically from the dataset rather than being manually entered.

# 🏁 Conclusion

This project demonstrates a complete **Python-based Data Analytics workflow** using a social media dataset.

The analysis progresses from:

**Data Import → Data Cleaning → Data Exploration → Data Wrangling → Statistical Analysis → Visualization → Insights**

By combining Pandas, NumPy, Matplotlib, Seaborn, and Plotly, the project demonstrates how raw social media data can be transformed into meaningful analytical insights related to **content performance, audience engagement, user behavior, sentiment, posting patterns, and device usage**.

---

## 👩‍💻 Author

**Hema Ishwarya C**
