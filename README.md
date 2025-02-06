# World Entertainment Analysis & Cultural Impact

## Overview

This repository provides tools and methodologies for analyzing global entertainment trends and their cultural impact using combined data sources. By leveraging datasets from music streaming platforms (Spotify/Apple Music), social media reactions (Twitter/Reddit), Google Trends, ticket sales (concerts/events), and streaming platforms (Netflix/Prime/Disney+), the project aims to identify emerging trends, predict viral hits, and explore how global events influence cultural consumption.

## Key Features

- **Prediction of Viral Hits**: Using data from music platforms and social media, predict which upcoming songs or events are likely to become viral.
- **Impact of Global Events**: Analyze how major events (e.g., political, social, or economic) affect entertainment consumption patterns around the world.
- **Cultural Influence Mapping**: Create visualizations to show how cultural influences spread between different countries and regions.
- **Trend Forecasting**: Forecast emerging entertainment trends by analyzing patterns in global media consumption data.

## Data Sources

The project uses various data sources to provide insights into global entertainment and cultural trends:

1. **Music Streaming Data**: Spotify, Apple Music consumption patterns.
2. **Social Media**: Real-time reactions from Twitter, Reddit, etc.
3. **Google Trends**: Search interest over time for different entertainment topics.
4. **Ticket Sales Data**: Insights from ticket sales for concerts and events worldwide.
5. **Streaming Platforms**: Netflix, Prime Video, Disney+ consumption data.

## Installation

1. Clone the repository:
   git clone https://github.com/HACHIMIATMANE/TrendWave_Mapping-the-Global-Entertainment-Impact.git
2. Install dependencies (ensure you have Python 3.x installed):
   pip install -r requirements.txt
3. Make sure to get API keys and set up credentials for accessing the required platforms (Spotify, Twitter, Google Trends, etc.).
4. Place your data in the data/ directory, or configure the paths for automatic data collection.
Usage
## Data Collection
You can start by collecting the data from the respective platforms:

1. **Spotify/Apple Music**: Use the APIs for these services to gather data about song streams, playlists, and trends.
2. **Social Media**: Use the Twitter API to fetch tweets and reactions related to specific entertainment topics.
3. **Google Trends**: Use the pytrends library to fetch trends data.
4. **Ticket Sales**: Extract ticket sales data from popular platforms or event websites.
5. **Streaming Platforms**: Use the APIs for Netflix, Prime Video, and Disney+ (or other alternatives) to collect data on popular shows and movies.
## Analysis
Once data is collected, you can run the analysis scripts:

**Viral Hit Prediction**: Execute predict_viral_hits.py to forecast which songs or events will become the next big trend.
**Global Impact Analysis**: Run global_impact_analysis.py to analyze the impact of global events on entertainment consumption.
**Cultural Mapping**: Run cultural_mapping.py to visualize the spread of cultural influences globally.
**Trend Forecasting**: Execute forecast_trends.py to predict the next big trends in global entertainment.
## Results
The results of your analysis will be saved in the results/ directory. You can visualize trends, predictions, and cultural maps using tools like matplotlib, seaborn, or plotly.
