# ✈️ Airline Booking Analysis (Forage x British Airways)

This project is based on the **Forage – British Airways Data Science Job Simulation** and uses a real-world-style dataset of **50,000 flight bookings** to explore customer behavior and booking completion.

The goal is to:
- Understand what factors influence whether a customer **completes** their booking.
- Clean and transform raw booking data into **model-ready features**.
- Practice an end-to-end **data science workflow** using Python and Jupyter Notebooks.

---

## 🧾 Dataset

The main dataset used is `customer_booking.csv` (50,000 rows, 14 columns), which includes:

- `num_passengers` – Number of passengers in the booking  
- `sales_channel` – Booking channel (e.g., Internet, Mobile)  
- `trip_type` – One-way vs round-trip  
- `purchase_lead` – Days between booking and flight date  
- `length_of_stay` – Trip length in days  
- `flight_hour` – Hour of departure  
- `flight_day` – Day of the week of the flight  
- `route` – Origin–destination route  
- `booking_origin` – Country of booking  
- `wants_extra_baggage` – 1 if customer wants extra baggage, else 0  
- `wants_preferred_seat` – 1 if customer wants a preferred seat, else 0  
- `wants_in_flight_meals` – 1 if customer wants in-flight meals, else 0  
- `flight_duration` – Flight duration in hours  
- `booking_complete` – **Target variable** (1 = booking completed, 0 = abandoned)

---

## 🧠 Skills Demonstrated

- Python (Pandas, NumPy)
- Data cleaning & exploratory data analysis (EDA)
- Feature engineering (e.g., converting `flight_day` to numeric)
- Working with categorical and numeric variables
- Jupyter Notebooks for analysis and documentation
- Reproducible project structure and GitHub documentation

This project is part of my portfolio to demonstrate **practical data science skills** on a realistic airline business problem.

---

## 📁 Project Structure

```text
.
├── README.md               # Project overview (you are here)
├── requirements.txt        # Python dependencies
├── .gitignore              # Ignore temporary / environment files
│
├── data/
│   ├── README.md           # Documentation for the dataset
│   └── customer_booking.csv# Main dataset (50,000 rows)
│
└── notebooks/
    └── getting_started.ipynb  # Exploration & feature engineering
