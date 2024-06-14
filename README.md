# vta-ridership-forecasting
Predicting ridership for VTA stations and analyzing the impact of weather on ridership.

## Folder Structure
- raw_data - This should contain all the raw dataset files.
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
