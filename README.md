# Intelligent Crop Recommendation System using Machine Learning

## Overview
The **Intelligent Crop Recommendation System** leverages **machine learning** to help farmers select the most suitable crops based on soil and environmental conditions. By analyzing factors such as **soil nutrients (N, P, K), temperature, humidity, pH, and rainfall**, the system predicts the optimal crop to maximize yield and sustainability.

## Features
- **Data-driven crop recommendations** based on soil properties and climatic conditions.
- **Machine Learning models** trained on agricultural datasets.
- **Flask-based Web Application** for user interaction.
- **Pre-trained ML models** for accurate and efficient predictions.
- **Scalable and extendable** for future improvements.

## Dataset
The dataset used in this project contains information on:
- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH Level
- Rainfall
- Crop Label (Target Variable)

## Technologies Used
- **Python** (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)
- **Machine Learning** (Logistic Regression, Random Forest, Decision Tree, SVM, KNN)
- **Flask** (For web-based user interaction)
- **Jupyter Notebook** (For model training and evaluation)

## Installation & Setup
Follow these steps to set up and run the project:

1. Clone the repository:
   ```bash
   git clone https://github.com/sakshipatil1396/Intelligent-Crop-Recommendation-System-using-ML.git
   ```

2. Navigate to the project folder:
   ```bash
   cd Intelligent-Crop-Recommendation-System-using-ML
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask application:
   ```bash
   python app.py
   ```

5. Open the web app in your browser:
   ```
   http://127.0.0.1:5000/
   ```

## Project Structure
```
📂 Intelligent-Crop-Recommendation-System
│── 📂 dataset
│── 📂 models
│── 📜 Crop Recommendation Using Machine Learning.ipynb
│── 📜 app.py
│── 📜 model.pkl
│── 📜 requirements.txt
│── 📜 README.md
```

## Usage
1. **Input soil and climate parameters** via the web interface.
2. **Receive crop recommendations** instantly based on ML predictions.
3. **Use the insights** to improve farming decisions.

## Results & Performance
The trained models achieve high accuracy in predicting suitable crops. The project utilizes multiple algorithms and selects the best-performing model.

## Future Enhancements
- Integrate **real-time weather API** for dynamic predictions.
- Implement **mobile-friendly UI** for farmers.
- Extend the dataset with **geographical variations** for broader applications.

## Contributors
- **Sakshi Patil** - Developer


