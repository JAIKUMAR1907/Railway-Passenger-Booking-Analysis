# 🚆 Railway Passenger Booking Analysis – Power BI Dashboard

## 📌 Project Overview

The **Railway Passenger Booking Analysis** project is an interactive Power BI dashboard developed to analyze railway passenger bookings, revenue, train performance, booking status, and passenger demographics.

The dashboard helps users understand booking trends and compare the performance of different trains and travel classes through interactive visualizations and slicers.

## 🎯 Project Objectives

- Analyze the total number of railway bookings and passengers.
- Track total revenue and average fare.
- Understand booking status distribution.
- Compare revenue across different quarters and travel classes.
- Identify top-performing trains based on bookings and revenue.
- Analyze passenger bookings by gender.
- Explore booking data using interactive filters.

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Dashboard development and data visualization.
- **Power Query** – Data cleaning and transformation.
- **DAX** – Measures and KPI calculations.
- **Microsoft Excel** – Dataset storage and preparation.

## 📂 Dataset Description

The project uses a railway passenger booking dataset stored in Excel.

- **Worksheet:** `Cleaned_Data`
- **Records:** 2,822
- **Columns:** 15

### Main columns

| Column | Description |
|---|---|
| Booking ID | Unique booking reference |
| Passenger Name | Name of the passenger |
| Age | Passenger age |
| Gender | Passenger gender |
| Train Number | Train number |
| Train Name | Name of the train |
| Source Station | Journey starting station |
| Destination Station | Journey destination |
| Class | Travel class |
| Booking Date | Date the ticket was booked |
| Journey Date | Scheduled journey date |
| Fare | Ticket fare |
| Seat Number | Passenger seat reference |
| Booking Status | Confirmed, Cancelled, RAC, or Waiting List |
| Booking Month | Month of booking |

## 🧹 Data Preparation

The dataset was prepared for analysis using Power Query and the Power BI data model.

The project separates booking information into a fact table and supporting dimension tables to organize the data and make analysis easier.

## 🧩 Data Model

The project follows a **star-schema-style data model** with the following tables:

- **Fact Booking** – Contains booking-level information and measures such as fare.
- **Dim Train** – Contains train details.
- **Dim Passenger** – Contains passenger details.
- **Dim Calendar** – Contains date attributes such as date, month, quarter, weekday, and year.
- **Dim Route** – Contains source and destination station details.

The dimension tables are connected to the Fact Booking table through relationships, enabling analysis across trains, passengers, dates, and routes.

## 📊 Dashboard Features

The dashboard includes the following KPIs and visualizations:

### Key Performance Indicators (KPIs)

- **Total Booking:** 2,822
- **Total Revenue:** 6.08M
- **Average Fare:** 2.15K
- **Total Train:** 11
- **Total Passengers:** 2,756

### Visualizations

1. **Total Booking by Booking Status** – Shows the distribution of Cancelled, RAC, Confirmed, and Waiting List bookings.
2. **Total Revenue by Quarter** – Displays quarterly revenue trends.
3. **Train-wise Performance** – Compares total bookings and revenue for each train.
4. **Top 10 Highest Fare Bookings** – Displays the ten bookings with the highest fares.
5. **Total Revenue by Class** – Compares revenue across different travel classes.
6. **Total Booking by Gender** – Shows booking distribution by gender.

### Interactive Slicers

Users can filter the dashboard by:

- Booking Status
- Class
- Train Name
- Gender
- Date range

## 🖼️ Dashboard Preview

![Railway Booking Performance Dashboard](images/Dashboard.png)

## 🗂️ Data Model Preview

![Railway Booking Data Model](images/Data%20Model.png)

## 📁 Project Files

```text
Railway-Passenger-Booking-Analysis/
│
├── README.md
├── Railway Passenger Booking Analysis.pbix
├── Railway_Passenger_Booking_Dataset.xlsx
└── images/
    ├── Dashboard.png
    └── Data Model.png
```

> Keep the dashboard and data model screenshots inside a folder named `images` in your GitHub repository. Use the same filenames shown above, or update the image paths in this README.

## 🚀 How to Use This Project

1. Download or clone this repository.
2. Open `Railway Passenger Booking Analysis.pbix` using Power BI Desktop.
3. If Power BI asks for the Excel source location, update the source path to `Railway_Passenger_Booking_Dataset.xlsx`.
4. Refresh the data if required.
5. Explore the dashboard using the slicers and visualizations.

## 💡 Key Insights

This dashboard provides an overview of railway booking performance, including booking status distribution, quarterly revenue, train-wise performance, class-wise revenue, and passenger booking patterns.

Users can interact with the report to explore these metrics across different trains, classes, booking statuses, genders, and dates.

## 💡 Business Suggestions

Based on the dashboard analysis, the following business suggestions can help improve railway booking performance:

1. **Reduce Booking Cancellations:** Analyze the reasons behind cancellations and introduce better booking policies to reduce cancellation rates.

2. **Improve Waiting List Management:** Monitor RAC and Waiting List bookings and improve seat allocation to provide better booking experiences for passengers.

3. **Increase Quarterly Revenue:** Analyze the lower revenue in Q4 and identify opportunities to improve bookings during low-revenue periods.

4. **Improve Train Performance:** Focus on trains with lower booking and revenue performance and identify opportunities to increase passenger demand.

5. **Optimize Travel Classes:** Analyze class-wise revenue and passenger demand to improve seat availability and resource allocation.

6. **Improve Passenger Experience:** Use booking trends and passenger data to improve railway services and customer satisfaction.

## 👤 Author

**JAIKUMAR**

---

⭐ If you find this project useful, feel free to star the repository!
