# AtliQ Hotels — Exploratory Data Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on hotel booking and operational data for **AtliQ Hotels**, a fictional luxury/business hotel chain operating across India.

The objective is to explore hotel performance, identify important business patterns, and translate the analysis into **actionable, business-oriented insights** using Python and Pandas.

---

## 🏨 Business Problem

AtliQ Hotels is facing challenges in maintaining market share and revenue performance in the competitive hospitality market.

The purpose of this analysis is to understand:

- Revenue performance across cities and hotel categories
- Occupancy performance across markets and day types
- Booking-platform contribution to realized revenue
- Monthly revenue trends
- Customer-rating patterns
- Areas where management may need to focus attention

---

## 🎯 Project Objectives

The analysis focuses on:

- Cleaning and preparing hotel datasets
- Exploring booking and revenue data
- Calculating occupancy rates
- Comparing hotel and city performance
- Analyzing revenue trends
- Examining booking-platform contribution
- Extracting business insights from the data

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **Matplotlib**
- **Jupyter Notebook**

---

## 📊 Key Business Insights

### 1. Mumbai is the leading revenue market

Mumbai generates the highest realized revenue among the four analyzed cities, making it an important market for AtliQ's overall revenue performance.

### 2. Delhi has the highest occupancy

Delhi records the highest average occupancy at approximately **61.5%**, while Bangalore has the lowest at approximately **56.3%**.

This suggests that occupancy performance varies considerably by market and that different cities may require different strategies.

### 3. Weekend demand is significantly stronger than weekday demand

Average occupancy is approximately **72.3% on weekends compared with 50.9% on weekdays**.

This large gap highlights a potential opportunity to increase weekday demand through targeted promotions, corporate offers, events, and other demand-generation strategies.

### 4. Luxury hotels are a major revenue contributor

The Luxury category contributes approximately **61.6% of realized revenue**, making it strategically important to AtliQ's revenue performance.

### 5. Bangalore requires further investigation

Bangalore has the lowest occupancy among the analyzed cities and also records the lowest average customer rating at approximately **3.41**.

This combination suggests that Bangalore deserves further investigation into demand generation, guest experience, and operational performance.

---

## 💡 Overall Business Takeaway

**AtliQ Hotels does not have one single, company-wide performance problem. Different markets show different challenges.**

- **Mumbai** → opportunity to improve occupancy while protecting its strong revenue contribution
- **Delhi** → opportunity to investigate revenue optimization despite strong occupancy
- **Bangalore** → opportunity to improve demand and customer experience
- **Weekdays** → significant opportunity to increase demand
- **Luxury segment** → strategically important because of its large contribution to realized revenue

The EDA therefore suggests that AtliQ should consider **market-specific and segment-specific strategies rather than applying one solution across the entire business.**

> **Note:** These findings identify opportunities for further investigation; the EDA alone does not prove the underlying causes of each performance difference.

---

# 📈 Visual Analysis

The project includes several visualizations designed around the main business questions.

## Revenue Realized by City

![Revenue Realized by City](images/Revenue%20Realized%20by%20City.png)

Mumbai stands out as the largest revenue-generating market in the analyzed data.

---

## Average Occupancy Rate by City

![Average Occupancy Rate by City](<img width="890" height="490" alt="Average Occupancy Rate by City" src="https://github.com/user-attachments/assets/9d8e5cba-2513-4d21-bc6c-1f3b70794af9" />
)

Delhi records the highest average occupancy, while Bangalore records the lowest among the analyzed cities.

---

## Weekday vs Weekend Occupancy

![Weekday vs Weekend Occupancy](images/Weekday%20vs%20Weekend%20Occupancy.png)

The substantial difference between weekday and weekend occupancy highlights a potential opportunity to strengthen weekday demand.

---

## Revenue Realized by Hotel Category

![Revenue Realized by Hotel Category](images/Revenue%20Realized%20by%20Hotel%20Category.png)

Luxury hotels contribute the majority of realized revenue, making the segment strategically important.

---

## Monthly Revenue Trend

![Monthly Revenue Trend](images/Monthly%20Revenue%20Trend.png)

The monthly trend provides a view of how realized revenue changes across the analyzed period.

---

## Revenue Realized by Booking Platform

![Revenue Realized by Booking Platform](images/Revenue%20Realized%20by%20Booking%20Platform.png)

The booking-platform analysis shows how realized revenue is distributed across the different channels used to make hotel bookings.

---

## 📁 Project Structure

```text
AtliQ Hotels Exploratory Data Analysis/
│
├── datasets/
│   ├── dim_date.csv
│   ├── dim_hotels.csv
│   ├── dim_rooms.csv
│   ├── fact_aggregated_bookings.csv
│   ├── fact_bookings.csv
│   └── new_data_august.csv
│
├── images/
│   ├── Average Occupancy Rate by City.png
│   ├── Monthly Revenue Trend.png
│   ├── Revenue Realized by Booking Platform.png
│   ├── Revenue Realized by City.png
│   ├── Revenue Realized by Hotel Category.png
│   └── Weekday vs Weekend Occupancy.png
│
├── notebooks/
│   ├── hotels_analysis.ipynb
│   └── exercise_solution.ipynb
│
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
https://github.com/sorofaf-hue/AtliQ-Hotels-Exploratory-Data-Analysis.git
```

### 2. Navigate into the project

```bash
cd "AtliQ Hotels Exploratory Data Analysis"
```

### 3. Install the dependencies

```bash
pip install -r requirements.txt
```

### 4. Open Jupyter Notebook

```bash
jupyter notebook
```

Then open:

```text
notebooks/hotels_analysis.ipynb
```

Run the notebook cells from top to bottom.

---

## 📦 Requirements

The project currently uses:

```text
pandas==3.0.5
```

Matplotlib is also used in the analysis notebook for visualization.

If your environment does not already have it installed:

```bash
pip install matplotlib
```

---

## 📓 Notebook

The main analysis is available in:

`notebooks/hotels_analysis.ipynb`

The notebook covers data loading, exploration, cleaning/transformation, occupancy calculations, revenue analysis, and business insights.

---

## 👤 Author

**Fortune Sorofa**

Computer Science Student | Aspiring Data Analyst

---

*This project demonstrates the application of Python, Pandas, and data visualization techniques to a real-world-style hospitality business problem.*
