# Uber Rides 2024 – Data Analysis & Visualization with Python

### **Domain:** Transportation Services

### **Tools Used:** Python, Pandas, NumPy, Matplotlib, Seaborn

## **Project Overview**

This project explores the **2024 Uber Ride dataset**, performing end-to-end **data cleaning**, **preprocessing**, **exploratory data analysis (EDA)**, and **visualization** to uncover patterns in user demand, booking behavior, cancellations, revenue, vehicle performance, and rating trends.

The goal is to transform raw ride-sharing data into **meaningful insights** that support operational improvements, resource allocation, and strategic decision-making.


## **Objectives**

* Clean, transform, and preprocess raw Uber data for reliability
* Identify booking trends, peak demand time periods, and ride distances
* Analyze cancellation patterns (customer & driver) and their reasons
* Visualize revenue, vehicle type performance, and payment preferences
* Derive insights to reduce cancellations and improve customer experience


## **Dataset Details**

* **Source:** Kaggle
* **Timeline:** Jan 2024 – Dec 2024
* **File Name:** `ncr_ride_bookings.csv`
* **Rows:** 150,000
* **Columns:** 21

### **Key Features Include:**

* Date & Time
* Booking ID & Status
* Customer & Vehicle Type
* Pickup/Drop Locations
* Ride Distance & Value
* VTAT / CTAT
* Cancellation & Incomplete ride reasons
* Driver & Customer ratings
* Payment method


## **Tech Stack**

| Task          | Tools                                             |
| ------------- | ------------------------------------------------- |
| Data Handling | Pandas, NumPy                                     |
| Visualization | Matplotlib, Seaborn                               |
| Analysis      | Descriptive, Diagnostic, Predictive, Prescriptive |
| Notebook      | Google Colab                                      |


## **Key Analysis Performed**

### **Data Cleaning**

* Checked duplicates
* Handled missing values (NaN → 0 or category-specific)
* Verified data types
* Removed noise/unnecessary inconsistencies

### **Exploratory Data Analysis**

* Peak booking dates & times
* Vehicle type distribution
* Most common pickup & drop locations
* Cancellation patterns
* Payment method preferences
* Rating distributions
* Repeated customers & repeated booking IDs

### **Visualizations**

* Bar charts
* Count plots
* Distribution plots
* Trend analysis
* Cancellation reason charts
* Vehicle performance comparisons

## **Key Insights**

* **Completed rides:** 93,000 (most frequent status)
* **Top Vehicle Types:** Auto, Go Mini, Go Sedan
* **Peak pickup locations:** Khandsa, Barakhamba Road, Saket
* **Most common cancellation reasons:**

  * Customer → Wrong Address, Change of Plans
  * Driver → Customer-related issues, sickness concerns
* **Most used payment method:** UPI
* **Highest customer satisfaction:** UberXL (Avg: 4.24 rating)

## **Recommendations**

* Improve driver allocation during peak hours
* Enforce better communication for location accuracy
* Incentivize drivers to reduce cancellation behavior
* Enhance vehicle reliability to reduce incomplete rides
* Promote digital payment options for faster processing

## **Conclusion**

This project delivers a complete data-driven understanding of Uber operations for 2024.
It identifies key problem areas, highlights performance trends, and provides recommendations for improving rider satisfaction, reducing cancellations, and optimizing resource allocation.
