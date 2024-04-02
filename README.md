# Weather Monitoring System

This is a Weather Monitoring System built using Node.js, integrating with the DarkSky Weather API and the Google Places API. It allows users to retrieve weather information for a specified location.

## Features

- Retrieve current weather conditions for a specific location.
- Obtain detailed weather forecasts including temperature, humidity, wind speed, etc.
- Search for weather information by providing a location name or coordinates.

## Installation

To run this Weather Monitoring System locally, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/swapnildubey29/Weather-App.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Weather-App
   ```

3. Install dependencies using npm:

   ```bash
   npm install
   ```

4. Obtain API keys for DarkSky Weather API and Google Places API. You can sign up for API keys at the following links:
   - [DarkSky Weather API](https://darksky.net/dev)
   - [Google Places API](https://developers.google.com/places/web-service/get-api-key)

5. Create a `.env` file in the root directory of the project and add your API keys:

   ```plaintext
   DARKSKY_API_KEY=your-darksky-api-key
   GOOGLE_PLACES_API_KEY=your-google-places-api-key
   ```

## Usage

Once you have installed the dependencies and set up your API keys, you can run the Weather Monitoring System using the following command:

```bash
npm run dev
```

The system will prompt you to enter a location. You can enter the name of a city, a specific address, or even coordinates (latitude and longitude). After providing the location, the system will fetch and display the current weather information for that location.

## Example

Here's an example of how to run the Weather Monitoring System:

1. After navigating to the project directory and installing dependencies, run:

   ```bash
npm run dev
```

2. The system will prompt you to enter a location. For example, you can enter "New York" or "40.7128,-74.0060" for the coordinates of New York City.

3. Press Enter, and the system will display the current weather conditions for the specified location.

## Credits

- **DarkSky Weather API**: [https://darksky.net/dev](https://darksky.net/dev)
- **Google Places API**: [https://developers.google.com/places/web-service/get-api-key](https://developers.google.com/places/web-service/get-api-key)

## 
