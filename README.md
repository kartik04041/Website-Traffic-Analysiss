# 📊 Website Traffic Analysis – Alfido Tech

## 🚀 Project Overview

This project analyzes website traffic logs to understand user behavior, session patterns, landing pages, exit pages, bounce rates, referral sources, and user journeys.

The goal is to extract actionable insights and provide data-driven recommendations to improve conversions for Alfido Tech.

---

## 📂 Dataset

Source: Kaggle – Website Traffic Analysis Dataset  

The dataset contains raw activity logs with the following fields:

- event  
- date  
- country  
- city  
- artist  
- album  
- track  
- isrc  
- linkid  

For analysis purposes:

- linkid → User ID  
- event → Page  
- date → Timestamp  
- country → Referral Source  

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🧹 Data Processing Steps

### 1️⃣ Data Cleaning
- Removed duplicate records
- Handled missing values
- Converted timestamps to datetime format
- Sorted data by user and time

### 2️⃣ Session Creation
- Implemented 30-minute inactivity rule
- Generated session IDs per user

### 3️⃣ Metrics Computed
- Total Users
- Total Sessions
- Bounce Rate
- Average Session Duration
- Top Landing Pages
- Top Exit Pages
- Referral Source Analysis
- Page Transition (User Flow)

---

## 📊 Key Metrics

### 👤 Total Users
Number of unique users visiting the website.

### 🔁 Total Sessions
Total number of browsing sessions created using the 30-minute rule.

### 📉 Bounce Rate
Percentage of sessions with only one page view.

Bounce Rate =  
(Single Page Sessions / Total Sessions) × 100

### ⏱️ Average Session Duration
Average time users spend per session.

---

## 📈 Visualizations

- Bar chart of top landing pages
- Bar chart of top exit pages
- Referral source traffic distribution
- Most common page transitions

---

## 🔍 Insights Generated

- Identified high-bounce pages
- Detected major drop-off points
- Analyzed traffic quality by referral source
- Mapped common user navigation paths

---

## 💡 Business Recommendations

1. Optimize high-bounce landing pages.
2. Improve call-to-action placement on top exit pages.
3. Focus marketing budget on high-engagement referral sources.
4. Improve internal linking to reduce drop-offs.
5. Use personalized content recommendations to increase session duration.

---

## 📦 Project Structure

