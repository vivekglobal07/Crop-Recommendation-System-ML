# 🌾 Crop Recommendation System

A Machine Learning-based Crop Recommendation System that suggests the most suitable crop to cultivate based on soil nutrients and environmental conditions. The system analyzes Nitrogen (N), Phosphorous (P), Potassium (K), temperature, humidity, pH, and rainfall to recommend an optimal crop for farming.

## 🚀 Features

* Predicts the most suitable crop based on soil and weather conditions.
* User-friendly Streamlit web interface.
* Data preprocessing using Label Encoding and Min-Max Scaling.
* Multiple machine learning models evaluated:

  * Logistic Regression
  * Random Forest Classifier
  * Gradient Boosting Classifier
* Real-time crop recommendation.
* Easy deployment and usage.

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Matplotlib
* Seaborn
* Pickle

## 📂 Project Structure

```text
Crop-Recommendation-System-ML/
│
├── app.py
├── models/
│   ├── encoder.pkl
│   ├── scaler.pkl
│   └── model_gbc.pkl
│
├── notebooks/
│   └── crop_recommendation.ipynb
│
├── dataset/
│   └── Crop_recommendation.csv
│
├── requirements.txt
└── README.md
```

## 📊 Input Parameters

The model takes the following inputs:

| Parameter       | Description                 |
| --------------- | --------------------------- |
| Nitrogen (N)    | Nitrogen content in soil    |
| Phosphorous (P) | Phosphorous content in soil |
| Potassium (K)   | Potassium content in soil   |
| Temperature     | Temperature in °C           |
| Humidity        | Relative humidity (%)       |
| pH              | Soil pH value               |
| Rainfall        | Rainfall in mm              |

## 🤖 Machine Learning Workflow

1. Data Collection and Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Scaling using MinMaxScaler
4. Label Encoding of Crop Labels
5. Model Training
6. Model Evaluation
7. Model Serialization using Pickle
8. Streamlit Deployment

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Crop-Recommendation-System-ML.git
cd Crop-Recommendation-System-ML
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

## 📈 Model Performance

The project compares multiple classification algorithms and selects the best-performing model based on accuracy and classification metrics.

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier

The final deployed model uses Gradient Boosting Classifier for crop prediction.

## 🌱 Example

Input:

* N = 90
* P = 42
* K = 43
* Temperature = 21°C
* Humidity = 82%
* pH = 6.5
* Rainfall = 203 mm

Output:

```text
Recommended Crop: Rice
```

## 🎯 Future Improvements

* Weather API integration
* Fertilizer recommendation system
* Disease prediction module
* Multi-language support
* Mobile application deployment

## 👨‍💻 Author

Vivek Yadav

If you found this project useful, consider giving it a ⭐ on GitHub.
