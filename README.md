# weather-streamlit-with-python
A real-time, interactive weather dashboard built using Python and Streamlit. This app allows users to enter a city name and get real-time weather updates, including temperature, humidity, and wind speed, for the next 12 to 48 hours. The data is pulled from the Open-Meteo API, with city name geolocation provided by Nominatim (OpenStreetMap).

Weather Dashboard Screenshot

📋 Features
Real-Time Weather Data: Fetches hourly temperature, humidity, and wind speed data.
City Search: Users can enter any city name to get weather data.
Customizable Graphs: Select forecast duration and display only chosen weather parameters.
Clean Summary View: Presents the latest temperature, humidity, and wind speed in a metric format.
🚀 Getting Started
Prerequisites
Ensure you have Python 3.7+ and pip installed.

Installation
Clone the Repository

git clone https://github.com/manikolbe/city_weather_dashboard_streamlit_example.git
cd city_weather_dashboard_streamlit_example
Install Required Packages

pip install -r requirements.txt
Note: If there’s no requirements.txt, create one by listing the dependencies:

streamlit
requests
pandas
Run the App
In the project directory, run:

streamlit run city_weather_dashboard.py
The app will open in a new browser tab at http://localhost:8501.

🌎 Usage
Enter a City Name: Type the city name (e.g., "San Francisco") in the input field.
Select Forecast Duration: Use the slider to choose between 12 to 48 hours.
Choose Parameters: Select which weather metrics to display: temperature, humidity, or wind speed.
Get Results: Press "Get Weather Data" to fetch and display data.
The app will show:

Line charts for each selected metric over the chosen duration.
A real-time summary of the current temperature, humidity, and wind speed.
📚 Project Structure
weather_dashboard.py: Main app code.
requirements.txt: List of Python dependencies.
README.md: Project documentation.
📦 APIs Used
Open-Meteo API: For real-time weather data.
Nominatim API (OpenStreetMap): For converting city names to coordinates.
🎉 Acknowledgments
OpenStreetMap & Nominatim for their free and open geolocation API.
Open-Meteo for providing real-time weather data.
