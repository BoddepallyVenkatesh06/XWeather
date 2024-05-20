# XWeather

XWeather is a comprehensive weather application that provides current weather conditions, forecasts, and other meteorological data for any location. It is built using modern web technologies and can be easily integrated into any web application.

## Table of Contents 📚

- [Introduction🚀](#introduction)
- [Features🛠️](#features)
- [Screenshot📷](#screenshot)
- [Getting Started🎯](#getting-started)
- [Prerequisites📋](#prerequisites)
- [Installation⚙️](#installation)
- [Usage📈](#usage)
- [API Endpoints🔌](#api-endpoints)
- [Contributing❤️](#contributing)
- [License📝](#license)

## Introduction🚀

XWeather is designed to provide accurate and up-to-date weather information. Whether you need current weather data, hourly forecasts, or long-term predictions, XWeather has you covered with a user-friendly interface and detailed meteorological data.

## Features🛠️

- Current weather conditions
- 7-day weather forecast
- Hourly weather updates
- Weather alerts and notifications
- Detailed weather metrics (temperature, humidity, wind speed, etc.)
- Responsive design for all devices

## Screenshot📷

![XWeather App](https://github.com/BoddepallyVenkatesh06/XWeather/blob/main/Screenshot_XWeather.png)

## Getting Started🎯

### Prerequisites📋

Before you begin, ensure you have the following installed on your system:
- Node.js
- npm (Node Package Manager)

### Installation⚙️

1. Clone the repository:

```bash
git clone https://github.com/BoddepallyVenkatesh06/XWeather.git
cd xweather
```

2. Install dependencies:

```bash
npm install
```

3. Set up environment variables:

Create a `.env` file in the root directory and add the following variables:

```env
REACT_APP_WEATHER_API_KEY=your_api_key
REACT_APP_WEATHER_API_URL=https://api.weatherapi.com
```

## Usage📈

To start the development server, run:

```bash
npm start
```

This will start the application in development mode at `http://localhost:3000`.

## API Endpoints🔌

### Get Current Weather

- **URL:** `/api/weather/current`
- **Method:** `GET`
- **Query Parameters:**
  - `location` (string, required): The location to get weather data for.

- **Response:**
  - `200 OK` with current weather data
  - `400 Bad Request` on validation error

### Get 7-Day Forecast

- **URL:** `/api/weather/forecast`
- **Method:** `GET`
- **Query Parameters:**
  - `location` (string, required): The location to get forecast data for.

- **Response:**
  - `200 OK` with 7-day forecast data
  - `400 Bad Request` on validation error

## Contributing❤️

Contributions are welcome! If you'd like to contribute to XWeather, please follow these steps:

1. Fork the project.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

## License📝

```
MIT License

Copyright (c) 2024 Venky Kumar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
