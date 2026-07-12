# OptiCrop – Smart Agricultural Production Optimization Engine

## 1. Project Overview

OptiCrop is an AI-powered web application that recommends the most suitable crop based on soil nutrients and environmental conditions. The system uses a trained Random Forest machine learning model to analyze Nitrogen (N), Phosphorus (P), Potassium (K), Temperature, Humidity, Soil pH, and Rainfall to generate accurate crop recommendations.

---

## 2. System Architecture

The application consists of four major components:

- **Frontend**
  - HTML5
  - CSS3

- **Backend**
  - Python
  - Flask

- **Machine Learning**
  - Scikit-learn Random Forest Classifier

- **Dataset**
  - Crop Recommendation Dataset (CSV)

---

## 3. Project Workflow

1. User enters soil parameters.
2. Flask validates the input.
3. The trained Random Forest model predicts the best crop.
4. The application displays:
   - Recommended Crop
   - Soil Suitability
   - Precautions
   - Policy Recommendations (Scenario 3)

---

## 4. Technology Stack

- Python
- Flask
- Pandas
- NumPy
- Scikit-learn
- Pickle
- HTML
- CSS
- Git
- GitHub

---

## 5. Installation

```bash
pip install -r requirements.txt
python app.py
```

Open:

```
http://127.0.0.1:5000
```

---

## 6. Future Enhancements

- Weather API Integration
- Mobile Application
- IoT Sensor Integration
- Fertilizer Recommendation
- Cloud Deployment

---

## 7. Conclusion

OptiCrop demonstrates how Machine Learning and Flask can be used to provide intelligent crop recommendations that support farmers in making informed agricultural decisions.