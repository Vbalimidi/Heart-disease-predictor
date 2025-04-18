# Heart Disease Predictor

A machine learning model to predict heart disease using clinical parameters.

## Overview

This project uses machine learning to predict the presence of heart disease in patients based on various clinical parameters. It implements multiple classification algorithms and compares their performance to find the best predictor.

## Dataset

The dataset used is from the UCI Machine Learning Repository's Heart Disease dataset, containing 303 samples with 13 clinical features:

- Age
- Sex (1 = male, 0 = female)
- Chest pain type (0-3)
- Resting blood pressure 
- Serum cholesterol
- Fasting blood sugar
- Resting ECG results
- Maximum heart rate
- Exercise induced angina
- ST depression induced by exercise
- Slope of peak exercise ST segment
- Number of major vessels colored by fluoroscopy
- Thalium stress test result

Target variable:
- Heart disease diagnosis (1 = present, 0 = absent)

## Models

The project implements and compares three classification models:

- Logistic Regression
- K-Nearest Neighbors (KNN) 
- Random Forest

## Requirements

```python
numpy>=1.21.0
pandas>=1.3.0
scikit-learn>=1.0.0
matplotlib>=3.4.0
seaborn>=0.11.0
jupyter>=1.0.0
```


## Model Performance

The models are evaluated using multiple metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Cross-validation scores

## Project Structure

```
Heart-disease-predictor/
│
├── heart-disease-classification.ipynb   
├── data/
│   └── heart-disease.csv               
├── README.md
└── requirements.txt
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
