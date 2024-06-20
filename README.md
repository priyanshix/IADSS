# IADSS- Integrated Agriculture Decision Support System

The IADSS is a machine learning-based project designed to provide predictions and recommendations for farmers. The system uses different algorithms to predict crops, recommend fertilizers, and provide rainfall and yield predictions to help farmers make informed decisions about their crops.

## Installation

1. Clone the repository to your local machine.
```bash
git clone https://github.com/priyanshix/IADSS.git
```
2. Install the required packages using pip.
```
pip install -r requirements.txt
```
3. Run Apache web server using XAMPP.

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
- Bootstrap4
- Scikit-learn

## Dataset
The IADSS dataset includes the following features:

### Crop Prediction Dataset
- State_Name
- District_Name
- Season
- Crop

### Crop Recommendation Dataset
- N
- P
- K
- Temperature
- Humidity
- pH
- Rainfall
- Label

### Fertilizer Recommendation Dataset
- Temparature
- Humidity
- Soil Moisture
- Soil Type
- Crop Type
- Nitrogen
- Phosphorous
- Potassium
- Fertilizer Name

### Rainfall Prediction Dataset
- SUBDIVISION
- YEAR
- JAN
- FEB
- MAR
- APR
- MAY
- JUN
- JUL
- AUG
- SEP
- OCT
- NOV
- DEC
- ANNUAL
- Jan-Feb
- Mar-May
- Jun-Sep
- Oct-Dec

### Yield Prediction Dataset
- State_Name
- District_Name
- Crop_Year
- Season
- Crop
- Area
- Production

## How to Use
- Crop Prediction: Input `State_Name`, `District_Name`, and `Season` to get the predicted crop for that location.
- Crop Recommendation: Input `N`, `P`, `K`, `Temperature`, `Humidity`, `pH`, and `Rainfall` for that location to get recommended crops for that location.
- Fertilizer Recommendation: Input `Temperature`, `Humidity`, `Soil Moisture`, `Soil Type`, `Crop Type`, `Nitrogen`, `Phosphorous`, and `Potassium` to get recommended fertilizer for that crop and location.
- Rainfall Prediction: Input `Subdivision` and `Year` to get rainfall prediction for that year.
- Yield Prediction: Input `State_Name`, `District_Name`, `Crop_Year`, `Season`, `Crop`, `Area`, `Production` to get predicted yields for that crop and location.
