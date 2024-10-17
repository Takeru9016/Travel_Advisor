# Travel Advisor

This project is a travel companion web application that allows users to search for restaurants, hotels, and attractions based on their location. It leverages Google Maps and RapidAPI to provide accurate, real-time data for various travel destinations.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Features

- **Location-Based Search**: Search for restaurants, hotels, and attractions near your current location.
- **Google Maps Integration**: Interactive map with markers for destinations, allowing users to explore visually.
- **API Integration**: Fetch data from multiple APIs (RapidAPI for travel data, OpenWeather for weather conditions).
- **Geolocation Support**: Automatically detects user location for more relevant results.
- **Weather Forecasting**: Includes real-time weather updates for selected destinations.

## Technologies

- **Frontend**:
  - React.js
  - Material-UI (for UI components and styling)
  - Axios (for API requests)
  - Google Maps API (for interactive maps)
  - RapidAPI (for restaurant, hotel, and attraction data)

- **Backend**:
  - No backend is needed since the project is powered by third-party APIs.

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Takeru9016/Travel_Advisor.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd Travel_Advisor
   ```
3. **Install the dependencies**:
   ```bash
   npm install
   ```
4. **Run the application**:
   ```bash
   npm start
   ```
   This will start the development server. To view the app, navigate to `http://localhost:3000` in your browser.

## Usage

1. **View Travel Destinations**: Explore various restaurants, hotels, and attractions near your current location.
2. **Use the Map**: Click on map markers to get more information about specific locations.
3. **Check Weather Conditions**: View the current weather for any location using the integrated weather API.

## Contributing

Contributions are welcome! If you'd like to improve the project or fix bugs, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.
