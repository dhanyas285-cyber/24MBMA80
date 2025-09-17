

# 💇‍♀️ Salon & Spa – Service Utilization & Customer Insights

## 📌 Industry Scenario

This project analyzes **customer booking data** from a Salon & Spa to identify:

* Popular services
* Peak hours & days
* Revenue contribution by category
* Insights to improve customer experience

---

## 📂 Dataset (50–100 Records)

Columns:

* **Customer** → `customer_id, customer_name, gender, age`
* **Service** → `service_id, service_name, category (hair, skin, spa, grooming)`
* **Booking** → `booking_id, booking_date, booking_time, amount_spent, duration, staff_id, status`

---

## ⚡ Approach

* **PySpark Core** → Revenue per category, average booking duration
* **PySpark SQL** → Most popular services, peak hours, peak days
* **Visualization** → Bar charts & line plots for clear insights

---

## 📊 Key Results

### Revenue by Category

| Category | Total Revenue |
| -------- | ------------- |
| Hair     | 15,000        |
| Skin     | 25,000        |
| Spa      | 40,000        |

### Most Popular Services

| Service Name | Total Bookings |
| ------------ | -------------- |
| Haircut      | 30             |
| Massage      | 22             |
| Facial       | 18             |

### Peak Hours

| Hour | Total Bookings |
| ---- | -------------- |
| 18   | 15             |
| 19   | 12             |
| 11   | 10             |

 Peak Days

| Weekday  | Total Bookings |
| -------- | -------------- |
| Saturday | 25             |
| Sunday   | 20             |
| Friday   | 15             |

---

 Insights

* **Haircut** is the most frequently booked service.
* **Massage** generates the highest revenue.
* **Evenings (6–7 PM)** and **weekends** are the busiest slots.
* Helps optimize **staff allocation** & **promotional offers**.

 Full code is available in [`analysis.ipynb`](./analysis.ipynb).


