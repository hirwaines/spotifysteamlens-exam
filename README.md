# spotifysteamlens-exam
# 🎧 Streaming Smarter: Analyzing Spotify Listening Patterns for Personal and Platform Optimization

Capstone Project – INSY 8413: Introduction to Big Data Analytics  
**Student:** HIRWA Ines  
**ID**:25870
**Dataset:** Spotify Streaming History  

---

## 📌 Project Description

This project uses a Spotify streaming history dataset to uncover behavioral patterns in music consumption. The central issue addressed is the lack of visibility into how users interact with the platform  when they listen, what they skip, and who they listen to most. By analyzing this behavior, the project helps optimize user experience, suggesting smarter recommendations and more personalized content. Economically, it benefits **users** by reducing time spent on unwanted tracks, **artists** by surfacing engagement trends that can guide content production and promotion, and **Spotify owners** by enhancing algorithm performance, boosting user retention, and improving ad targeting or subscription value.

---

## 🎯 Objective

Identify and analyze streaming behavior over time to:
- Discover peak listening hours
- Detect most and least engaged artists
- Understand skip frequency and shuffle usage
- Offer meaningful insights for listeners, artists, and app developers

---

## 🛠️ Tools Used
- Python (pandas, seaborn, matplotlib, sklearn)
- Power BI
- GitHub(for submission)
**1. Python**
Python was used as the primary programming language for data processing and exploratory analysis. It offers powerful libraries and flexibility, making it ideal for handling structured data like the Spotify streaming history.

Key Contributions:

Data cleaning (handling null values, renaming columns, fixing timestamp formats)

Feature engineering (extracting listening hours, session IDs, day of week)

Exploratory data analysis (EDA) through plotting and descriptive statistics

Clustering (unsupervised machine learning) to discover listening behavior patterns

Libraries used:

pandas – for data manipulation and cleaning

numpy – for mathematical operations

matplotlib and seaborn – for data visualization

scikit-learn – for clustering and evaluation with KMeans and silhouette score

**2. Power BI**
Power BI was used for interactive data visualization. While Python is great for analysis, Power BI excels at communication — making insights accessible, visual, and explorable.

Key Contributions:

Created dynamic dashboards with slicers and filters

Built visuals like bar charts, line graphs, and time-based summaries

Allowed non-technical users (e.g., instructors or stakeholders) to understand patterns in the data

Why Power BI?

Easy integration with CSV exports from Python

Interactive filters help focus on specific artists, albums, or time periods

Business intelligence-grade design that’s ideal for reporting and decision-making

**3. GitHub**
GitHub was used as a version-controlled platform to organize and submit all files related to the project, including code, data, visuals, and documentation.

Key Contributions:

Shared the entire capstone project with structure and clarity

Hosted files like Jupyter notebooks, Power BI dashboard, and presentation

Demonstrated best practices in project delivery and transparency
---

## 🧪 Python Analytics
- **Data cleaning:** Handled missing values, converted timestamps, created time features
- **EDA:** Explored trends by hour, day, artist, and session
- **Session Detection:** Defined sessions based on 30-minute listening gaps
- **Exported Data:** Cleaned and summarized datasets ready for Power BI

---

## 📊 Power BI Dashboard
<img width="959" height="509" alt="Capture" src="https://github.com/user-attachments/assets/7f8f51d2-eba8-4d8a-a9a0-0d799b845e6a" />

### 1. 🎶 Count of Shuffle by Album
- **What it shows:** Albums most often played in shuffle mode.
- **Insight:** Preference for familiar full albums while multitasking or relaxing.
- **Example:** "Past Masters" and "The Beatles" dominate shuffle counts.

### 2. ⏭️ Track Play vs Skipped (by Track Name)
- **What it shows:** Which tracks were played the most and which were skipped.
- **Insight:** Tracks with high skip rates despite frequent plays may not be engaging or might indicate playlist padding.
- **Use:** Helps Spotify and artists fine-tune future releases or recommendations.

### 3. 👤 Listening Frequency by Artist
- **What it shows:** Total plays by artist.
- **Insight:** Strong artist loyalty (e.g., *The Killers*, *John Mayer*) indicates repeat listening behavior.
- **Use:** Informs platform algorithms for artist-specific push content or concert recommendations.

### 4. 📅 Listening & Skipping by Day
- **What it shows:** Daily patterns of listening time and skipping activity.
- **Insight:** Higher skipping occurs on high listening days — indicating users explore more when they listen longer.
- **Use:** Spotify could send curated playlists during peak listening days.

### 🔍 Filters
- Artist Name
- Album Name
- Date Hierarchy (Year, Quarter, Month)

