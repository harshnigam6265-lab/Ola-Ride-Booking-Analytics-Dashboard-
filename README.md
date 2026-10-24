# 🚖 OLA Ride Booking Analytics Dashboard

An end-to-end data analytics project analyzing OLA ride-booking data for Bengaluru using **SQL, Microsoft Excel, and Power BI**. The project explores booking performance, vehicle-type trends, revenue, cancellations, and customer/driver ratings through an interactive five-page dashboard.

> **Dataset note:** This is a portfolio analysis of the dataset included in this repository. Dashboard figures are dataset-specific and should not be interpreted as official OLA business metrics.

## 📌 Project Overview

The objective is to convert ride-booking records into useful business insights. The workflow includes preparing the dataset, answering business questions with SQL, and presenting results through Power BI visualizations.

## 🧰 Tools & Technologies

- **Microsoft Excel** — data review and preparation
- **SQL** — filtering, aggregation, business-question analysis, and views
- **Power BI** — KPI cards, charts, date slicers, and interactive reporting

## 📊 Dashboard Pages

### 1. Overall Performance
Shows total bookings, booking value, booking-status breakdown, and ride volume over time.

![Overall Dashboard](screenshots/overview.png)
<img width="1075" height="603" alt="image" src="https://github.com/user-attachments/assets/fafb56f5-abc7-4961-ba28-4eb91da34980" />


### 2. Vehicle Type Analysis
Compares total booking value, successful booking value, average distance, and total distance travelled across vehicle types.

![Vehicle Type Dashboard](screenshots/vechile_type.png)
<img width="1072" height="601" alt="image" src="https://github.com/user-attachments/assets/5aac8a0e-195d-46c9-919d-497762c1d4f9" />


### 3. Revenue Analysis
Explores booking value by payment method, top customers by booking value, and ride-distance distribution by date.

![Revenue Dashboard](screenshots/revenue.png)
<img width="1075" height="602" alt="image" src="https://github.com/user-attachments/assets/bb3b780d-c5d7-41ed-8158-9acf4038df02" />


### 4. Cancellation Analysis
Examines customer and driver cancellation reasons, succeeded and cancelled bookings, and cancellation rate.

![Cancellation Dashboard](screenshots/cancellation.png)
<img width="1077" height="598" alt="image" src="https://github.com/user-attachments/assets/28b61195-3f8e-4677-ac58-f6e93884fa45" />


### 5. Ratings Analysis
Compares average driver ratings and customer ratings across vehicle types.

![Ratings Dashboard](screenshots/ratings.png)
<img width="1075" height="607" alt="image" src="https://github.com/user-attachments/assets/53a1aca0-7534-4b30-a9f2-f15ff6d6f49f" />


## 📈 KPI Snapshot

The current dashboard view displays these dataset-level figures:

| KPI | Value shown |
|---|---:|
| Total bookings | 103,024 |
| Successful bookings | 63,967 |
| Cancelled bookings | 28,933 |
| Cancellation rate | 28.08% |
| Total booking value | 35M |

The Overall page shows approximately **62.09% Success**, **17.89% Cancelled by Driver**, **10.19% Cancelled by Customer**, and **9.83% Driver Not Found**. Figures can change when the date filter is adjusted.

## 🔍 SQL Business Questions

The SQL script (`ola_queries.sql`) covers these questions:

1. Retrieve all successful bookings.
2. Calculate average ride distance by vehicle type.
3. Count bookings cancelled by customers.
4. Find the top five customers by number of bookings.
5. Count driver cancellations caused by personal or vehicle-related issues.
6. Find maximum and minimum driver ratings for Prime Sedan bookings.
7. Retrieve bookings paid through UPI.
8. Calculate average customer rating by vehicle type.
9. Calculate total booking value for successful rides.
10. List incomplete rides with their reasons.

The script uses SQL views to organize reusable query results. Review the SQL file before running it, and ensure the database and table (`Ola` and `bookings`) exist with matching column names.

## 💡 Key Analysis Areas

- Booking volume and booking-status distribution
- Vehicle-type performance and ride distance
- Booking value by payment method
- Highest-value customers
- Customer and driver cancellation reasons
- Customer and driver rating comparisons
- Date-based analysis using dashboard filters

## 🔄 Workflow

1. **Data preparation:** Reviewed and prepared the ride-booking dataset.
2. **SQL analysis:** Used filtering, grouping, aggregate functions, and views to answer business questions.
3. **Dashboard development:** Created Power BI visuals and KPI cards across five report pages.
4. **Business exploration:** Used dashboard filters to compare performance across dates and booking categories.


## 🚀 How to Explore

1. Clone or download this repository.
2. Open `ola_dataset.csv` to inspect the data.
3. Review `ola_queries.sql` for the SQL analysis.
4. Open `ola_project_dashboard.pbix` in **Microsoft Power BI Desktop**.
5. Use the date slicers and report interactions to explore the dashboard.

## 🧠 Skills Demonstrated

- Data preparation and cleaning
- SQL querying and aggregation
- KPI analysis
- Power BI dashboard development
- Data visualization and reporting
- Business analysis and problem-solving

## 👨‍💻 Author

**Harshit Nigam**  
B.Tech, Metallurgical and Materials Engineering  
National Institute of Technology, Raipur

- **GitHub:** [harshnigam6265-lab](https://github.com/harshnigam6265-lab)
- **LinkedIn:** Add your LinkedIn profile URL here

---

⭐ If you find this project useful, feel free to star the repository.
