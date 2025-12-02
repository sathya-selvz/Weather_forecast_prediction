![Weather GIF](screenshots/GIF.png)


# 🌦️ Weather Forecasting using Machine Learning

**📌 Achieved 98% Accuracy | Python | Jupyter Notebook**

This project focuses on predicting weather conditions using machine learning techniques.
Using a structured dataset containing meteorological parameters (temperature, humidity, pressure, etc.), the model learns patterns and forecasts the weather category with high accuracy.

The core implementation is inside the Jupyter Notebook:
📄 **`weather-forecasting-98-acc.ipynb`**
📁 A separate dataset file is included.

---

## 🔍 1. Project Summary

Accurate short-term weather forecasting is crucial for agriculture, outdoor event planning, environmental monitoring, and daily life.
This project applies machine learning to classify weather conditions based on real-world weather features.

Key highlights:

* End-to-end ML workflow implemented in Python
* Proper preprocessing of dataset
* Visual exploratory data analysis
* Multiple ML models tested
* Best model achieved **98% accuracy**
* Final model capable of predicting weather for new inputs

---

## 📂 2. Project Folder Structure

```
📁 Weather-Forecasting-ML
│
├── weather-forecasting-98-acc.ipynb      
├── temp.csv                          
├── README.md                             
└── screenshots/                               
---

## 📊 3. Dataset Description

The dataset contains weather-related observations.
Common columns include:

| Feature           | Description                                          |
| ----------------- | ---------------------------------------------------- |
| Temperature       | Atmospheric temperature (°C or °F)                   |
| Humidity          | Moisture content (%)                                 |
| Pressure          | Atmospheric pressure (hPa)                           |
| Wind Speed        | Speed of wind (km/h or m/s)                          |
| Visibility        | Distance of clear visibility                         |
| Weather Condition | Target label (e.g., Sunny, Cloudy, Rainy, Fog, etc.) |

### ✔️ Dataset Tasks Performed

* Missing values handling
* Label encoding (for categorical columns)
* Feature scaling (if required)
* Correlation analysis
* Train-test split

---

## 🧪 4. Project Workflow (Deep Explanation)

### **Step 1: Importing Libraries**

Used libraries include:

* **pandas** → dataset handling
* **numpy** → numerical operations
* **matplotlib / seaborn** → visualization
* **sklearn** → ML algorithms, metrics, preprocessing

---

### **Step 2: Data Preprocessing**

* Handle missing or null values
* Convert categorical text into numbers (LabelEncoder / OneHotEncoder)
* Inspect outliers, data distribution
* Normalize or standardize features (if needed)

---

### **Step 3: Exploratory Data Analysis (EDA)**

Performed visualizations:

* Heatmaps for feature correlation
* Distribution plots
* Weather condition frequency count
* Pair plots for major features

This helps understand patterns and relationships between weather variables.

---

### **Step 4: Model Selection & Training**

Multiple classification models may be tested:

* Logistic Regression
* Random Forest Classifier
* Decision Tree
* SVM
* Gradient Boosting

The model with **best performance (98% accuracy)** is selected.

---

### **Step 5: Evaluation Metrics**

Evaluated using:

* Accuracy Score
* Confusion Matrix
* Precision, Recall, F1-score
* Training vs Test accuracy comparison

A confusion matrix visualization is included in the notebook.

---

### **Step 6: Prediction**

The trained model can predict weather for new input such as:

```python
predict([temperature, humidity, pressure, windspeed])
```

---

## 🚀 5. How to Run the Project

### **Step 1 — Clone the Repository**

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

### **Step 2 — Install Dependencies**

```bash
pip install -r requirements.txt
```

### **Step 3 — Launch Jupyter Notebook**

```bash
jupyter notebook weather-forecasting-98-acc.ipynb
```

### **Step 4 — Dataset Placement**

[dataset file](temp.csv)


---

## 📈 6. Results & Observations

* The best-performing model achieved **98% accuracy**
* Weather predictions are consistent across test cases
* High correlation found between humidity, temperature, and certain weather labels
* No major overfitting observed

![Model Accuracy Result](screenshots/result.png)


---

## 📦 7. Technologies Used

* **Python 3.x**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**

---

## 📝 8. Future Improvements

Here are possible enhancements:

* Deploy as a Flask/Django web app
* Create a live weather dashboard using Power BI
* Improve model using deep learning (LSTM / RNN)
* Hyperparameter tuning using GridSearchCV
* Add real-time API data (OpenWeather API)

---

## 🤝 9. Contributing

Pull requests are welcome!
If you find any bug or want to enhance the model, feel free to contribute.

---

## 📜 10. License

This project is open-source and free to use.


