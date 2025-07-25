# 🌦️ Weather Prediction using Linear Regression

This project predicts temperature, humidity, and pressure using historical weather data from European cities (2000-2010) through linear regression modeling. Developed in Jupyter Notebook for the Artificial Intelligence course.

## 📌 Project Overview

Predicts three key meteorological variables:

- Temperature (°C)
- Humidity (%)
- Pressure (hPa)

Using machine learning (Linear Regression) on a dataset covering 18 European cities.

## 👨‍💻 Developer

**'Affan Najiy Bin Rusdi**  
_Student ID: 22010453_  
_University: Universiti Teknologi PETRONAS_

## 📂 Dataset

**Source:** [Zenodo Weather Prediction Dataset](https://zenodo.org/records/4770937)  
**Features:**

- Daily meteorological records (2000-2010)
- 18 European cities
- Multiple weather parameters

## 🔧 Technical Implementation

### 🛠️ Tech Stack

- **Python 3**
- **Libraries:**
  - pandas (data handling)
  - numpy (numerical operations)
  - matplotlib/seaborn (visualization)
  - scikit-learn (machine learning)

### 📊 Methodology

**Data Preprocessing**

- Missing value handling
- One-hot encoding for categorical data
- Correlation analysis

**Modeling**

- Separate Linear Regression models for:
  - Temperature prediction
  - Humidity prediction
  - Pressure prediction
- Train-test split (80-20)

**Evaluation Metrics**

- Mean Squared Error (MSE)
- R² Score

## 📋 Code Structure

```plaintext
1. Data Loading & Inspection
2. Missing Value Analysis
3. Data Preprocessing
4. Feature Selection
5. Train-Test Split
6. Model Training
7. Evaluation
8. Visualization
```

## 🚀 Getting Started

Install requirements:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run Jupyter Notebook:

```
jupyter notebook weather_prediction.ipynb
```

## 📚 Term Definitions

- MSE: Measures average squared difference between predicted and actual values
- R² Score: Indicates proportion of variance explained by the model
- Correlation: Statistical relationship between variables (-1 to 1)

## 📜 License

Educational use only - Not for commercial purposes

## 🙏 Acknowledgements

- Huber, F. (2021, May 18). Weather prediction dataset. Retrieved from Zenodo: https://zenodo.org/records/4770937t

# Thank you for reading!
