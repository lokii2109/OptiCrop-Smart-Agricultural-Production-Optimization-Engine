# Project Executable Files

## Main Application

```
app.py
```

Run:

```bash
python app.py
```

---

## Machine Learning Model

```
models/best_crop_model.pkl
```

This file contains the trained Random Forest model used for crop prediction.

---

## Dataset

```
crop_dataset.csv
```

Contains soil nutrients and environmental parameters used for training the model.

---

## HTML Templates

```
templates/
│
├── index.html
└── result.html
```

These files provide the user interface for data input and displaying crop recommendations.

---

## Project Structure

```
OptiCrop
│
├── app.py
├── crop_dataset.csv
├── models
│   └── best_crop_model.pkl
├── templates
│   ├── index.html
│   └── result.html
├── requirements.txt
└── README.md
```