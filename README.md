
# Lyft Dashboard

### Dashboard Link: https://app.powerbi.com/view?r=eyJrIjoiZjgwZGM5NmMtYWFmZS00ZmNjLTk3Y2MtNjY1N2U3OWI5ZDAxIiwidCI6Ijk2NDY0YThhLWY4ZWQtNDBiMS05OWUyLTVmNmI1MGEyMDI1MCIsImMiOjN9

## Problem Statement
This Power BI dashboard provides a comprehensive view of Lyft’s ride-sharing operations, focusing on ride volume, revenue generation, cancellation trends, and user ratings. The goal is to identify key trends in ride demand, understand factors affecting booking success, analyze revenue by payment methods, and explore reasons behind ride cancellations.

By analyzing this data, Lyft can optimize driver allocation, improve customer satisfaction, and minimize ride cancellations.

### Steps Followed:
- Step 1: Data Import & Cleaning
Imported the dataset into Power BI Desktop (CSV format).
Used Power Query Editor to check column distribution, quality, and profiling.
Removed duplicates, handled missing values, and formatted time-based data.

- Step 2: Data Transformation & Preparation
Created calculated columns for ride distance categories, peak-hour rides, and customer spending tiers. Applied filters to ensure only successful bookings were used for revenue calculations.Ensured cancellation reasons were properly categorized.

- Step 3: Data Visualization & Report Design
Applied a consistent theme for clear data representation.
Added slicers (filters) for: Booking Status, Payment Methods,Vehicle Type,Date Range.

Created key visualizations:

Line Chart: Ride volume over time.

Pie Chart: Booking status breakdown.

Bar Chart: Revenue by payment method.

Stacked Bar Chart: Cancellation reasons by customer vs. driver.

Card Visuals:Total Bookings, Successful Bookings, Cancellation Rate, Top 5 Customers by Booking Value.


### Sneek - Peek at the Dashboard

![Overall](https://github.com/user-attachments/assets/638042f0-aee0-4c47-b21b-f6ebc8dd4ec6)

![VehicleType](https://github.com/user-attachments/assets/4a2ab44f-525a-4cff-81ea-646a22fba6cb)

![Cancellations](https://github.com/user-attachments/assets/7ee01558-b3e1-42c6-9d1d-b158af3d015f)


## To get access to interactive Dashboard visit: https://app.powerbi.com/view?r=eyJrIjoiZjgwZGM5NmMtYWFmZS00ZmNjLTk3Y2MtNjY1N2U3OWI5ZDAxIiwidCI6Ijk2NDY0YThhLWY4ZWQtNDBiMS05OWUyLTVmNmI1MGEyMDI1MCIsImMiOjN9


### Key Insights from The Dashboard:

### [1] Ride Volume & Booking Status
Total Bookings = 71,201

Successful Bookings = 44,271 (62.18%)

Cancelled by Customer = 7,210 (10.13%)

Cancelled by Driver = 12,730 (17.88%)

Driver Not Found Cases = 6,990 (9.81%)
#### 📌 Insight:
 The overall success rate aligns with the requirement (62%). However, cancellations by drivers (17.88%) are slightly above the 18% threshold.

 ### [2] Revenue & Payment Trends
Total Booking Value = ₹24 million

Top Payment Methods = UPI & Credit Cards contribute the most revenue.
Cash payments are relatively lower.

#### 📌Insight: 
Digital payments dominate, indicating a cashless preference among users. Targeting discounts or offers on UPI payments could further increase digital transactions.

### [3] Ride Distance & Vehicle Type
Most Rides (Top 5 Vehicles by Distance):
Prime Sedan > Prime SUV > Mini > Auto > Bike

#### 📌Insight: 
Sedans and SUVs generate the longest ride distances, making them key contributors to revenue. Incentivizing drivers in these categories could boost profits.

### [4] Cancellation Trends
#### Customer Cancellation Reasons:

Top Reasons:
Driver not moving to pickup (29.96%) > Driver asked to cancel (25.66%) >  Change of plans (20.36%)

#### Driver Cancellation Reasons:
Top Reasons:
Personal & car-related issues (34.95%) > Customer-related issues (29.48%) > More than permitted passengers (15.63%)

#### 📌Insight: 
The most common customer complaint is drivers not heading toward the pickup location. Introducing penalties or incentives could reduce this issue. On the driver side, personal issues account for the highest cancellations, suggesting a need for better driver support programs.

### [5] Customer & Driver Ratings
Average Driver Rating: ~4.00

Average Customer Rating: ~4.00

📌Insight: Ratings are consistent, indicating balanced experiences between customers and drivers.

### Next Steps & Recommendations
1️.Reduce Driver Cancellations:

Implement stricter penalties for frequent cancellations. Provide incentives for completing more rides.

2.Improve Customer Experience:

Address "Driver not moving to pickup" complaints. Introduce real-time driver tracking alerts for better transparency.

3️.Optimize Revenue Growth:

Offer discounts on digital payment methods to encourage non-cash transactions. Promote high-revenue vehicle types (Sedan & SUV) with targeted incentives.

This Lyft Power BI dashboard offers valuable insights into ride trends, revenue generation, cancellation patterns, and user satisfaction, helping Lyft enhance service quality and efficiency.

