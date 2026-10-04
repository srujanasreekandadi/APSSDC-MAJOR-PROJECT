# Road Accident Severity Prediction using Machine Learning

## APSSDC ML Internship – Major Project

### Project Overview

This project predicts the severity of road accidents based on different road and environmental conditions.

The accident severity is classified into **Minor, Major, or Fatal**.

The project uses **XGBoost Classification** to predict the accident severity based on selected accident-related features.

- Weather Condition: Clear, Sunny, Cloudy, Rain, Heavy Rain, Fog, Storm
- Road Type: Urban, Rural, Highway
- Traffic Density: Low, Medium, High
- Visibility: 50–2000 meters
- Vehicles Involved: 1–5
- Hour of Day: 0–23

---

## Objectives

- Load and understand the road accident dataset.
- Check missing values and duplicate records.
- Analyze accident severity distribution.
- Select the required features for prediction.
- Encode categorical features.
- Encode the accident severity target.
- Split the dataset into training and testing data.
- Apply XGBoost classification.
- Predict accident severity.
- Evaluate the model using accuracy, classification report, and confusion matrix.
- Visualize the accident severity results.
- Save the trained model and encoders.
- Develop an interactive accident severity prediction system.
- Display confidence score and prediction probabilities.
- Provide risk levels and safety recommendations.

---

## Dataset

The project uses the following dataset:

```text
road_accident_dataset_v2_realistic.csv
```

The selected features used in the model are:

- Weather
- Road Type
- Traffic Density
- Visibility
- Vehicles Involved
- Hour

The target variable is:

```text
accident_severity
```

The accident severity contains three classes:

```text
Minor
Major
Fatal
```

The dataset is loaded and analyzed using Python.

---

## Methodology

The project follows these steps:

```text
Road Accident Dataset
          ↓
Load Dataset
          ↓
Understand Dataset
          ↓
Check Missing Values
          ↓
Check Duplicate Records
          ↓
Analyze Accident Severity
          ↓
Select Required Features
          ↓
Encode Categorical Features
          ↓
Encode Target Variable
          ↓
Train-Test Split
          ↓
XGBoost Model
          ↓
Prediction
          ↓
Model Evaluation
          ↓
Data Visualization
          ↓
Save Model and Encoders
          ↓
Accident Severity Prediction
```

---

## Machine Learning Algorithm

### XGBoost Classifier

XGBoost is used as the machine learning algorithm.

It is a gradient boosting algorithm that combines multiple decision trees to make predictions and is used for accident severity classification.

The main input features used in the model are:

```text
Weather
Road Type
Traffic Density
Visibility
Vehicles Involved
Hour
```

The target variable is:

```text
Accident Severity
```

The model parameters used are:

```text
n_estimators = 300
learning_rate = 0.05
max_depth = 6
random_state = 42
eval_metric = mlogloss
```

---

## Visualizations

The project generates two main visualizations.

### 1. Accident Severity Distribution

The count plot compares the number of accidents belonging to:

- Minor
- Major
- Fatal

### 2. Confusion Matrix

The confusion matrix represents the relationship between:

- Actual accident severity
- Predicted accident severity

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Gradio
- Google Colab
- GitHub

---

## Python Libraries

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
gradio
pickle
ipywidgets
warnings
```

---

## Project Files

```text
Road-Accident-Severity-Prediction/
│
├── road_accident_project_apssdc_(ml)(1).py
├── README.md
└── road_accident_dataset_v2_realistic.csv
```

The program also generates the following model files:

```text
road_accident_model.pkl
feature_encoder.pkl
target_encoder.pkl
```

---

## How to Run

### 1. Clone the repository

```text
git clone https://github.com/srujanasreekandadi/APSSDC-MAJOR-PROJECT.git
```

### 2. Open the Python file

Run:

```text
road_accident_project_apssdc_(ml)(1).py
```

### 3. Upload the Dataset

The program asks for the road accident dataset:

```text
road_accident_dataset_v2_realistic.csv
```

### 4. Run the program

The program will:

- Load the dataset
- Check the dataset information
- Check missing values
- Check duplicate records
- Analyze accident severity
- Select the required features
- Encode categorical features
- Encode the target variable
- Split the dataset
- Train the XGBoost model
- Predict accident severity
- Display the accuracy
- Generate the classification report
- Generate the confusion matrix
- Save the trained model and encoders
- Display the visualizations

---

## Prediction Criteria

The system predicts accident severity based on the selected road and environmental conditions.

The prediction inputs are:

| Input Feature | Values / Range |
| -------------- | -------------- |
| Weather | Clear, Sunny, Cloudy, Rain, Heavy Rain, Fog, Storm |
| Road Type | Urban, Rural, Highway |
| Traffic Density | Low, Medium, High |
| Visibility | 50–2000 meters |
| Vehicles Involved | 1–5 |
| Hour of Day | 0–23 |

The predicted accident severity is:

| Prediction | Risk Level |
| ---------- | ---------- |
| Minor | Low |
| Major | Medium |
| Fatal | High |

---

## Sample Output

The program displays:

```text
Predicted Accident Severity : Minor / Major / Fatal
Confidence Score            : XX.XX%
Risk Level                  : Low / Medium / High
```

The system also displays prediction probabilities for:

```text
Minor
Major
Fatal
```

The exact values may vary depending on the input conditions and dataset used.

---

## Future Enhancement

The project can be extended by including additional accident-related factors such as:

- Day of the week
- Traffic signals
- Number of lanes
- Temperature
- Cause of accident
- Number of casualties
- Peak hour information
- Location information
- Historical accident data

The system can also be extended with real-time traffic information, weather information, GPS-based accident risk prediction, mobile applications, and real-time accident alerts.

---

## Note

This project is developed for educational purposes as part of the **APSSDC ML Internship – Major Project**.

The dataset and predictions are used for machine learning and academic purposes.

---

## Author

**APSSDC ML Internship – Major Project**

**Road Accident Severity Prediction using XGBoost**
```
