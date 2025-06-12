# 🌍 Life Expectancy Prediction with Machine Learning

This project uses real WHO data and machine learning models to predict life expectancy based on socioeconomic and health indicators.

## 🎯 Goal
- Predict life expectancy using socioeconomic and health-related variables.
- Compare models: Linear Regression, Random Forest, XGBoost.
- Understand key drivers of longevity through feature importance and error analysis.

## 📊 Dataset
Source: [WHO Global Health Observatory](https://www.who.int/data/gho)

## 📈 Models & Results

| Model            | MAE  | RMSE | R²     |
|------------------|------|------|--------|
| Linear Regression| 2.86 | 3.91 | 0.824  |
| Random Forest    | 1.07 | 1.66 | 0.968 ✅ |
| XGBoost          | 1.11 | 1.67 | 0.9677 |

## 🔍 Key Learnings
- HIV/AIDS, adult mortality, schooling, and income are the top predictors.
- Ensemble models outperform linear models in complex real-world data.
- Error analysis revealed underestimation in extreme countries (e.g., South Africa, Norway).

## 🧪 Files
- `notebook.ipynb`: full analysis & modeling
- `modelo_random_forest.pkl`: trained model
- `resultado_previsto.csv`: predictions on new data
- `requirements.txt`: libraries to reproduce

## 📦 Requirements
```bash
pip install -r requirements.txt
