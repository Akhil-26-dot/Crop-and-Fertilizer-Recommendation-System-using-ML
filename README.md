# Crop and Fertilizer Recommendation System using Machine Learning

## Project Overview
This project aims to develop an advanced system that leverages machine learning to provide precise crop and fertilizer recommendations to farmers. By analyzing soil attributes, weather conditions, and historical data, the system offers data-driven insights to optimize crop selection and enhance agricultural productivity.

The solution addresses the challenges faced by farmers, including low crop yield, unsuitable crop selection, and inadequate fertilizer use, with the goal of promoting sustainable farming practices.

---

## Features
- **Crop Recommendation**: Suggests the most suitable crops based on the input data (e.g., soil and weather attributes).
- **Fertilizer Recommendation**: Identifies the optimal fertilizers required for the selected crop, enhancing growth and yield.
- **Data-Driven Insights**: Integrates historical data and predictive modeling for tailored recommendations.

---

## Dataset Information
Two datasets are used in this project:

### 1. **Crop Recommendation Dataset**
- **File**: Crop_recommendation.csv
- **Description**: Contains information on soil attributes, such as nitrogen (N), phosphorus (P), and potassium (K) levels, along with temperature, humidity, pH, and rainfall for various crops.
- **Columns**:
  - `N`: Nitrogen content in soil
  - `P`: Phosphorus content in soil
  - `K`: Potassium content in soil
  - `Temperature`: Temperature in °C
  - `Humidity`: Relative humidity in %
  - `pH`: pH level of the soil
  - `Rainfall`: Rainfall in mm
  - `label`: Target crop

### 2. **Fertilizer Recommendation Dataset**
- **File**: Fertilizer Prediction.csv
- **Description**: Provides guidance on the type and quantity of fertilizers required for specific soil and crop combinations.
- **Columns**:
  - `Crop Type`: Type of crop
  - `Soil Type`: Type of soil
  - `N`, `P`, `K`: Current levels of nitrogen, phosphorus, and potassium
  - `Fertilizer Name`: Optimal fertilizer suggestion

---

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - `pandas` and `numpy` for data manipulation
  - `matplotlib` and `seaborn` for data visualization
  - `scikit-learn` for machine learning model development
  
- **Machine Learning Algorithms**:
  -

---

## Installation and Usage

### Prerequisites
- Python 3.8 or higher
- Required Python libraries (install using `pip`):
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn 
  ```

### Steps to Run
1. Clone the repository or download the project files.
2. Place the datasets (`Crop_recommendation.csv` and `Fertilizer Prediction.csv`) in the project directory.
3. Run the script to preprocess the data and train the model:
   ```bash
   python train_model.py
   ```
---

## How It Works
1. **Data Preprocessing**:
   - The datasets are cleaned and normalized for efficient model training.
   - Missing values, if any, are handled appropriately.

2. **Model Training**:
   - The system trains machine learning models on the crop recommendation dataset.
   - A separate logic-based algorithm or ML model is applied to the fertilizer recommendation dataset.

3. **User Interaction**:
   - Farmers input soil and environmental parameters into the application.
   - The system outputs the recommended crop and fertilizer, along with insights to improve farming practices.

---

## Future Scope
- Integrating real-time weather data APIs for dynamic recommendations.
- Incorporating additional parameters like pest control and water usage.
- Expanding the dataset to cover more crops and regions.
- Enhancing the user interface with multi-language support.

---

## License
This project is licensed under the MIT License. See `LICENSE` file for details.

---

## Acknowledgments
- The datasets were sourced for academic and development purposes.
- Thanks to the contributors and open-source community for support.

---


