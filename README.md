# Weather Forecast Webpage

This project gathers weather forecast data using the NOAA API and creates an HTML page that contains information regarding the forecast.

## Features
- Gather weather forecast data using latitude and longitude.
- Save forecast data to a text file.
- Create an HTML page displaying the forecast data in a tabular format.

## Requirements
- Python 3.x
- `requests` library

## Setup

1. Clone the repository:
    git clone https://github.com/your-username/weather-forecast-webpage.git
    cd weather-forecast-webpage


3. Create and activate a virtual environment:
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`

4. Install the required packages:
    pip install requests

## Usage

1. Replace the `latitude` and `longitude` values in `your_script_name.py` with the desired coordinates.

2. Run the script:
    python your_script_name.py


3. The script will:
    - Gather the weather forecast data from the NOAA API.
    - Save forecast information in `forecast.txt`.
    - Create an HTML file `weatherForecast.html` to show forecast information.