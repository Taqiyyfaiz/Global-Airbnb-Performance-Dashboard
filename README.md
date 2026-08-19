# Global-Airbnb-Performance-Dashboard

An interactive Power BI dashboard designed to analyze Airbnb performance across 10 major global cities, with a focus on listings, reviews, pricing, ratings, seasonality, and host trust.

---

## 📌 Short Description / Purpose

The **Global Airbnb Performance Dashboard** is an interactive Power BI report that provides a comprehensive view of Airbnb's performance across 10 global cities.

The dashboard analyzes key aspects of the Airbnb marketplace, including **listing growth, market share, room-type pricing, customer reviews, city-level ratings, seasonal review patterns, and host trust signals**. The objective is to transform Airbnb data into clear and actionable insights that can help users understand market concentration, customer behavior, listing performance, and differences across cities.

---

## 🛠️ Tech Stack

The dashboard was built using the following tools and technologies:

* 📊 **Power BI Desktop** – Main data visualization and dashboard development platform.
* 📂 **Power Query** – Used for data cleaning, transformation, and preparation.
* 📈 **Data Visualization** – Used to create KPI cards, combo charts, bar charts, line charts, heatmaps, and other analytical visuals.
* 🧠 **Data Analysis & Calculations** – Used to aggregate and compare listings, reviews, prices, ratings, and other performance metrics.
* 📁 **File Format** – `.pbix` for the Power BI dashboard and `.png` for dashboard previews.

---

## 📂 Data Source

**Source:** Maeven Analytics

The dataset contains Airbnb-related information used to analyze listings, hosts, reviews, pricing, ratings, room types, and other marketplace characteristics across 10 global cities.

The data was prepared and transformed using **Power Query** before being used to build the dashboard and its analytical visuals.

---

# ⭐ Features / Highlights

## 🔎 Business Problem

Airbnb operates across a wide range of cities and property types, generating large amounts of data related to listings, hosts, customer reviews, prices, and ratings.

However, raw marketplace data can make it difficult to quickly answer questions such as:

* Which cities have the largest Airbnb markets?
* How concentrated are listings and reviews across cities?
* How do prices differ by room type?
* Which cities receive the highest customer ratings?
* How frequently do customers leave reviews?
* Does review activity change throughout the year?
* What trust signals are present among Airbnb hosts?
* How has Airbnb listing activity changed over time?

The dashboard was developed to bring these different dimensions together into a single interactive analytical view.

---

## 🎯 Goal of the Dashboard

The goal of the dashboard is to provide an interactive visual tool that:

* Enables users to compare Airbnb performance across major global cities.
* Highlights listing growth and market concentration.
* Compares average prices across different room types.
* Evaluates customer ratings across multiple dimensions.
* Analyzes customer review frequency and seasonality.
* Examines host identity verification and profile-picture signals.
* Identifies patterns and differences between Airbnb markets.
* Converts complex marketplace data into easily understandable insights.

---

# 📊 Walkthrough of Key Visuals

## 1. Overview & New Listings

The Overview page provides a high-level snapshot of the Airbnb dataset through key performance indicators:

* **2,797,712 Listings**
* **10 Cities**
* **182,024 Hosts**
* **144 Property Types**
* **5.373M Reviews**

The **New Listings** trend visual tracks listing activity from 2008 to 2021 and divides the timeline into different stages of Airbnb's development, including introduction, growth, maturity, decline, reinvention, and the COVID-19 period.

The visualization highlights the strong increase in Airbnb listings during the early and mid-2010s, followed by a decline in listing activity around 2020.

---

## 2. Market Share by City

The **Market Share by City** analysis compares Airbnb listings across the 10 cities included in the dataset.

The visual combines:

* Superhost listings
* Non-Superhost listings
* Cumulative percentage

The analysis shows that **Paris, New York, and Sydney account for almost half of the total listings and 48% of total reviews**, demonstrating a significant concentration of Airbnb activity among the largest markets.

The analysis also highlights **Paris as the city with the highest number of listings and reviews** within the analyzed markets.

---

## 3. Average Price by Room Type

The average-price comparison shows differences in Airbnb pricing across room types:

| Room Type    | Average Price |
| ------------ | ------------: |
| Hotel Room   |          $800 |
| Entire Place |          $673 |
| Shared Room  |          $580 |
| Private Room |          $462 |

The visualization shows that **hotel rooms and entire-place listings have higher average prices**, while private rooms have the lowest average price among the room types shown.

This allows users to quickly compare pricing differences across accommodation types.

---

## 4. Overall Ratings

The **Overall Ratings** visualization compares average ratings across the 10 cities.

The cities are ranked from lower to higher average rating, with:

* Hong Kong — **89.7**
* Istanbul — **91.1**
* Bangkok — **93.0**
* Paris — **93.1**
* Sydney — **93.2**
* Rome — **93.5**
* New York — **93.8**
* Cape Town — **94.4**
* Rio de Janeiro — **94.6**
* Mexico City — **94.8**

Based on the analyzed data, **Mexico City and Rio de Janeiro have the highest overall average ratings**, while **Hong Kong and Istanbul have the lowest** among the cities included.

---

## 5. Detailed Ratings

The Detailed Ratings view provides a deeper comparison of city performance across five rating dimensions:

* ⭐ Accuracy
* 🧹 Cleanliness
* 💬 Communication
* 📍 Location
* 💰 Value

The heatmap allows users to compare individual rating categories across cities rather than relying only on an overall rating.

