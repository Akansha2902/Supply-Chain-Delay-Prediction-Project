# Supply-Chain-Delay-Prediction-Project

Problem Statement

Logistics and supply chain companies need to predict shipment delays to optimize operations and improve customer satisfaction. The objective of this project is to predict the delay duration (in hours) using shipment, route, warehouse, and external factors.

Data Dictionary

distance_km, shipment_weight, shipment_volume, traffic_index, route_complexity_score, number_of_stops, driver_experience_years, origin_warehouse_load, destination_warehouse_load, processing_time_hours, fuel_price, holiday_flag, strike_flag, dispatch_delay_hours, handling_issues_count, documentation_delay_flag, delay_duration_hours (target)

EDA Questions

What is the distribution of delay_duration_hours?

How does distance_km affect delay?

Does traffic_index increase delay significantly?

How does route_complexity_score impact delay?

Do more stops increase delay?

Does driver experience reduce delay?

How does warehouse load affect delays?

Do holidays increase delays?

Do strikes cause extreme delays?

How does weather impact delay?

Which transport mode causes highest delay?

Is delay higher for long distance shipments?

Are there outliers in delay?

Which features are most correlated with delay?

Does dispatch delay directly affect final delay?

Are there nonlinear relationships present?

Do combinations of traffic + weather increase delay?

Does fuel price impact indirectly?

Which factor contributes most to delay?

What patterns can be observed overall?

Feature Engineering

Create new features such as:

• delay_per_km

• load_ratio

• traffic_category

• risk_score

• weather_severity_index

Feature Scaling

Apply scaling for KNN and Polynomial Regression using StandardScaler or MinMaxScaler.

Model Building

Train: Linear Regression, Polynomial Regression, Decision Tree, Random Forest, Gradient Boosting, XGBoost, KNN.

Model Evaluation

Use MAE, MSE, RMSE, and R² Score to compare models.
