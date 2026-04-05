# Business-Insights-Hotel-Bookings
Exploratory Data Analysis on hotel booking transactions to uncover customer behavior, cancellation drivers, revenue patterns, and seasonal trends. Built actionable business recommendations to reduce cancellations and optimize profitability for an online travel platform. Includes Analysis, visualizations, PowerPoint insights, and a detailed report.
# Hotel Booking Data Analysis: Customer Behaviour, Revenue & Cancellation Insights

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge)
![PowerPoint](https://img.shields.io/badge/PowerPoint-B7472A?style=for-the-badge&logo=microsoft-powerpoint&logoColor=white)

## 📌 Project Overview

This project performs an **in-depth Exploratory Data Analysis (EDA)** on hotel booking transactions from an online travel platform. The goal was to understand customer booking behaviour, identify key drivers of cancellations, analyse revenue patterns across channels, room types, and star ratings, and uncover seasonal trends.

The analysis reveals critical insights such as:
- High cancellation rates through **Travel Agents (27.9%)** and **Standard Rooms (23.3%)**
- Surprisingly higher cancellations at **5-Star properties (21.3%)**
- Strong volume spike in April but lower average booking value
- Peak cancellation risk during summer months (July–August)

The final deliverables include **actionable business recommendations** to reduce cancellations, improve booking stability, and optimize pricing & channel strategy.

## 🎯 Business Problem

Online travel platforms lose significant revenue due to high cancellation rates and suboptimal channel performance. This analysis helps identify low-commitment segments and provides data-driven strategies to increase booking reliability and profitability.

## 📊 Key Insights

### Customer Behaviour & Cancellation Drivers
- **Travel Agents** show the highest cancellation rate (**27.9%**) vs. **Website** bookings (**17.6%**)
- **Standard Rooms** are most risky (**23.3%** cancellation) while **Deluxe Rooms** are the most stable (**16.0%**)
- **5-Star hotels** have higher cancellations (**21.3%**) compared to lower-star properties

### Revenue & Seasonal Trends
- April sees massive booking volume (~4,494) but significantly lower average booking value
- Summer months (July–August) show high booking value but very high cancellation rates (~30%)
- November is the most stable month with the lowest cancellation rate (~15.9%)

### Correlation Findings
- Almost no linear relationship between **booking value** and **cancellation** (correlation ≈ -0.04)
- Booking channel has the strongest (though still weak) correlation with booking value

## 🛠️ Tools & Technologies

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Jupyter Notebook** for analysis and visualizations
- **Microsoft PowerPoint** for business-friendly insights and charts
- **Microsoft Word** for the detailed report

## 📁 Repository Structure
/Business-Insights-Hotel-Bookings

├── Notebook_Ayush_Travclan_.ipynb          
├── Report_AyushLohani_TravClan.docx       
├── Charts_Ayush_Travclan.pptx            
├── Hotel_bookings_final.csv              
├── images/                                 
└── README.md
