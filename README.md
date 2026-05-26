# 🚗 CarIQ — Used Car Price Predictor

<div align="center">

!\[Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
!\[Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-F7931E?style=for-the-badge\&logo=scikit-learn\&logoColor=white)
!\[Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-F9AB00?style=for-the-badge\&logo=googlecolab\&logoColor=white)
!\[License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**AI-Powered Vehicle Valuation using Machine Learning \& Gradient Boosting**

*Introduction to Data Science | PBL ETE Assessment*

[📓 View Notebook](https://colab.research.google.com/drive/1aw9IJHE3xRALQsGdOGIs6m8DLs7U6XIN) · [📊 Dataset (Kaggle)](https://www.kaggle.com/datasets/manishkr1754/cardekho-used-car-data) · [🎯 Live Demo](https://7afbf300b0fa1cf27c.gradio.live)

</div>

\---

## 📌 Overview

**CarIQ** is an end-to-end machine learning project that predicts used car prices based on real-world Indian market data. Using a dataset of **15,000+ car listings** from CarDekho, the model achieves **93.6% accuracy (R²)** with a Gradient Boosting Machine (GBM).

> Submitted by: \*\*Aayush Singh\*\* | Roll No.: `25SCS1003004271`
> Submitted To: \*\*Dr. Ashish Sharma\*\* | Associate Professor, SCSE

\---

## 🏆 Key Results

|Metric|Value|
|-|-|
|📈 R² Score|**93.6%**|
|📉 Mean Absolute Error|Low|
|🔄 Validation|K-Fold Cross-Validation|
|🚘 Dataset Size|15,000+ listings|
|🏷️ Brands Covered|32|
|🤖 Final Model|Gradient Boosting Machine (GBM)|

\---

## 📂 Project Structure

```
used-car-price-predictor/
│
├── 📓 UsedCarPricePredictor.ipynb   # Main Colab notebook
├── 📊 data/
│   └── car\_data.csv                 # CarDekho dataset
├── 📈 visuals/
│   ├── actual\_vs\_predicted.png
│   ├── residuals\_distribution.png
│   └── feature\_importance.png
├── 📋 presentation/
│   └── UsedCarPricePredictor.pptx
└── 📄 README.md
```

\---

## ⚙️ Methodology

```
Raw Data → Preprocessing → Feature Engineering → Model Selection → Training → Evaluation → Prediction
```

### Step-by-Step Pipeline

|Step|Description|
|-|-|
|**1. Data Collection**|CarDekho / Kaggle dataset with 15,000+ Indian used car listings|
|**2. Preprocessing**|Handled missing values, removed duplicates \& outliers|
|**3. Feature Engineering**|Label Encoding \& One-Hot Encoding for categorical variables|
|**4. Model Selection**|Evaluated Linear Regression, Decision Tree, Random Forest, GBM|
|**5. Training \& Testing**|70:30 train-test split + K-Fold Cross-Validation|
|**6. Evaluation**|R², MAE, MSE metrics — GBM achieved best results|

\---

## 🤖 Model Comparison

|Model|Performance|Notes|
|-|-|-|
|Linear Regression|❌ Baseline|Simple, limited for non-linear data|
|Decision Tree|⚠️ Moderate|Prone to overfitting|
|Random Forest|✅ Strong|Ensemble, reduces overfitting|
|**GBM (Final)**|🏆 **Best**|93.6% R², tuned hyperparameters|

\---

## 🔍 Input Features

The model uses the following features for prediction:

* **Max Power** *(most important — 72.5% feature importance)*
* **Vehicle Age** *(15.7% importance)*
* **Engine CC** *(3.3% importance)*
* Mileage (km/l)
* Kilometers Driven
* Brand
* Fuel Type (Petrol / Diesel / Electric / CNG)
* Transmission (Manual / Automatic)
* Number of Seats

\---

## 📊 Visualizations

### Feature Importance

> Max Power dominates at \*\*0.725\*\*, followed by Age \*\*(0.157)\*\* and Engine \*\*(0.033)\*\*

### Price Depreciation Trend

> Clear depreciation as vehicle age increases; peak prices at \*\*1–2 years\*\*

### Fuel Type Insights

> Electric cars hold the \*\*highest average prices\*\* despite fewer listings

\---

## 🛠️ Tech Stack

|Tool|Purpose|
|-|-|
|!\[Python](https://img.shields.io/badge/-Python-3776AB?logo=python\&logoColor=white)|Core programming language|
|!\[Pandas](https://img.shields.io/badge/-Pandas-150458?logo=pandas\&logoColor=white)|Data manipulation|
|!\[NumPy](https://img.shields.io/badge/-NumPy-013243?logo=numpy\&logoColor=white)|Numerical operations|
|!\[Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C)|Data visualization|
|!\[Scikit-learn](https://img.shields.io/badge/-Scikit--learn-F7931E?logo=scikit-learn\&logoColor=white)|ML models \& pipelines|
|!\[Colab](https://img.shields.io/badge/-Google%20Colab-F9AB00?logo=googlecolab\&logoColor=white)|Cloud notebook environment|

\---

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy matplotlib scikit-learn
```

### Run Locally

```bash
# Clone the repository
git clone https://github.com/your-username/used-car-price-predictor.git
cd used-car-price-predictor

# Open the notebook
jupyter notebook UsedCarPricePredictor.ipynb
```

### Run on Google Colab

Click the badge below to open directly in Colab:

[!\[Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](#)

\---

## 🔮 Future Enhancements

* \[ ] 🌐 Deploy as full-stack web application
* \[ ] 📡 Integrate real-time market data feeds
* \[ ] 🧬 Explore deep learning / neural network models
* \[ ] 📍 Add location, condition, owner history as features
* \[ ] 📱 Build a mobile-friendly interface

\---

## 📚 References

* [CarDekho Dataset — Kaggle](https://www.kaggle.com)
* [Scikit-learn Documentation](https://scikit-learn.org/stable/)
* [CarDekho.com](https://www.cardekho.com) — Market comparison
* OLX Autos — Indian used car market reference

\---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

\---

<div align="center">

Made with ❤️ by **Aayush Singh** | SCSE

*School of Computer Science and Engineering*

</div>

