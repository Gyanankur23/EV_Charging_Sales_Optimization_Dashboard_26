# EV_Charging_Sales_Optimization_Dashboard_26 CaseCraft Analytics Project Sprint Project 26

## ⚡ Overview  
This project builds an EV charging station optimization dashboard using simulated session logs, charger metadata, and user preferences. It blends recommendation logic, energy analytics, and clean visual storytelling to support infrastructure planning and personalized station selection.

## 🎯 Objective  
To recommend optimal EV stations based on vehicle type and charger preference, while visualizing usage patterns, feedback, and energy consumption.

## 🔋 Dataset & Features  
- **Stations**: 20 entries with location, charger type, capacity, and install year  
- **Sessions**: 20 logs with vehicle type, duration, energy used, timestamp  
- **Users**: 20 profiles with region, vehicle type, subscription plan  
- **Feedback**: 20 ratings with comments  
- **Features**:  
  - `charger_type`, `vehicle_type`, `energy_kwh`, `duration_min`, `rating`, `region`

## 📊 Visual Explorations  
- **Count Plot**: Charger type distribution  
- **Pie Chart**: Energy consumption by vehicle type  
- **Scatterplot**: Station capacity vs energy usage  
- **Histogram**: Feedback rating distribution  
- **Heatmap**: Charging duration by station and vehicle type  
- **Recommendation Table**: Top stations by vehicle-charger match

## 🧠 Recommendation Logic  
- **Inputs**: Vehicle type + charger preference  
- **Filtering**: Match charger type  
- **Ranking**: Average energy usage per station  
- **Fallback**: Top 5 stations by charger type if no match found  
- **Output**: Station ID, location, charger type, capacity, avg energy

## 🧠 Key Insights  
1. **Fast Chargers**: Concentrated in Mumbai and Delhi, with high capacity  
2. **Energy Usage**: SUVs and Trucks consume the most per session  
3. **Feedback**: Skews positive, with 4–5 star dominance  
4. **Duration Heatmap**: Trucks take longest charging time  
5. **Recommendation Accuracy**: Aligns well with vehicle-charger preferences  
6. **Modular Design**: Reproducible logic and clean visuals support deployment

## ✅ Final Conclusion  
The EV dashboard delivers clarity-first recommendations using modular logic and strategic visuals. It supports charger upgrades, regional planning, and personalized station selection. Ready for real-world deployment or extension into predictive maintenance and dynamic pricing.