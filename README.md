# WeatherTrackerApp
A Swift iOS app to display weather information using the WeatherAPI


The Weather App allows users to view and search for the weather of different cities. Key features include displaying current weather data for a saved city, searching for new cities, and storing the selected city for future use.

Functionality Implemented

Home Screen:

* Displays weather data for a saved city, including:
  
1. City name, temperature, weather condition (with an icon), humidity, UV index, and feels-like temperature.
2. If no city is saved, prompts the user to search for one.
3. Search bar for querying new cities.

* Search and Selection:

1. Search results show a card with the city’s weather data.
2. Tapping a search result updates the Home Screen with the selected city’s weather.

* Local Storage:

1. The selected city is saved using UserDefaults.
2. On app launch, the weather for the saved city is automatically loaded.

* API Integration
  
1. The app fetches weather data from WeatherAPI.com, which provides:

==> Temperature, weather condition (with icon), humidity, UV index, and feels-like temperature.

* Tech Stack :-
  
Language: Swift
UI: UIKit
Persistence: UserDefaults
API: WeatherAPI.com

