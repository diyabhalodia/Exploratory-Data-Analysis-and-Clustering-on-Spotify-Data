# Exploratory-Data-Analysis-and-Clustering-on-Spotify-Data

## 📌 Project Overview
This project focuses on exploratory data analysis (EDA), clustering, and visualization of Spotify track audio features to uncover meaningful music patterns and listener-oriented insights.  
Using unsupervised learning, tracks were grouped into distinct music clusters such as High Energy Dance, Acoustic/Chill, and Moody tracks, followed by an interactive Power BI dashboard for storytelling.

---

## 🎯 Objectives
- Perform data cleaning and EDA on Spotify audio feature data  
- Identify patterns and relationships between audio characteristics  
- Apply clustering techniques to segment tracks based on musical attributes  
- Create intuitive Power BI dashboards  
- Translate analytical results into business-friendly insights  

---

## 🗂️ Dataset Description
Spotify tracks dataset containing:

### 🎧 Audio Features
- Danceability  
- Energy  
- Valence  
- Tempo  
- Loudness  
- Acousticness  
- Instrumentalness  
- Speechiness  
- Liveness  

### 📊 Metadata
- Popularity  
- Genre  
- Duration  

---

## 🧹 Data Cleaning & Preprocessing
- Removed missing and duplicate values  
- Converted duration from milliseconds to minutes  
- Scaled numerical features for clustering  
- Selected relevant audio features for analysis  
- Prepared final dataset for Power BI  

---

## 📈 Exploratory Data Analysis (EDA)
- Distribution analysis of audio features  
- Correlation analysis between musical attributes  
- Popularity comparison across genres  
- Feature trends across music clusters  

---

## 🤖 Clustering Approach
- Applied K-Means clustering on scaled audio features  
- Used the Elbow Method (WCSS) to determine optimal number of clusters  
- Assigned meaningful cluster names based on musical characteristics  

### 🎶 Identified Music Clusters
- High Energy Dance / Pop Tracks  
- Fast-Paced Party Tracks  
- Acoustic / Chill Songs  
- Low Energy / Moody Tracks  

---

## 📊 Power BI Dashboard Highlights
Interactive dashboard built to explore music insights:

### 🔑 KPIs
- Total Tracks  
- Average Popularity  
- Total Clusters  
- Top Genre  

### 📉 Visuals Used
- Bar Chart: Average Popularity by Music Cluster  
- Line Chart: Average Audio Features by Cluster  
- Scatter Plot (Mood Map): Energy vs Danceability by Cluster  
- Stacked Bar Chart: Track Distribution by Genre & Cluster  
- Slicers: Cluster Name, Genre  

---

## 🧠 Key Insights
- High-energy and fast-paced tracks show higher popularity  
- Acoustic and chill tracks have lower energy but balanced valence  
- Music mood segmentation is clearly visible through clustering  
- Audio features strongly influence listener engagement  

---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)  
- Google Colab  
- Power BI  
- GitHub  

---


