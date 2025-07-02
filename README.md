# ✈️ Customer Booking Prediction

This project analyzes customer flight booking behavior and builds a predictive model to determine whether a booking will be completed or not.

## 📊 Problem Statement

Airlines want to better understand customer behavior and identify which users are likely to complete their bookings. Using historical booking data, this project aims to predict booking completion using various user and flight features.

## 📁 Dataset

- The dataset used is `customer_booking.csv`.
- It contains customer behavior features like:
  - Flight day and hour
  - Number of passengers
  - Preferences (e.g., seat, baggage, meals)
  - Booking channel and route
  - Length of stay, trip type, etc.
  - Target: `booking_complete` (1 if completed, 0 if not)

## ⚙️ Key Features Engineered

- `total_addons`: Combined preference for meals, baggage, and seat
- `time_of_day`: Categorized flight hour into morning, afternoon, evening, night
- `is_weekend`: Flag for flights booked on weekends
- `is_group`: Whether the booking includes more than 1 passenger
- `long_stay`: Whether the length of stay is greater than 7 days

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn (if visualization is included)
- Jupyter Notebook

## 🧠 Machine Learning



- Model(s) used: Logistic Regression / Random Forest / etc.
- Evaluation: Accuracy, Confusion Matrix, ROC-AUC Score

## 📈 Results


- Best model: XYZ
- Accuracy: 85%
- Key insight: Customers booking in the morning with more add-ons are more likely to complete their bookings.


