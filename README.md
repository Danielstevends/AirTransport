# AirTransport Calculator

This repository calculates operational variables, comparing air taxi vehicles and ground transportation. It features sliders to customize variables such as fuel consumption, emissions, and more. As input, the application uses the Google Maps API to determine distances and travel times.

Feel free to use this repository and credit my name if you find it helpful for your project.

---

## Features

- **Customizable Sliders**: Adjust variables such as fuel consumption and emissions.
- **Google Maps Integration**: Automatically calculates distances and travel times using the Google Maps API.
- **Final Output Visualization**: See detailed results of your calculations.

---

## Prerequisites

### Google Maps API Key
To use this repository, you will need a valid Google Maps API key. Follow these steps to obtain your API key:

1. Go to the [Google Cloud Console](https://console.cloud.google.com/).
2. Create a new project (or select an existing one).
3. Enable the "Google Maps JavaScript API" and "Google Distance Matrix API" for your project.
4. Go to the "Credentials" page and create an API key.
5. Replace `YOUR_API_KEY` in the code with your actual API key.

### Code Snippet for Google Maps API Integration
```python
API_KEY = 'YOUR_API_KEY'  # Replace 'YOUR_API_KEY' with your actual Google Maps API key
import googlemaps

# Initialize the Google Maps client
gmaps = googlemaps.Client(key=API_KEY)
```

Final Results:
Sliders to adjust variables:

<img width="716" alt="image" src="https://github.com/Danielstevends/AirTransport/assets/45707023/9ea261a2-4dae-447a-898c-ae914ff4de18">


This is the expected final output after running this:

<img width="565" alt="image" src="https://github.com/Danielstevends/AirTransport/assets/45707023/334da73e-9055-4e1d-bd87-8e535569057c">
