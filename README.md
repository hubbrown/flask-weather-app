# flask-weather-app
This is a Weather Monitor project built with Flask and Python. It provides real-time weather information based on user input. The application uses the OpenWeatherMap API to fetch weather data for any given location.

## Installation

1. Clone the repository to your local machine:
   git clone https://github.com/your-username/flask-weather-app.git

2. Navigate to the project directory:
   cd weatherapp

3. Create a virtual environment (optional but recommended):
   python3 -m venv env

4. Activate the virtual environment:
   - For Windows:
      env\Scripts\activate
   - For macOS/Linux:
      source env/bin/activate
5. Install the required dependencies:
    pip install -r requirements.txt

## Configuration

Before running this application, you need to obtain an API key from OpenWeatherMap. Follow these steps:

1. Visit the [OpenWeatherMap website](https://openweathermap.org) and sign up for a free account.

2. Once you have an account, navigate to the [API Keys](https://home.openweathermap.org/api_keys) page and generate a new API key.

3. Copy the generated API key.

4. Rename the `.env.example` file to `.env` in the project root directory.

5. Open the `.env` file and replace `YOUR_API_KEY_HERE` with the API key you obtained from OpenWeatherMap.

## Usage

1. Ensure that the virtual environment is activated.

2. Start the Flask development server withe command:
    flask run
    
3. Open your web browser and go to `http://127.0.0.1:5000/`.

4. Choose city, state and country, then click the "Get Weather" button.

5. The application will display the current weather information for the specified location.

## Features

- Real-time weather information
- Temperature in Celsius
- Weather description and icon


## Contributing

Contributions to this Weather App project are welcome. If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request on the [GitHub repository](https://github.com/your-username/weather-app).

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- [Flask](https://flask.palletsprojects.com) - Web framework used
- [OpenWeatherMap](https://openweathermap.org) - Weather data API
