
Developing a real-time data processing system to monitor weather conditions and provide summarized insights using rollups and aggregates. The system will utilize data from the
OpenWeatherMap API

# Weather Data Retrieval and Analysis System

![image](https://github.com/user-attachments/assets/34f4174f-7862-4be5-8f96-47386b0586a0)



## Overview

This project is designed to retrieve weather data from the OpenWeatherMap API at configurable intervals, convert temperature values based on user preference, and provide daily weather summaries including additional parameters like humidity and wind speed. The system is built to be robust, easy to set up, and extendable.

## Features

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

## Requirements
- Screen 1070*680 minimum
- Nodejs (optional in case system do not have live server utility)

## Getting Started

### Prerequisites

- Node.js and npm installed

### Installation

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
