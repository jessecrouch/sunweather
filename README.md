# SunWeather

Real-time space weather and natural hazards dashboard.

## Pages

### Space Weather Dashboard (`index.html`)
- SUVI solar imagery (GOES satellite, multiple wavelengths)
- Planetary Kp index with aurora forecast
- WSA-Enlil solar wind / CME predictions
- OVATION aurora forecast map
- NOAA space weather alerts

### Earthquake & Volcano Monitor (`earthquakes.html`)
- USGS earthquake feed (worldwide, filterable by time/magnitude/region)
- NOAA volcanic events (2020+)
- Interactive Leaflet map with dark theme
- Toggle layers independently
- Auto-refresh every 5 minutes

## Data Sources
- [NOAA SWPC](https://www.swpc.noaa.gov/) - Space weather
- [USGS Earthquake Hazards](https://earthquake.usgs.gov/) - Seismic data
- [NOAA NGDC Hazard Service](https://www.ngdc.noaa.gov/hazel/hazard-service/) - Volcanic events

## Run Locally
```bash
python3 -m http.server 8080
```
Then open `http://localhost:8080`
