
# 🚦 Smart City Traffic Pattern Forecasting

## 📍 Project Overview
This project is part of a smart city initiative focused on **predicting traffic patterns** using historical data from multiple city junctions. The goal is to help governments anticipate peak traffic periods and optimize infrastructure planning accordingly.

## 🗂️ Dataset
- **Source**: [Kaggle - Smart City Traffic Patterns](https://www.kaggle.com/utathya/smart-city-traffic-patterns)
- **Data Format**: Time series data across four junctions
- **Features**: Timestamp, Vehicle count, Junction IDs

## 🎯 Objectives
- Analyze traffic trends based on hour, weekday, and month
- Build machine learning models to forecast vehicle count
- Evaluate model performance using MSE and R² score

## 📊 Exploratory Data Analysis
- Time-based features extracted: Hour, Day, Weekday, Month, Year, IsWeekend
- Visualizations:
  - 📈 Average vehicle count per hour
  - 📉 Weekday trends
  - 📆 Monthly traffic patterns

## 🤖 Machine Learning Models
| Model                | MSE     | R² Score |
|---------------------|---------|----------|
| Linear Regression    | 161.21  | 0.60     |
| Random Forest        | 12.63   | 0.97     |

✅ Random Forest performed significantly better, indicating non-linear relationships in traffic data.

## 🧠 Key Learnings
- Time-based features improve model accuracy
- Feature engineering plays a crucial role in time series data
- Random Forest is more robust for traffic forecasting tasks

## 🔧 Tech Stack
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

## 🗓️ Future Work
- Train separate models per junction
- Include holiday/event-based traffic anomalies
- Deploy model using Flask or Streamlit for real-time forecasting