This makes it easier to identify specific areas where cities perform relatively strongly or weakly.

---

## 6. Review Frequency

The **Review Frequency** analysis examines how many reviews individual customers leave.

The dashboard shows that:

* **86.5%** of reviewers left one review.
* **98.8%** of reviewers left three reviews or fewer.

The distribution demonstrates that review activity is highly concentrated among low-frequency reviewers.

The dashboard also identifies an unusual case involving a customer who left **283 reviews**, highlighting a potential outlier in the dataset.

---

## 7. Seasonality

The **Seasonality** visualization examines monthly review activity across selected cities.

The analysis highlights differences in review patterns throughout the year.

Key observations include:

* **Paris and Rome** show stronger review activity from approximately April through August.
* **New York** shows increased review activity during November and December, coinciding with the holiday period.

This visualization helps identify seasonal differences in customer activity across markets.

---

## 8. Host Trust

The **Trust** analysis examines two host-related trust signals:

* Identity verification
* Profile picture availability

The dashboard shows four combinations of these characteristics:

* Identity verified + profile picture
* Identity verified + no profile picture
* Identity not verified + profile picture
* Identity not verified + no profile picture

The largest segment represents hosts who have **both an identity-verified profile and a profile picture**, accounting for **66.9%** of the analyzed data.

This provides an overview of how common different host trust signals are within the dataset.

---

# 💡 Business Impact & Insights

### 🌎 Market Concentration

Airbnb activity is concentrated among a relatively small number of major global cities. Paris, New York, and Sydney represent a substantial proportion of listings and reviews within the analyzed markets.

### 💰 Pricing Differences

Average prices vary considerably by room type. Hotel-room and entire-place listings have higher average prices than private-room listings.

### ⭐ Customer Ratings

Mexico City and Rio de Janeiro have the highest overall average ratings among the analyzed cities, while Hong Kong and Istanbul rank lower.

### 📝 Review Behavior

Most customers leave reviews infrequently. The large majority of reviewers leave only one or a small number of reviews, with a small number of users generating unusually high review counts.

### 📅 Seasonal Activity

Review activity varies across months and cities. European markets such as Paris and Rome show stronger activity during the spring and summer period, while New York shows increased activity toward the end of the year.

### 🤝 Host Trust

Identity verification and profile-picture availability are common trust signals within the dataset, with the largest group of hosts having both signals present.

### 📈 Listing Growth

Airbnb experienced substantial listing growth during the 2010s, followed by a significant decline around 2020. The decline occurs during the same period as the COVID-19 pandemic.

---

# 📸 Screenshots / Dashboard Preview

## Overview Page

![Overview Dashboard](<img width="509" height="383" alt="Overview Page" src="https://github.com/user-attachments/assets/2b7fd96c-2433-4a38-bd71-7b561aa540a6" />
)

The overview page presents the main KPIs and the historical development of Airbnb listings.

---

## Market Share & Ratings

![Market Share and Ratings](<img width="518" height="388" alt="Overall Ratings" src="https://github.com/user-attachments/assets/0f1f3bae-cc8a-40d0-95fa-642048eb631e" />
)

This page focuses on market concentration, Superhost listings, pricing by room type, and city-level ratings.

---

## Review Frequency, Seasonality & Trust

![Review Frequency, Seasonality and Trust](<img width="516" height="388" alt="Review Page" src="https://github.com/user-attachments/assets/550798da-6801-4d58-98b7-e6fbb05f7525" />
)

This page analyzes customer review behavior, seasonal patterns, and host trust signals.

---

## Detailed Ratings

![Detailed Ratings](<img width="515" height="391" alt="Detailed Ratings" src="https://github.com/user-attachments/assets/346ba472-e835-4bf9-b381-49d408ac0dd2" />
)

The detailed ratings view compares city performance across accuracy, cleanliness, communication, location, and value.

---

# 📁 Project Structure

```text
Global-Airbnb-Performance-Dashboard/
│
├── README.md
│
├── Dashboard/
│   └── Airbnb_Performance_Dashboard.pbix
│
├── Screenshots/
│   ├── overview-dashboard.png
│   ├── market-share-ratings.png
│   ├── review-seasonality-trust.png
│   └── detailed-ratings.png
│
└── Data/
    └── README.md
```

---

# ⚠️ Notes & Limitations

* The analysis is based on the Airbnb dataset provided by Maeven Analytics.
* The findings represent the cities and data available in the dataset and should not automatically be interpreted as representative of the entire global Airbnb marketplace.
* The analysis identifies patterns and relationships in the available data but does not establish causal relationships.
* Average prices can be affected by differences in room type and market composition.
* Review frequency should not be interpreted as a direct measure of customer satisfaction.
* The decline in listings around 2020 coincides with the COVID-19 period, but the dashboard alone does not establish COVID-19 as the sole cause of the decline.

---

# 🚀 Future Improvements

Potential extensions to the project could include:

* Adding geographic maps to analyze listing concentration by neighborhood.
* Comparing Superhost and non-Superhost performance.
* Analyzing the relationship between price and customer ratings.
* Adding year-over-year performance metrics.
* Investigating listing performance by property type.
* Incorporating additional external market or tourism data.
* Developing predictive analysis for listing performance.
* Adding interactive filters for deeper city-level exploration.

---

## 👨‍💻 Project

**Global Airbnb Performance Dashboard**

Built using **Power BI** and **Power Query**
Data Source: **Maeven Analytics**
