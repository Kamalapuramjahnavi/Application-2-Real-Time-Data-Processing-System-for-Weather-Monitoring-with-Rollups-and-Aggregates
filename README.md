# Weather Data Retrieval and Analysis System

<img width="960" alt="image" src="https://github.com/user-attachments/assets/2c4fc70a-9633-485e-a3d6-aef57359b81a">

Hosted link: https://santosh-2003-sahoo.github.io/App2-Weather-app/

# Real-Time Weather Monitoring System

## Objective

The objective of this project is to develop a real-time data processing system that monitors weather conditions and provides summarized insights using rollups and aggregates. The system retrieves data from the OpenWeatherMap API, focusing on key weather parameters such as temperature and weather conditions.

## Features

**Real-Time Data Retrieval**: Continuously fetches weather data from the OpenWeatherMap API every 5 minutes.
- **Temperature Conversion**: Converts temperature values from Kelvin to Celsius.
- **Daily Weather Summary**: Calculates daily aggregates including average, maximum, and minimum temperatures, along with the dominant weather condition.
- **Alerting Thresholds**: Configurable thresholds for temperature alerts.
- **Data Visualization**: Displays daily weather summaries and historical trends using visualizations.
- **System Setup:** Initializes and connects to the OpenWeatherMap API using a valid API key.
- **Data Retrieval:** Simulates API calls at configurable intervals to retrieve and parse weather data for specified locations.
- **Temperature Conversion:** Converts temperature values from Kelvin to Celsius or Fahrenheit based on user preference.
- **Daily Weather Summary:** Simulates weather updates over several days and calculates average, maximum, minimum temperatures, and dominant weather conditions.
- **Additional Parameters:** Supports retrieval and analysis of additional weather parameters such as humidity and wind speed.
- **5 days Weather Forecast** 

## Design Choices

- **Modularity:** The system is divided into distinct modules for initialization, data retrieval, temperature conversion, and summary generation, making it easy to maintain and extend.
- **Configurability:** API call intervals and temperature units are configurable to allow flexibility.
- **Extensibility:** Designed to easily incorporate additional weather parameters from the OpenWeatherMap API.

## Data Source

The system utilizes the OpenWeatherMap API. You will need to sign up for a free API key to access the data. The API provides various weather parameters, including:

- `main`: Main weather condition (e.g., Rain, Snow, Clear)
- `temp`: Current temperature in Centigrade
- `feels_like`: Perceived temperature in Centigrade
- `dt`: Time of the data update (Unix timestamp)

## Installation

### Prerequisites

- Python 3.7 or higher
- SQLite (or any other database of your choice)

### Dependencies

Install the required Python libraries using pip:


1. **Clone the Repository**
   ```bash
   git clone "https://github.com/Santosh-2003-sahoo/App2-Weather-app.git"
   cd App2-Weather-app
   ```

2. **Install Backend Dependencies**

   ```bash
   npm install
   
   ```
   
3. **run live server

   ```bash
   npm install http-server -g
   http-server -p 8080**
   ```

## Running Tests

You can add and run tests to ensure everything is working correctly.
```
created bt: santosh sahoo
