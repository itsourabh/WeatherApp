🌤️ Weather App – Real-Time Weather Data via API
This is a simple and responsive Weather App built using Python and OpenWeatherMap API. It fetches real-time weather information for any city entered by the user and displays key weather metrics such as temperature, humidity, wind speed, and weather conditions.

🚀 Features
🌍 Get real-time weather data for any city worldwide

📡 API integration using OpenWeatherMap

🌡️ Displays temperature, weather condition, humidity, and wind speed

💻 User-friendly interface with input validation

🔁 Converts temperature units (Kelvin → Celsius)

🧼 Clean and modular Python code

🛠️ Tech Stack
Python

Requests (HTTP API calls)

Tkinter (for GUI, optional) or CLI version

OpenWeatherMap API

📦 How It Works
User enters a city name

App sends a request to OpenWeatherMap API

API returns JSON response with weather data

Data is parsed and displayed in a clean format

🔧 Setup Instructions
Clone this repo

bash
git clone https://github.com/yourusername/weather-app.git
cd weather-app
Install dependencies

bash
pip install requests
Add your API key (from OpenWeatherMap) in the script

python
Copy
Edit
api_key = "your_api_key"
Run the app

bash
python weather_app.py


📌 Sample Output (CLI Version)
vbnet

City: New York
Temperature: 18.3°C
Condition: Light rain
Humidity: 82%
Wind Speed: 5.1 m/s

📁 Project Structure

├── weather_app.py
├── README.md
└── requirements.txt
