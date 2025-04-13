# Weather Forecast Dashboard

A comprehensive weather forecasting system that combines real-time data with historical analysis to provide accurate weather predictions.

## Features

### 1. Current Weather
- Real-time weather data from WeatherAPI.com
- City search functionality
- Live updates of:
  - Temperature
  - Humidity
  - Wind Speed
  - Pressure
  - Precipitation
- 24-hour trend visualization
- Weather condition indicators

### 2. Historical Analysis
- Temperature trend analysis
- Weather metrics comparison
- Weather patterns analysis
- Customizable date range selection
- Interactive visualizations

### 3. Weather Prediction
- Future weather forecasts
- Machine learning-based predictions
- Customizable prediction period
- Confidence scores
- Multiple weather metrics prediction

## Technical Stack

- **Frontend**: Streamlit
- **Data Processing**: Pandas, NumPy
- **Visualization**: Plotly
- **Machine Learning**: Scikit-learn
- **API Integration**: WeatherAPI.com
- **Data Storage**: CSV, API

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/hastibhalodia/Xto10X_Hackathon_Weather_Forecast
   cd weather_forecast_HAC
   ```

2. **Create virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure API Key**
   - Create a `.streamlit/secrets.toml` file
   - Add your WeatherAPI.com key:
     ```toml
     [weather_api]
     api_key = "845fbd885adf4f2eb2e70629251204"
     ```

5. **Run the dashboard**
   ```bash
   python -m streamlit run src/dashboard/app.py
   ```

## Project Structure

```
weather_forecast_HAC/
├── src/
│   ├── dashboard/
│   │   └── app.py
│   ├── models/
│   │   ├── evaluation.py
│   │   └── prediction.py
│   └── utils/
│       └── weather_api.py
├── data/
│   └── Weather_Prediction_Updated.csv
├── .streamlit/
│   └── secrets.toml
├── requirements.txt
└── README.md
```

## Data Sources

1. **Real-time Data**: WeatherAPI.com
   - Current weather conditions
   - Forecast data
   - Location-based weather

2. **Historical Data**: Weather_Prediction_Updated.csv
   - Temperature records
   - Weather conditions
   - Meteorological metrics

## Usage

1. **Current Weather Tab**
   - Search for any city
   - View real-time weather metrics
   - Analyze 24-hour trends
   - Monitor weather conditions

2. **Historical Analysis Tab**
   - Select date range
   - Compare weather metrics
   - Analyze temperature trends
   - Study weather patterns

3. **Weather Prediction Tab**
   - Choose prediction period
   - View forecasted conditions
   - Analyze prediction confidence
   - Compare with historical data

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## Youtube Video Link

https://www.youtube.com/watch?v=-KD6pH_z1QU

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- WeatherAPI.com for real-time weather data
- Streamlit for the dashboard framework
- Scikit-learn for machine learning capabilities
- Plotly for interactive visualizations 
