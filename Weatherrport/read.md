This project is a Graphical Weather Application developed using Python. It provides real-time weather information for any city using data fetched from the OpenWeather API.
The application features a simple and user-friendly interface built with Tkinter, making it easy for users to check weather conditions quickly.
🚀 Features
🌍 Search weather by city name
🌡 Displays temperature in Celsius
💧 Shows humidity levels
🌬 Displays wind speed
☁ Shows weather condition (clear, cloudy, etc.)
❗ Error handling for invalid city names
🖥️ GUI-based interface using Tkinter
🛠️ Technologies Used
Python
Tkinter (GUI)
Requests (API integration)
📁 Project Structure
Weather-App/
│
├── weather_app.py        # Main Python application
├── README.md             # Project documentation
└── requirements.txt      # Dependencies (optional)
🧪 Sample Input
User enters a city name in the input field:
Hyderabad
📤 Sample Output
📍 Hyderabad, IN
🌡 Temperature: 32°C
💧 Humidity: 65%
🌬 Wind Speed: 4.2 m/s
☁ Condition: Clear sky
👉 If invalid city:
Error: city not found
🧠 How It Works
The app uses requests library to call the API
Data is received in JSON format
Required fields (temperature, humidity, etc.) are extracted
Tkinter GUI displays the results
License
This project is licensed under the MIT License.
Author
Badduri Lakshmi Hemalatha Reddy
