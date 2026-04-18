# 📊 YouTube Channel Data Analytics using Python & MongoDB

## 📌 Project Overview
This project focuses on analyzing YouTube channel performance using real-time data.  
We extract channel statistics using the YouTube Data API, store the data in MongoDB Atlas, and perform analysis using Python.

The goal is to compare different YouTube channels and understand factors influencing their growth and engagement.

---

## 🎯 Objectives
- Extract real-time YouTube channel data
- Store data in MongoDB Atlas
- Perform data cleaning and transformation
- Analyze key metrics such as:
  - Subscriber Count
  - Total Views
  - Video Count
- Generate visualizations for comparison
- Derive insights on channel performance

---

## 🛠️ Tools & Technologies Used
- Python
- YouTube Data API v3
- MongoDB Atlas (NoSQL Database)
- Pandas (Data Processing)
- Matplotlib (Data Visualization)
- Google Colab

---

## 📂 Dataset
The dataset consists of selected YouTube channels:
- Saskatchewan Polytechnic
- IRCC (Immigration, Refugees and Citizenship Canada)
- Royal Challengers Bangalore (RCB)
- Cristiano Ronaldo
- Google

Data fields:
- Channel Title
- Subscriber Count
- View Count
- Video Count

---

## 🔄 Project Workflow

1. **Data Extraction**
   - Used YouTube API to fetch channel data

2. **Data Cleaning**
   - Converted numeric values
   - Handled missing data

3. **Data Storage**
   - Stored cleaned data in MongoDB Atlas

4. **Data Analysis**
   - Used Pandas for processing
   - Created new features:
     - Average Views per Video
     - Subscribers per Video

5. **Data Visualization**
   - Bar charts for comparison
   - Scatter plots for relationships

---

## 📊 Key Insights
- Cristiano Ronaldo has the highest subscribers due to strong personal branding
- Google has the highest total views due to large content volume
- RCB has the highest video uploads, indicating consistent posting
- More videos do not always lead to more subscribers
- Content quality and engagement are key drivers of success

---

## ⚠️ Challenges Faced
- API key generation and authentication
- Extracting correct channel IDs
- MongoDB connection and network access configuration
- Data type conversion for analysis
- Handling visualization clarity issues

---

## 📈 Future Improvements
- Include more YouTube channels
- Perform sentiment analysis on comments
- Use advanced visualization tools (Seaborn / Plotly)
- Build a dashboard for real-time analysis

---

## 👨‍💻 Author
- Group 4 Project
- Course: Data Analytics / COMP 603

---

## 📎 Conclusion
This project demonstrates how Python and MongoDB can be used to build a complete data analytics pipeline.  
It highlights the importance of data-driven decision-making in understanding digital platform performance.

---
