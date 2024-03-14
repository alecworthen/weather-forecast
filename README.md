## Overview

Weather Forecast is a web application designed to provide users with a convenient way to access weather forecasts for multiple cities. Leveraging the OpenWeatherMap API, the dashboard dynamically fetches and displays current weather conditions and a 5-day forecast based on user-provided city names. With a clean and intuitive interface, users can quickly obtain essential weather information to plan their trips effectively.

## User Story

As a traveler,
I want to access weather forecasts for multiple cities
So that I can plan my trips accordingly.

## Acceptance Criteria

Given a weather dashboard with form inputs,
When I search for a city,
Then I should be presented with current and future weather conditions for that city, and the city should be added to the search history.
When I view the current weather conditions for a city,
Then I should see the city name, date, weather icon, temperature, humidity, and wind speed.
When I view the future weather conditions for a city,
Then I should see a 5-day forecast displaying the date, weather icon, temperature, humidity, and wind speed.
When I click on a city in the search history,
Then I should be presented with current and future weather conditions for that city.

## Features

- Search for weather forecasts by city name.
- Display current weather conditions including temperature, humidity, and wind speed.
- Present a 5-day forecast with weather details for each day.
- Store search history for easy access to previously searched cities.


## Usage

1. Visit the [Weather Dashboard]() webpage.
2. Enter the name of a city in the search field.
3. Click the "Search" button.
4. View the current weather conditions and 5-day forecast for the entered city.
5. Repeat the process to search for weather information for additional cities.

## Installation

To run the Weather Dashboard locally, follow these steps:

1. Clone this repository to your local machine using `git clone`.
2. Open the cloned repository in your preferred code editor.
3. Start a local server or simply open the `index.html` file in a web browser.

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- OpenWeatherMap API
- localStorage

## What I Learned

During the development of this project, I gained experience in:

- Integrating third-party APIs to retrieve weather data.
- Dynamically updating the DOM based on API responses.
- Utilizing localStorage to store and manage user search history.
- Enhancing the user experience through intuitive design and functionality.

## Future Enhancements

In future iterations, I plan to implement the following enhancements:

- Dark mode/light mode toggle for improved accessibility.
- Incorporation of additional weather data such as precipitation and UV index.
- Optimization of the user interface for a more polished look and feel.

## Contact

For inquiries or feedback, feel free to contact me at [alecworthen@gmail.com](mailto:alecworthen@gmail.com).
