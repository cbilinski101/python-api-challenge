# Python API Challenge - Weather and Vacation Analysis

## Overview
This project explores weather patterns and vacation destinations using APIs to collect and analyze weather data across global cities. The project consists of two main parts:

1. **WeatherPy** - A script that pulls weather data from OpenWeatherMap API, processes the data, and visualizes relationships between latitude and various weather metrics.
2. **VacationPy** - A script that identifies ideal vacation destinations based on temperature preferences and maps them using Google Places API.

## Files Included
- **WeatherPy.ipynb**: Jupyter Notebook for fetching and analyzing weather data.
- **VacationPy.ipynb**: Jupyter Notebook for finding vacation spots and mapping them.
- **cities.csv**: A dataset containing weather data for different cities.
- **Figures (Fig1.png, Fig2.png, Fig3.png, Fig4.png)**: Visualizations generated from WeatherPy.

## Data Sources
- [OpenWeatherMap API](https://openweathermap.org/api) for weather data.
- [Google Places API](https://developers.google.com/places/web-service/intro) for mapping vacation locations.

## Visualizations
The project analyzes relationships between latitude and various weather conditions such as:

   - **Latitude vs. Temperature:**
     - Shows a strong correlation where temperatures are highest near the equator and decrease as latitude increases or decreases.
     - The Northern Hemisphere often has a steeper decline in temperature due to landmass effects compared to the Southern Hemisphere, which has more ocean coverage.
     - ![image](https://github.com/user-attachments/assets/4e6ce1d2-8eb6-474a-92df-7a4c0111e034)
       
   - **Latitude vs. Humidity:**
     - Displays varied humidity levels across latitudes, with no strong correlation but higher variability in tropical regions.
     - Coastal areas and tropical regions tend to have higher humidity.
     - ![image](https://github.com/user-attachments/assets/a2a40206-8800-4543-a5a8-d549ece572d9)

   - **Latitude vs. Cloudiness:**
     - Shows a widely scattered distribution, indicating no clear relationship between latitude and cloudiness.
     - Some regions may exhibit bands of high cloud cover due to prevailing weather patterns.
     - ![image](https://github.com/user-attachments/assets/91425d3e-37b3-4a7f-a57b-371a46ea5477)

   - **Latitude vs. Wind Speed:**
     - Generally shows no strong correlation, but some higher wind speeds are observed at higher latitudes.
     - The distribution can be influenced by local topography and large-scale atmospheric circulation.
     - ![image](https://github.com/user-attachments/assets/58993a77-bab5-42ce-b262-67d6639ac06a)

   - **Northern Hemisphere: Temperature vs. Latitude**
       - Strong negative correlation; temperature decreases as latitude increases.
       - ![image](https://github.com/user-attachments/assets/7dbbe347-8333-4d1e-901b-f05c8557e382)

   - **Southern Hemisphere: Temperature vs. Latitude**
       - Positive correlation; temperature increases as latitude approaches the equator.
       - ![image](https://github.com/user-attachments/assets/a3c6408a-d0d3-4345-ac58-609d4f76ce6a)

   - **Northern Hemisphere: Humidity vs. Latitude**
       - No strong correlation but trends vary by season and region.
       - ![image](https://github.com/user-attachments/assets/e38fad86-219b-4dad-a05f-85ea1a68744a)

   - **Southern Hemisphere: Humidity vs. Latitude**
       - Similar scattered pattern with no strong correlation.
       - ![image](https://github.com/user-attachments/assets/24ff2275-8588-4c3f-a59b-647613899362)

   - **Northern Hemisphere: Cloudiness vs. Latitude**
       - Distribution suggests clusters of cloud coverage at certain latitudes.
       - ![image](https://github.com/user-attachments/assets/d33e55b0-73f2-4d54-9375-27209db88cc7)

   - **Southern Hemisphere: Cloudiness vs. Latitude**
       - Similar trends as the Northern Hemisphere, but generally more uniform due to oceanic influence.
       - ![image](https://github.com/user-attachments/assets/480cb119-b8ad-4687-a349-2ca7e176c4de)

   - **Northern Hemisphere: Wind Speed vs. Latitude**
       - Slight increase in wind speed at higher latitudes due to stronger atmospheric dynamics.
       - ![image](https://github.com/user-attachments/assets/b53e9ce4-8842-4da6-987b-6349c9189b72)

   - **Southern Hemisphere: Wind Speed vs. Latitude**
       - Similar pattern, often affected by fewer land obstructions.
       - ![image](https://github.com/user-attachments/assets/72def744-6c07-4c85-bb73-5f5353fae990)

       
## Deployment
The project is deployed on GitHub Pages. You can view the deployed version here:
[Python API Challenge Deployment](https://cbilinski101.github.io/python-api-challenge/)

## Instructions
1. Clone the repository.
2. Install necessary dependencies using:
   ```bash
   pip install requests matplotlib pandas jupyter
   ```
3. Run the `WeatherPy.ipynb` notebook to generate weather insights.
4. Run the `VacationPy.ipynb` notebook to identify vacation destinations.

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

This project was developed with the assistance of the following resources:

- **"U of T" (Turtoring Session - Xpert Learning Assistant - GitLab Activites)** – Provided guidance on code and explanations.
- **ChatGPT** – Assisted with code, explanations, and README formatting. 
