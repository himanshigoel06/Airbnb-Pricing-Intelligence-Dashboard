# 🏡 Airbnb-Pricing-Intelligence-Dashboard

A dynamic and interactive Power BI dashboard designed to analyze Airbnb listing performance, pricing drivers, and customer demand patterns across global markets.

---

## 📌 1. Short Description / Purpose

The **Staylytics Dashboard** is a visually engaging Power BI report that enables users to explore Airbnb listings, understand pricing behavior, and analyze customer demand trends. It helps uncover how factors like location, room type, and ratings impact pricing and engagement.

---

## 🛠️ 2. Tech Stack

The dashboard was built using the following tools and technologies:<br>

• 📊 **Power BI Desktop** – Main data visualization platform used for report creation.<br>
• 📂 **Power Query** – Data transformation and cleaning layer.<br>
• 🧠 **DAX (Data Analysis Expressions)** – Used for calculated measures, KPIs, and logic.<br>
• 🔗 **Data Modeling** – Relationships between Listings & Reviews tables.<br>
• 📁 **File Format** – `.pbix` for development and `.png` for dashboard previews.<br>

---

## 📊 3. Data Source

**Source:** Maven Analytics – Airbnb Listings & Reviews Dataset  
🔗 https://mavenanalytics.io/data-playground/airbnb-listings-reviews  

The dataset includes:

- **Listings Data** → price, location, room type, ratings, availability  
- **Reviews Data** → reviewer behavior, review frequency, timestamps  

This combination enables both **Supply (Listings)** and **Demand (Reviews)** analysis.

---

## 🚀 4. Features / Highlights

### 💼 Business Problem

The Airbnb marketplace generates massive amounts of data, but extracting meaningful insights about pricing trends, customer demand, and market performance is challenging without structured visualization.

Key questions include:
- What drives Airbnb pricing across cities?
- How does customer demand change over time?
- Which locations dominate listings and reviews?

---

### 🎯 Goal of the Dashboard

To build an interactive dashboard that:

- Analyzes Airbnb pricing drivers  
- Tracks demand trends using review data  
- Compares performance across cities and room types  
- Supports data-driven decision-making  

---

### 📊 Walkthrough of Key Visuals

#### 🔹 Page 1: Overview (Pricing & Demand)

- **KPI Cards**
  - Avg Price  
  - Avg Rating  
  - Total Listings  
  - Reviews per Listing (Demand Indicator)  

- **Supply vs Demand Trend (Line Chart)**
  - Compares listing growth with review activity over time  

- **Price by Room Type (Bar Chart)**
  - Entire Home, Private Room, Shared Room comparison  

- **Geographic Distribution (Map)**
  - City-wise listing concentration  

- **Price vs Rating (Scatter Plot)**
  - Relationship between pricing and customer ratings  

---

#### 🔹 Page 2: Ratings Analysis

- **City-wise Rating Heatmap**
  - Accuracy, Cleanliness, Communication, Location, Value  

- **Top & Bottom Performing Cities**
  - Identify best and worst-rated markets  

---

#### 🔹 Page 3: Reviews & Customer Behavior

- **Review Frequency Distribution**
  - Majority users leave only 1 review  

- **Cumulative % Analysis**
  - ~98% users review ≤ 3 times  

- **Seasonality Trends**
  - Monthly demand patterns  

- **Trust Indicators**
  - Verified vs non-verified profiles  

---

### 📈 Business Impact & Insights

- 💰 **Pricing Strategy**
  - Entire homes command higher prices, but ratings do not always correlate with pricing  

- 📊 **Demand Trends**
  - Review activity reflects increasing user engagement over time  

- 🌍 **Market Insights**
  - Few cities dominate listings and demand  

- 👤 **User Behavior**
  - Most users show low repeat engagement  

---

## 🖼️ 5. Screenshots / Demos

### 📊 Overview Dashboard
https://github.com/himanshigoel06/Airbnb-Pricing-Intelligence-Dashboard/blob/main/Overview%20of%20Airbnb.png

### ⭐ Ratings Dashboard
https://github.com/himanshigoel06/Airbnb-Pricing-Intelligence-Dashboard/blob/main/Rating%20of%20Airbnb.png

### 📝 Reviews Dashboard
https://github.com/himanshigoel06/Airbnb-Pricing-Intelligence-Dashboard/blob/main/Reviews%20of%20Airbnb.png

---

## 📌 6. Project Structure
