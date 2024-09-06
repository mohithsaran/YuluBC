# **YULU Business Case Study**

Colab link: https://colab.research.google.com/drive/1BCOsj4cSUMdkX89P_SRewu2mQDniHPHy?usp=sharing

Yulu is India’s leading micro-mobility service provider, which offers unique vehicles for the daily commute. Starting off as a mission to eliminate traffic congestion in India, Yulu provides the safest commute solution through a user-friendly mobile app to enable shared, solo and sustainable commuting.

Yulu zones are located at all the appropriate locations (including metro stations, bus stands, office spaces, residential areas, corporate offices, etc) to make those first and last miles smooth, affordable, and convenient!

Yulu has recently suffered considerable dips in its revenues. They have contracted a consulting company to understand the factors on which the demand for these shared electric cycles depends. Specifically, they want to understand the factors affecting the demand for these shared electric cycles in the Indian market.

## **Business Problem**

The company wants to know:

Which variables are significant in predicting the demand for shared electric cycles in the Indian market?
How well those variables describe the electric cycle demands

### **Column Profiling:**

- datetime: datetime
- season: season (1: spring, 2: summer, 3: fall, 4: winter)
- holiday: whether day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
- workingday: if day is neither weekend nor holiday is 1, otherwise is 0.
- weather:
    1. Clear, Few clouds, partly cloudy, partly cloudy
    2. Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
    3. Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
    4. Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- temp: temperature in Celsius
- atemp: feeling temperature in Celsius
- humidity: humidity
- windspeed: wind speed
- casual: count of casual users
- registered: count of registered users
- count: count of total rental bikes including both casual and registered

## **Recommendations**

- **Weather-Based Pricing Strategy:**

    - Increase Rental Prices During Favorable Weather: Since demand varies significantly, rental prices could be adjusted based on the weather forecast. Higher prices could be charged during clear or misty weather conditions when demand is likely higher.
- **Discounts During Poor Weather:**
    - Offer discounts during light snow/rain or heavy rain/snow conditions to encourage rentals despite the less favorable weather.

- **Real-Time Notifications:**
    - Use real-time weather data to send notifications to users, encouraging them to rent bikes during favorable weather. Conversely, inform users about promotions during less favorable weather to maintain engagement.

- It indicates the demand in bicycle gets impacted by season. It is advisable to adjust the number of available bikes seasonally. For example, if demand is higher in the summer and fall, the company should increase the number of bikes available during these periods to meet the higher demand.
- The company can implement dynamic pricing based on seasonal demand. Higher prices can be charged during peak seasons to maximize revenue, while discounts can be offered during off-peak seasons to encourage more usage.

- - **Seasonal Planning:**

    - **Inventory and Resource Management:** Since weather and seasons are dependent, it's essential to align bike availability with expected weather patterns. For instance, if winter often brings poor weather, you might reduce bike availability or offer promotions to encourage rentals during these times.
- **User Experience Enhancement:**

    - **Weather-Dependent Offers:** Create special offers or incentives that take into account the likely weather in each season. For instance, offering discounts on rainy days in autumn could maintain demand during less favorable conditions.
- **Predictive Analytics:**
    - Use historical data on weather and seasons to predict future demand and adjust operations accordingly. This could include staffing, bike maintenance schedules, and customer service adjustments.
