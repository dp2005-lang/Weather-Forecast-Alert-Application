# Weather-Forecast-Alert-Application
🌦 Weather AI Dashboard — Open-Meteo Powered Weather Forecast System

A modern, real-time Weather Forecast & Alert Dashboard built using Python, Streamlit, and Open-Meteo API.
This project delivers live weather updates, 7-day forecasts, visual analytics, alerts, and interactive maps in a clean, professional UI similar to modern mobile weather applications.

🚀 Project Overview

The Weather AI Dashboard is an intelligent weather monitoring system that fetches real-time weather data from the Open-Meteo API and transforms it into meaningful insights.

It helps users:

Track weather conditions across multiple cities 🌍
View temperature and wind trends 📈
Get automated weather alerts 🔔
Visualize locations on interactive maps 🗺️
Analyze short-term weather forecasts 🌦
🎯 Problem Statement

People often rely on basic weather apps that only show raw data.
This project solves that by:

✔ Converting weather data into insights
✔ Adding alert-based intelligence
✔ Supporting multiple cities at once
✔ Visualizing data in a dashboard format

✨ Key Features
🌍 Multi-city weather tracking
📈 24-hour temperature & wind trend charts
🔔 Smart alerts (Heat / Rain / Normal conditions)
🗺️ Interactive city map visualization
📊 Clean analytics dashboard UI
📱 Mobile-responsive Streamlit interface
☁️ Powered by Open-Meteo (free weather API)
🛠️ Tech Stack
Python 🐍
Streamlit 🎈
Open-Meteo API 🌍
Pandas 📊
Plotly 📈
Folium 🗺️
Requests 🌐
🏗️ Project Workflow
User selects cities
        ↓
Open-Meteo API fetches weather data
        ↓
Data is processed using Python (Pandas)
        ↓
Alert system evaluates conditions
        ↓
Graphs + Maps + Metrics are generated
        ↓
Streamlit dashboard displays results
📊 Sample Outputs
Temperature trend graph 📈
Wind speed visualization 🌬️
Rainfall summary 🌧️
City-based map markers 🗺️
Weather alert banners 🔔
⚙️ How to Run
# Install dependencies
pip install streamlit requests pandas plotly folium streamlit-folium

# Run the app
streamlit run app.py
📁 Project Structure
Weather-AI-Dashboard/
│
├── app.py                 # Main Streamlit application
├── requirements.txt      # Dependencies
├── README.md             # Documentation
└── assets/               # Images/screenshots (optional)
💡 Key Learnings
API integration using Python
Real-time data processing
Dashboard development using Streamlit
Data visualization with Plotly
Map-based visualization using Folium
Alert system logic design
📌 Future Improvements
🌫 Add AQI (Air Quality Index) integration
📲 Add SMS / Email alerts
🤖 AI-based weather prediction
📍 Auto-detect user location
⚡ Deploy on cloud (AWS / Render / HuggingFace Spaces)
👨‍💻 Author

Developed by: Debankita Panja Project (Python Developer Track)
Focus Areas: API Integration | Data Visualization | Dashboard Development

⭐ If you like this project

Give it a ⭐ on GitHub and connect for more AI + Python + Dashboard projects.
