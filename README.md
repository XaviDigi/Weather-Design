# ☀️🌧️ Weather Design 🌩️❄️

A **Streamlit**-powered Python application that fetches real-time weather data and displays it in an interactive interface. Users can easily input a city to get the current weather, all with a sleek and modular design.

![Weather App](https://img.shields.io/badge/Weather-App-blue?style=for-the-badge&logo=python) ![Streamlit](https://img.shields.io/badge/Built%20with-Streamlit-red?style=for-the-badge&logo=streamlit) ![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 🌟 Features

- 🔥 **Real-time weather data**: Fetches live data using an API.
- 🌍 **City-based search**: Users can input any city to get weather details.
- 🖥️ **Interactive web interface**: Powered by Streamlit for a smooth user experience.
- 🛠️ **Modular design**: Easy to extend and maintain.

---

## 📂 Project Structure

    ```bash
    Weather-Design/
    ├── src/
    │   └── weather_app/
    │       ├── __init__.py       # Initializes the package
    │       ├── __main__.py       # Main script to run the app
    │       ├── constants.py      # API key and constants
    ├── pyproject.toml            # Project metadata
    ├── README.md                 # This file
    └── requirements.txt          # Python dependencies

🚀 How to Run
1. Clone the repository:
     ```bash
    git clone https://github.com/your-username/weather-design.git
    cd weather-design
2. Install dependencies: Make sure you have Python installed. Then, install the required packages:
   ```bash
   pip install -r requirements.txt
4. Run the Streamlit app:
   ```bash
   streamlit run main.py

🔧 Configuration
Add your weather API key in src/weather_design/constants.py:

    API_KEY = "your_api_key_here"

You can get an API key from OpenWeather.

🛠️ Technologies Used:

Python 🐍
Streamlit 🎈
OpenWeather API 🌤️


