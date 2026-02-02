# 📊 Netflix Content Analysis & Visualization – Python (Pandas + Matplotlib)

## 🔷 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on Netflix’s content dataset using **Python, Pandas, and Matplotlib**.

The objective is to transform raw streaming data into **clear visual insights** that help answer business questions like:

- Does Netflix have more Movies or TV Shows?
- Which ratings dominate the platform?
- What is the average movie duration?
- Which countries produce the most content?
- How has content grown over the years?

## 🔷 Dataset

**File:** `netflix_titles.csv`

Contains:

- Title
- Type (Movie / TV Show)
- Release Year
- Rating
- Country
- Duration
- Genre

## 🔷 Step-by-Step Analysis

### 🎬 Movies vs TV Shows Distribution
- Counted number of Movies and TV Shows
- Visualized using bar chart

📈 Insight: Helps understand Netflix’s primary content focus

### 🔞 Content Rating Distribution
- Calculated rating frequency (TV-MA, TV-14, PG, etc.)
- Visualized using pie chart

📈 Insight: Shows platform targets mostly mature audience

### ⏱ Movie Duration Analysis
- Cleaned "duration" column
- Converted to numeric minutes
- Created histogram of movie lengths

📈 Insight: Reveals most common movie length range

### 📅 Release Year Trend
- Counted titles released per year
- Plotted scatter chart

📈 Insight: Shows growth of Netflix content over time

### 🌍 Top 10 Countries by Content
- Grouped data by country
- Selected top 10
- Horizontal bar chart

📈 Insight: Identifies major content-producing regions

### 📈 Movies vs TV Shows Over Time
- Grouped by release year + type
- Created side-by-side line plots

📈 Insight:
- Compare growth of Movies vs TV Shows
- Understand long-term content strategy

## 🔷 Data Cleaning Steps

- Removed null values from important columns
- Filtered incomplete records
- Converted duration text to integers
- Structured data for analysis

## 🔷 Tech Stack

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

  ## 👨‍💻 Author

**Parth Inamdar**  
Aspiring Data Analyst

LinkedIn: https://www.linkedin.com/in/parthinamdar/
