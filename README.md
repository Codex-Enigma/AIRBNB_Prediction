# 🏡 Airbnb Dynamic Pricing Recommendation Engine

## 📌 Objective  
Build a dynamic pricing recommendation engine for Airbnb listings by analyzing historical data and identifying key pricing drivers based on property type, city, reviews, and more.

---

## 🛠️ Tools Used  
- **Python**: Data cleaning, feature engineering, model building  
- **Tableau**: Visual dashboards and data storytelling  
- **Excel**: Quick checks and summary calculations

---
Link to Dashoboard - https://public.tableau.com/app/profile/pranay.mody/viz/Airbnb_17466031672600/AirbnbDashboard
![Airbnb Dashboard](https://raw.githubusercontent.com/Codex-Enigma/AIRBNB_Prediction/main/Airbnb%20Dashboard.png)

## 📈 Key Insights from Data Analysis

### Number of Listings by Top 10 Property Types
- **Apartments Dominate**: ~29,000 listings as "Entire home/apt" and ~18,000 as "Private room".
- **Houses Are Second Most Frequent**: ~8,000 as "Entire home/apt", ~2,000 as "Private room".
- **Other Property Types Are Less Common**: Condos, Lofts, Townhouses are far fewer in comparison.

### ⚡Instant Booking Availability by Room Type
- **High Availability for Entire Homes/Apts**: Most "Entire home/apt" listings offer instant booking.
- **Private Rooms Mostly Not Instantly Bookable**: Majority lack instant booking feature.
- **Shared Rooms Have Lowest Instant Booking Count**.

### 🧁 Listing Share by Room Type (Pie Chart)
- **Entire Homes/Apts**: 55.7% of all listings.
- **Private Rooms**: 41.3% of listings.
- **Shared Rooms**: Only 2.9%.

### ⭐ Avg Review Score by Property Type
- **High Review Scores Across Types**: Most above 95.
- **Little Variation**: Guests rate unique types like "Yurt", "Cave" similarly.
- **"Cave" Has Slightly Higher Avg Review**.

### 💬 Avg Price by Number of Reviews
- **Few Reviews = Higher Prices**: 0-10 reviews average ~$151.
- **More Reviews = Lower Prices (Up to 200)**: Down to ~$131.
- **500+ Reviews Spike Again**: Average price rises above ~$160.

### ✅  Price Comparison by Host Identity Verification
- **Verified Hosts Slightly Higher**: ~$162 vs ~$160 for unverified.
- **Minimal Price Difference**.
- **Most Listings Are Verified**.

### 🧳 Most Common Amenities (Word Cloud)
- **Top Amenities**: "Essentials", "Wireless Internet", "Air conditioning".
- **Frequent Safety Features**: "Smoke detector", "First aid kit".
- **Comfort Amenities Common**: "Hair dryer", "Laptop workspace", "Heating".

### 🏆 Top 20 Most Common Amenities (Bar Chart)
- **Wireless Internet**: Most frequent (~74,000).
- **Essential Comforts**: "Kitchen" (~68,000), "Heating" (~67,000), "Essentials" (~64,000).
- **Safety Features Prominent**: "Smoke detector" (~62,000), "CO detector" (~48,000).

---

## 💡 Correlation Analysis

### 📌 Strong Positive Correlation
- **Beds, Bedrooms, Accommodates**: Strongly correlated—larger listings host more guests.

### 📌 Moderate Positive Correlation with Price
- **Beds, Bedrooms, Bathrooms, Accommodates**: Moderately correlated with price—more amenities = higher price.

### 📌 Weak or No Correlation
- **Review Scores & Host Response Rate**: Very weak/no correlation with price or other numeric features.

---

## 💰 Price Distribution Analysis

### 📈 Distribution of Price
- **Right-Skewed**: Most listings priced < $250.
- **Long Tail**: High-end listings are rare but exist.
- **Concentration at Lower Prices**: Majority are budget-friendly.

---

## 🏠 Room Type Analysis

### 📊 Price by Room Type (Box Plot)
- **Entire Home/Apt**: Highest median price, largest variability.
- **Private Room**: Intermediate price, moderate variability.
- **Shared Room**: Lowest median price, narrow range.

### 📉 Avg Price by Room Type (Bar Chart)
- **Entire Home/Apt**: Avg ~$120+
- **Private Room**: Avg ~$50–90
- **Shared Room**: Avg ~$30–60

---

## 🌍 Location-Based Pricing

### 📍 Image: Avg Price by Top 10 Cities
- **San Francisco & DC**: Highest prices (SF ~ $392).
- **Chicago**: Lowest (~$161).
- **Huge Variability**: SF is > 2x Chicago price.

---

## 🤖 Model Performance

> ✅ The model can predict with **63.50% accuracy** within **±20% error**.

---

## 📊 Deliverables
- ✅ **Tableau Dashboard** with filters & interactive pricing visuals  
- ✅ **Python Pricing Engine** with regression model  
- ✅ **PDF Report** summarizing insights & recommendations

---

## 🧭 Conclusion
- Airbnb pricing is influenced by room type, city, size, and property features.
- Verified hosts and review scores have limited effect on pricing.
- Amenities and instant booking options align with guest expectations.
- The model offers a reliable foundation for dynamic pricing suggestions.
