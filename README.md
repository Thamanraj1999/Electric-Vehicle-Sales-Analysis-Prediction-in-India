## 📌 Project Overview
This project examines EV sales trends across India, highlighting:  
- 🚀 Rapid adoption of EVs nationwide  
- 🛵 Dominance of two- and three-wheelers  
- 📈 Strong state-wise growth patterns  
- 🤖 Accurate sales prediction using **Gradient Boosting** (R² ≈ 0.74)  
- 🏛️ Key drivers: policies, vehicle type preferences, and temporal trends  

---

## 🔍 Introduction
Electric Vehicles (EVs) are central to India’s shift toward sustainable mobility.  
This project:  
- Analyzes EV sales by **state and vehicle type**  
- Identifies **growth patterns and adoption trends**  
- Applies **Machine Learning models** to forecast future EV sales  

---

## 📂 Dataset Overview
- **Source:** Electric Vehicle Sales by State in India  
- **Size:** ~96,845 records  

**Features:**  
- **Temporal:** Year, Month_Name, Date  
- **Geographic:** State  
- **Vehicle Details:** Vehicle_Class (Tractor, Bus, Ambulance, etc.), Vehicle_Category (Car, Bus, Others), Vehicle_Type (simplified grouping)  
- **Target Variable:** EV_Sales_Quantity (number of vehicles sold)  

---

## 📊 Exploratory Data Analysis (EDA)

### a) Market Trend Analysis
- EV sales show a **consistent upward trend**  
- **Two- and three-wheelers dominate** adoption  
- Cars and buses are growing steadily, especially in recent years  

### b) State-Wise Distribution
- Sales are **concentrated in leading states**: Delhi, Maharashtra, Karnataka, and Uttar Pradesh  
- **Different states favor different vehicle classes** (two-wheelers vs buses for public transport)  

### c) Market Share
- 🛵 Two-wheelers → Largest market share  
- 🛺 Three-wheelers → Second-largest, supporting shared/public mobility  
- 🚗 Cars & 🚌 Buses → Smaller but increasing shares  

---

## 🤖 Machine Learning for Sales Prediction

### Preprocessing
- **Categorical:** One-hot encoded (State, Vehicle_Class, etc.)  
- **Numerical:** Retained as-is (Year, etc.)  
- **Target:** EV_Sales_Quantity  

### Models Tested
- Linear Regression  
- Random Forest Regressor  
- Gradient Boosting Regressor  

### Evaluation Metrics
- RMSE (Root Mean Squared Error)  
- R² (Coefficient of Determination)  

---

## 📈 Results
- **Best Model:** Gradient Boosting Regressor  
- **RMSE:** ~261.3  
- **R²:** ~0.74 (explains ~74% of sales variance)  

### Model Insights
- Predictions align closely with actual sales trends  
- Some spikes under/overestimated  
- **Key Influencing Factors:**  
  - State (policy & adoption differences)  
  - Vehicle Type & Category  
  - Year (natural growth trend)  

---

## ✅ Conclusion & Recommendations

### Key Findings
- EV adoption is **accelerating rapidly** in India  
- Two- and three-wheelers **lead the market**  
- Adoption patterns **vary significantly across states**  
- **Policies and infrastructure** play a crucial role in driving adoption  

### Recommendations
1. **Expand charging infrastructure** in high-growth states  
2. **Encourage adoption of buses and cars** with targeted subsidies  
3. **Tailor EV policies state-wise** to account for regional variations  
4. **Leverage ML forecasting** for demand planning and policy evaluation  

---

## 📝 Summary (30 words)
This project analyzes EV sales in India, revealing rising adoption, state-wise growth, and dominance of two/three-wheelers. Using ML, sales forecasting achieves strong accuracy, highlighting policy and infrastructure as key enablers.  

