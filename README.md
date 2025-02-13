# Predicting-Hotel-Reservation-Cancellations
A machine Learning Project was done using R Programming

## Objective
This project aims to predict hotel reservation cancellations using machine learning. The goal is to help the hotel reduce cancellations, improve customer retention, and maximize revenue.

## Dataset
The dataset contains information about **5,725 hotel reservations**, including:
- Booking status (cancelled or notcancelledd)
- Customer details (number of adults, children, special requests, etc.)
- Booking details (room type, meal plan, room price, lead time, etc.)

## Key Steps
1. **Exploratory Data Analysis (EDA)**:
   - Analyzed factors influencing cancellations (e.g., lead time, room price, meal plans).
   - Created visualizations to identify trends and patterns.
2. **Machine Learning Modeling**:
   - Built and evaluated three models: Logistic Regression, Random Forest, and Decision Tree.
   - Selected the **Random Forest model** as the best performer (AUC: 0.909).
3. **Recommendations**:
   - Proposed actionable strategies to reduce cancellations, such as dynamic pricing, flexible rescheduling, and loyalty programs.

## Results
- **Best Model**: Random Forest (AUC: 0.909, F1 Score: 0.881).
- **Key Insights**:
  - Bookings made far in advance are more likely to be cancelled.
  - Higher room prices are associated with higher cancellation rates.
  - Certain meal plans and room types have higher cancellation rates.

