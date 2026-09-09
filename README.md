# task3-hcl

# Weather Dashboard Application

## Project Description

This project is a Weather Dashboard Application that uses a public weather API to display current weather conditions based on the searched city.

## Features

* Search weather by city name
* Display current temperature
* Display feels-like temperature
* Display humidity
* Display wind speed and direction
* Display atmospheric pressure
* Display cloud cover
* Display weather condition
* Celsius/Fahrenheit temperature conversion
* Current location weather
* Weather-based animations
* Loading indicator
* Error handling for invalid cities and API/network errors
* Responsive user interface

## Technologies Used

* HTML5
* CSS3
* JavaScript
* Fetch API
* Promises
* Async/Await
* Open-Meteo Weather API

## API Integration

This project uses the Open-Meteo public API.

### Geocoding API

The geocoding API converts a city name into latitude and longitude.

### Weather API

The weather API uses latitude and longitude to retrieve the current weather information.

No API key is required.

## Asynchronous Programming

JavaScript `async` and `await` are used for API requests.

The main flow is:

```text
User enters city
       ↓
handleSearch()
       ↓
geocodeCity()
       ↓
Get latitude and longitude
       ↓
fetchWeather()
       ↓
Get current weather
       ↓
renderWeather()
       ↓
Display result
```

## Error Handling

The application handles:

1. Empty city input
2. Invalid city names
3. City not found
4. API request failure
5. Network errors
6. Invalid weather response
7. Loading state during API requests

JavaScript `try`, `catch`, and `finally` are used to handle errors safely.

## AI-Assisted Activity

AI tools were used as development assistance during this project.

### AI-Assisted API Integration

AI assistance was used to understand and implement:

* Open-Meteo API integration
* Fetch API requests
* Geocoding API
* Weather API
* Async/Await programming

### AI-Supported Debugging

AI assistance was used to:

* Analyze JavaScript errors
* Improve API error handling
* Check asynchronous programming
* Improve user-friendly error messages
* Debug weather data processing

### AI-Assisted Git Commit Messages

AI assistance was used to generate meaningful Git commit messages for different development stages.

Example commit messages:

```text
Initial weather dashboard implementation
Integrate Open-Meteo weather API
Add city search and geocoding
Implement asynchronous API handling
Add weather error handling
Add weather-based animations
Improve responsive dashboard design
Add project documentation
```

### AI-Assisted Documentation

AI assistance was used to organize the project documentation and explain:

* API integration
* Asynchronous programming
* Error handling
* Git workflow
* Project features

## Example AI Prompts Used

### API Integration

"Help me integrate the Open-Meteo weather API using JavaScript Fetch API and async/await."

### Debugging

"Analyze my JavaScript weather API code and identify possible errors in asynchronous API handling."

### Error Handling

"Improve the error handling for invalid city names and weather API failures."

### Git

"Generate meaningful Git commit messages for the development stages of my weather dashboard project."

### Documentation

"Create documentation explaining the API integration, asynchronous programming and error handling in my weather dashboard."

## Git Commands

Initialize Git:

```bash
git init
```

Add project files:

```bash
git add .
```

Create the first commit:

```bash
git commit -m "Initial weather dashboard implementation"
```

After making changes:

```bash
git add .
git commit -m "Integrate Open-Meteo weather API"
```

Continue with meaningful commits as the project develops.

## Expected Outcome

The completed application provides hands-on experience with:

* Public API integration
* Asynchronous JavaScript programming
* Fetch API
* Async/Await
* Error handling
* City-based weather search
* Git version control
* AI-assisted software development
* Technical documentation
