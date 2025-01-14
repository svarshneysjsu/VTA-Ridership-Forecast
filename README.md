# Bay Area VTA Ridership Forecasting
The Valley Transportation Authority (VTA) is a public transit agency that serves Santa Clara County, California. VTA provides bus, light rail, and paratransit services.
This project leverages machine learning techniques to forecast ridership for the Valley Transportation Authority (VTA). By analyzing historical ridership data considering the imapct of weather on it, the model aims to predict future ridership patterns, assisting in effective transit planning and resource allocation.

## Features

- **Data Collection**: Aggregates historical ridership data from VTA's open data portal.
- **Data Preprocessing**: Cleans and prepares data for analysis, including handling missing values and outliers.
- **Feature Engineering**: Incorporates external factors such as weather conditions and economic indicators to enhance model accuracy.
- **Model Training**: Implements machine learning algorithms, including Decision Trees and Random Forests, to forecast ridership.
- **Model Evaluation**: Assesses model performance using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
- **Visualization**: Provides graphical representations of data trends and model predictions.

## Usage

To use this project, follow these steps:

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook (optional, for exploring data and running experiments)

### Folder Structure
- raw_data - This will contain all the raw dataset files collected from -
    - Ridership - https://data.vta.org/documents/a3e899b0822e433fb52dda8a2d4f140c
    - Weather - https://noaa-ghcn-pds.s3.amazonaws.com/index.html
- staging_data - This folder will be used as a staging area to store intermediate tables.
- clean_data - This will contain the final clean dataset along with the train test splits.

### Steps
1. clean_ridership.ipynb
2. generate_dates.ipynb
3. merge_stops.ipynb
4. merge_climate.ipynb
5. merge_data.ipynb
6. train_test_split.ipynb
7. train_test_split_wo_weather.ipynb

## Technologies Used
- **Programming Language**: Python
- **Machine Learning**: scikit-learn
- **Data Manipulation**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Data Sources**: VTA's Open Data Portal, National Weather Service

## Contribution
- This project was developed as part of the DATA 245 course at San Jose State University. This is a team project for academic purposes. If you find any issues or have suggestions, feel free to open a GitHub issue.

  
## Contact

For questions or additional information, please reach out via:
- **GitHub Issues**: [Open an Issue](https://github.com/svarshneysjsu/VTA-Ridership-Forecast/issues)

--
Hope this project serves as a valuable resource for understanding transit ridership forecasting using machine learning techniques
