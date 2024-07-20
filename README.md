# IADSS - Integrated Agriculture Decision Support System

IADSS is a project that utilizes machine learning to provide predictive analytics and recommendations for farmers. By leveraging various algorithms, the system can forecast crops, suggest fertilizers, and predict rainfall and yields, aiding farmers in making data-driven decisions.

## Installation

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/priyanshix/IADSS.git
    ```
2. Install the necessary packages using pip:
    ```bash
    pip install -r requirements.txt
    ```
3. Start the Apache web server using XAMPP.

## Features
- Crop Prediction
- Crop Recommendation
- Fertilizer Recommendation
- Rainfall Prediction
- Yield Prediction

## Technologies Used
- Python
- PHP
- Pandas
- NumPy
- JavaScript
- HTML/CSS
- Bootstrap 4
- Scikit-learn

## Dataset
The IADSS system relies on datasets with the following attributes:

### Crop Prediction Dataset
- State Name
- District Name
- Season
- Crop

### Crop Recommendation Dataset
- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH
- Rainfall
- Label

### Fertilizer Recommendation Dataset
- Temperature
- Humidity
- Soil Moisture
- Soil Type
- Crop Type
- Nitrogen
- Phosphorus
- Potassium
- Fertilizer Name

### Rainfall Prediction Dataset
- Subdivision
- Year
- Monthly Rainfall Data (Jan-Dec)
- Annual Rainfall
- Seasonal Rainfall (Jan-Feb, Mar-May, Jun-Sep, Oct-Dec)

### Yield Prediction Dataset
- State Name
- District Name
- Crop Year
- Season
- Crop
- Area
- Production

## How to Use
- **Crop Prediction**: Enter `State Name`, `District Name`, and `Season` to receive the predicted crop for that area.
- **Crop Recommendation**: Provide `N`, `P`, `K`, `Temperature`, `Humidity`, `pH`, and `Rainfall` to get crop recommendations for that location.
- **Fertilizer Recommendation**: Input `Temperature`, `Humidity`, `Soil Moisture`, `Soil Type`, `Crop Type`, `Nitrogen`, `Phosphorus`, and `Potassium` to receive fertilizer suggestions for the specified crop and location.
- **Rainfall Prediction**: Provide `Subdivision` and `Year` to get rainfall forecasts for that year.
- **Yield Prediction**: Enter `State Name`, `District Name`, `Crop Year`, `Season`, `Crop`, `Area`, and `Production` to get yield predictions for the specified crop and location.
"""
