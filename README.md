# Bay Area VTA Ridership Forecasting
The Valley Transportation Authority (VTA) is a public transit agency that serves Santa Clara County, California. VTA provides bus, light rail, and paratransit services.
In this project, ridership is predicted for VTA stations and the impact of weather on ridership is analyzed.

## Folder Structure
- raw_data - This will contain all the raw dataset files collected from -
    - Ridership - https://data.vta.org/documents/a3e899b0822e433fb52dda8a2d4f140c
    - Weather - https://noaa-ghcn-pds.s3.amazonaws.com/index.html
- staging_data - This folder will be used as a staging area to store intermediate tables.
- clean_data - This will contain the final clean dataset along with the train test splits.

## Order of running the notebooks
1. clean_ridership.ipynb
2. generate_dates.ipynb
3. merge_stops.ipynb
4. merge_climate.ipynb
5. merge_data.ipynb
6. train_test_split.ipynb
7. train_test_split_wo_weather.ipynb
