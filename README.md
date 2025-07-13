# 🌦️ Weather Dashboard | Power BI Project

A real-time, interactive **Weather Dashboard** built using **Power BI** and **WeatherAPI**, visualizing live weather metrics, air quality index, and forecasts across 10 major Indian cities. This project demonstrates strong data visualization, integration of APIs with Power BI, and dashboard design best practices.

<img src="./Snapshot of Weather Dashboard _ Mumbai.png">

---

## 📌 Features

- 🔄 **Real-Time Weather Data** using [WeatherAPI](https://www.weatherapi.com/)
- 🏙️ Covers **10 Popular Indian Cities** (e.g., Mumbai, Delhi, Lucknow)
- 🌡️ Current Temperature, Mist/Fog Indicators
- 💧 Humidity, 🌬️ Wind Speed, 🌫️ Visibility, 🌞 UV Index, 🌧️ Precipitation
- 📊 **7-Day Weekly Forecast** with Line Charts
- 🕓 Sunrise and Sunset Times
- 💨 **Air Quality Index (AQI)** Components:
  - PM10, PM2.5
  - SO₂, NO₂, CO, O₃
  - Color-coded indicators (Green, Yellow, Red)
- ☔ **Chances of Rain** bar charts for upcoming days
- 🧭 Intuitive layout with slicers to switch between cities

---

## 📊 Technologies Used

| Tool/Tech        | Description                                 |
|------------------|---------------------------------------------|
| Power BI         | Main dashboard creation and visualization   |
| WeatherAPI       | Real-time weather & AQI data source         |
| Power Query      | For fetching and transforming API data      |
| DAX              | Calculated fields and KPIs                  |

---

## 🚀 How It Works

1. **API Integration**: WeatherAPI endpoints are used to fetch live data (temperature, AQI, forecast).
2. **Data Transformation**: Data is cleaned, formatted, and structured using Power Query Editor.
3. **Dashboard Design**: Multiple Power BI visuals used for dynamic and clean UX.
4. **City Selection**: Users can switch between 10 cities using buttons/slicers.
5. **Responsive Forecast Graphs**: Weekly trends rendered using line charts.
6. **Color-Coded AQI Display**: Follows Indian AQI guidelines (Green = Good, Yellow = Moderate, Red = Unhealthy).

---

## 📸 Preview

<img src="./Snapshot of Weather Dashboard _ Ahmedabad.png" alt="Weather Dashboard Screenshot" width="800"/>
<img src="./Snapshot of Weather Dashboard _ Chennai.png" alt="Weather Dashboard Screenshot" width="800"/>
<img src="./Snapshot of Weather Dashboard _ Mumbai.png" alt="Weather Dashboard Screenshot" width="800"/>

---

## 🗂️ File Structure

📁 Weather Dashboard Repository  
├── 📄 README.md                               # Project Documentation  
├── 📷 Snapshot of Weather Dashboard _ Mumbai.png   # Dashboard Screenshot  
└── 📄 Weather Dashboard.pbit                  # Power BI Template File

---

## 📈 Use Cases

- 📍 Location-based weather insights
- 🏫 Educational tool for learning Power BI & APIs
- 🧪 Environmental monitoring visualizations
- 📊 Data storytelling and portfolio showcase

---

## 🛠️ Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/Anushka-Sharma-008/WeatherDashboard.git
2. Open the .pbit file in Power BI Desktop.
3. Replace API Key placeholders (if any) with your WeatherAPI key.
4. Refresh data to load real-time weather details.
5. Explore the dashboard and switch cities using the interface.
- ⚠️ Note: You may need a free WeatherAPI key from [WeatherAPI](https://www.weatherapi.com/)

---

## 📌 Notes
- AQI classification is based on real Indian environmental standards.
- Dashboard is optimized for desktop view.
- WeatherAPI allows limited free calls per day (consider caching if needed).

---

## 🙋‍♀️ Author

**Anushka Sharma**  
🌐 [LinkedIn](https://www.linkedin.com/in/anushkasharma008/) • 🐱 [GitHub](https://github.com/Anushka-Sharma-008) 
🎓 Learning Data Science, Analytics & Machine Learning

---

## ⭐ Show Your Support

If you found this project helpful or inspiring:

- ⭐ Star this repository  
- 🛠️ Fork it and add your own city or country  
- 💬 Share feedback or suggestions via Issues/Discussions
