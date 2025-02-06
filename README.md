# Crop and Fertilizer Recommendation System using Machine Learning

## 📌 Overview
This project aims to develop a **machine learning-based recommendation system** for both **crop selection** and **fertilizer suggestions**. By analyzing **soil attributes, weather conditions, and historical data**, the system provides optimized recommendations to improve agricultural productivity.

## 🚀 Features
✅ **Crop Recommendation:** Suggests the most suitable crops based on soil and climatic conditions.  
✅ **Fertilizer Recommendation:** Recommends the best fertilizers based on soil nutrient levels and crop requirements.  
✅ **Machine Learning Models:** Utilizes multiple classification models for accurate predictions.  
✅ **Data-driven Insights:** Analyzes key agricultural parameters for better decision-making.  
✅ **User-Friendly Interface:** Allows users to input data and receive recommendations easily.  

## 📂 Dataset Information
The project utilizes two datasets to train and test the models:

### 1️⃣ Crop Recommendation Dataset (`Crop_recommendation.csv`)
- **Features:**
  - Nitrogen (N)
  - Phosphorus (P)
  - Potassium (K)
  - Temperature
  - Humidity
  - pH Level
  - Rainfall
- **Target:** Recommended Crop Type

### 2️⃣ Fertilizer Recommendation Dataset (`Fertilizer Prediction.csv`)
- **Features:**
  - Soil Moisture
  - Nitrogen (N)
  - Phosphorus (P)
  - Potassium (K)
  - Crop Type
- **Target:** Recommended Fertilizer Type

## 🛠 Installation & Setup
Ensure you have **Python 3.x** installed along with the necessary dependencies. You can install them using:
```sh
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

## 🔧 Usage Instructions
Follow these steps to run the models:

### 1️⃣ Run the Crop Recommendation Model
```sh
jupyter notebook crop.ipynb
```

- Input relevant **soil and environmental parameters** (N, P, K, temperature, humidity, pH, rainfall).
- The model will suggest the **best crop** for the given conditions.

### 2️⃣ Run the Fertilizer Recommendation Model
```sh
jupyter notebook fertilizer.ipynb
```

- Provide **soil properties and crop type** as input.
- The system will recommend the **most suitable fertilizer**.

## 📊 Machine Learning Model Used
🔹 **Decision Tree Classifier**  
 

## 🏆 Benefits of the System
🌱 **Optimized Crop Yield:** Helps farmers make **informed decisions** about crop selection.  
🔬 **Soil Health Improvement:** Provides **fertilizer recommendations** based on soil composition.  
📉 **Reduction in Resource Wastage:** Ensures **efficient use of fertilizers** to prevent overuse.  

## Future Scope
- Integrating real-time weather data APIs for dynamic recommendations.
- Incorporating additional parameters like pest control and water usage.
- Expanding the dataset to cover more crops and regions.
- Enhancing the user interface with multi-language support.

---

## License
This project is licensed under the MIT License. See `LICENSE` file for details.

---
## 🤝 Acknowledgments
This project is developed as part of an initiative to **support precision farming** and **enhance agricultural productivity** using machine learning techniques. It leverages datasets and ML models to provide valuable insights for farmers and agricultural professionals.

---
🎯 **Let's revolutionize agriculture with AI & Data Science!** 🚜🌾

