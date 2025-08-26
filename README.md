# Electric-Vehicle-Sales-Analysis-Prediction-in-India
This project analyzes EV sales in India, showing rising adoption, dominance of two- and three-wheelers, strong state-wise growth, and effective prediction using Gradient Boosting (R² ≈ 0.74), with policies, vehicle types, and time trends as key drivers for planning and policy support.

1. Introduction
The adoption of Electric Vehicles (EVs) is a key driver in India’s push toward sustainable mobility. This project analyzes EV sales data across Indian states and vehicle types, identifies trends, and applies Machine Learning (ML) models to predict EV sales.

2. Dataset Overview
   
Source: Electric Vehicle Sales by State in India
Size: ~96,845 records

Features:
Year, Month_Name, Date → Temporal sales information
State → Indian state of sale
Vehicle_Class → Detailed class (e.g., Tractor, Bus, Ambulance)
Vehicle_Category → Broader category (Car, Bus, Others)
Vehicle_Type → Simplified grouping of vehicle types
EV_Sales_Quantity → Target variable (sales volume)

3. Exploratory Data Analysis (EDA)
   
a) Market Trend Analysis (Bar Plot: Yearly EV Sales by Vehicle Type)
EV sales have shown a consistent upward trend over the years.
Two-wheeler and three-wheeler EVs dominate adoption.
Passenger cars and buses also show growing adoption, especially in recent years.

b) Infrastructure Planning (Heatmap: State vs Vehicle Class Sales)
Sales are unevenly distributed across states.
States like Delhi, Maharashtra, Karnataka, and Uttar Pradesh emerge as leaders.
Vehicle classes differ state-wise: some states favor two-wheelers, others focus on public transport (buses).

c) Market Share by Vehicle Category (Pie Chart)
Two-wheelers form the largest market share.
Three-wheelers are the second-largest, supporting public and shared mobility.
Cars and buses have smaller shares but are steadily increasing.

4. Machine Learning for Sales Prediction
   
Preprocessing
Categorical features: One-hot encoded (State, Vehicle_Class, etc.)
Numerical features: Passed through unchanged (Year, etc.)
Target: EV_Sales_Quantity

Models Tested
Linear Regression
Random Forest Regressor
Gradient Boosting Regressor

Evaluation Metrics
RMSE (Root Mean Squared Error)
R² (Coefficient of Determination)

Results
Best model: Gradient Boosting Regressor
RMSE ≈ 261.3
R² ≈ 0.74
This indicates that the model explains ~74% of the variance in EV sales, which is fairly strong given the complexity of the dataset.

5. Model Insights
   
a) Actual vs Predicted EV Sales
Predictions follow the actual trend closely, though some high sales spikes are under/overestimated.

b) Feature Importance
Key factors influencing EV sales:
State (policy support and adoption varies)
Vehicle_Type & Category
Year (natural growth trend)
This confirms that regional policy and vehicle type are crucial drivers of EV adoption.

6. Conclusion & Recommendations

EV adoption in India is growing rapidly, with two-wheelers and three-wheelers leading the market.
Sales vary significantly across states, suggesting that state-level policy interventions (subsidies, charging infra) strongly affect adoption.
Predictive modeling shows that future sales can be reasonably forecasted using historical trends, state, and vehicle characteristics.

Recommendations:

Focus on high-growth states to expand charging infrastructure.
Encourage adoption of buses and cars with targeted subsidies.
Monitor state-level differences to design region-specific EV policies.

Use ML forecasting for demand planning and policy evaluation.
