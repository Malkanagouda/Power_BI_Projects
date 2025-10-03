# 🏨 Hotel Bookings Analysis Dashboard  

This **Power BI project** provides a comprehensive analysis of hotel bookings data, enabling stakeholders to explore hotel performance, room occupancy, revenue generation, and booking trends. The dataset consists of **five CSV files** capturing hotel, room, date, and booking information.  

---

## 🔎 Project Overview  
The dashboard focuses on understanding **hotel operations and booking patterns**:  
- Analyze bookings by date, room type, and hotel category  
- Monitor room occupancy and capacity utilization  
- Track revenue generation and realized revenue per hotel  
- Examine customer behavior, ratings, and booking platforms  
- Identify trends in successful bookings and cancellations  

It leverages **Power BI’s interactive features** to provide an **intuitive, user-friendly experience** for exploring hotel and booking data.  

---

## 📂 Dataset Description  

The project uses **five CSV files** with the following structure:  

### 1. **dim_date**  
| Column | Description |
|--------|-------------|
| date | Dates from May, June, and July |
| mmm yy | Date formatted as month-year (e.g., May 2025) |
| week no | Unique week number for each date |
| day_type | Weekend or Weekday indicator |

### 2. **dim_hotels**  
| Column | Description |
|--------|-------------|
| property_id | Unique ID for each hotel |
| property_name | Hotel name |
| category | Hotel class (Luxury, Business) |
| city | Hotel location |

### 3. **dim_rooms**  
| Column | Description |
|--------|-------------|
| room_id | Room type (RT1, RT2, RT3, RT4) |
| room_class | Room class (Standard, Elite, Premium, Presidential) |

### 4. **fact_aggregated_bookings**  
| Column | Description |
|--------|-------------|
| property_id | Unique ID for each hotel |
| check_in_date | Check-in date of customers |
| room_category | Room type (RT1, RT2, RT3, RT4) |
| successful_bookings | Number of successful bookings for a room type |
| capacity | Maximum rooms available for a room type |

### 5. **fact_bookings**  
| Column | Description |
|--------|-------------|
| booking_id | Unique booking ID per customer |
| property_id | Unique ID for each hotel |
| booking_date | Date when the room was booked |
| check_in_date | Customer check-in date |
| check_out_date | Customer check-out date |
| no_guests | Number of guests in the room |
| room_category | Room type (RT1, RT2, RT3, RT4) |
| booking_platform | Platform used for booking |
| ratings_given | Ratings provided by customers |
| booking_status | Booking status (Cancelled, Checked Out, No show) |
| revenue_generated | Revenue amount for the booking |
| revenue_realized | Actual revenue after deductions based on booking status |

---

## 📈 Key Insights  
The dashboard provides insights such as:  
- **Bookings Trends:** Daily, weekly, and monthly patterns for check-ins and successful bookings  
- **Room & Hotel Performance:** Occupancy rates, capacity utilization, and top-performing rooms/hotels  
- **Revenue Analysis:** Total revenue, revenue realized, and comparison by room category or hotel  
- **Customer Insights:** Ratings, booking platforms, and guest preferences  
- **Cancellation Patterns:** Analysis of cancelled and no-show bookings  

---

## 🛠️ Skills Demonstrated  
- **Data Cleaning & Transformation:** Preparing hotel and booking data for analysis  
- **Data Modeling:** Relationships between hotels, rooms, dates, and bookings  
- **DAX Calculations:** KPIs for revenue, occupancy, and booking trends  
- **Interactive Visualizations:** Maps, charts, tables, and slicers for deep exploration  
- **Data Storytelling:** Presenting actionable insights for hotel management and operations  

---

## 🎯 Purpose & Usefulness  
This dashboard helps stakeholders to:  
- Monitor hotel and room performance  
- Identify high-demand areas, peak periods, and booking trends  
- Make data-driven decisions on pricing, promotions, and capacity planning  
- Optimize operational efficiency and revenue realization  

---

## 📬 Get in Touch  
If you’d like to know more about this project or collaborate on similar Power BI dashboards, feel free to reach out:  

- 💼 **LinkedIn:** [https://linkedin.com/in/mvrp7143](https://linkedin.com/in/mvrp7143)  
- 🌐 **Portfolio / Website:** [https://github.com/Malkanagouda](https://github.com/Malkanagouda)  
- 📩 **Email:** mgpatil1107@gmail.com  

I’m always happy to connect, share insights, or discuss new projects!
