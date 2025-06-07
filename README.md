# ⚡ EVision: Machine Learning for EV Mileage Insight

A machine learning project focused on predicting the mileage (distance driven per charge) of Electric Vehicles (EVs) using real-world charging session and vehicle data. The model aims to help users identify high-efficiency EVs by analyzing charging behavior, battery characteristics, and environmental conditions.

## 🚀 Objective

Predict EV mileage using regression models and key input features such as:
- Charging time
- Energy consumed
- Charging cost
- Battery capacity
- Driving patterns
- Ambient temperature

## 📊 Dataset Overview

The dataset includes:
- User details: ID, vehicle model, usage type
- Charging sessions: time, energy used, location
- Battery metrics: charge level, battery size
- Driving behavior: distance driven
- Environmental & financial data: temperature, cost

## 🔧 Data Preprocessing

- Handled missing values with median imputation
- Removed rows with missing target values
- Removed outliers where distance > 300 km
- Performed correlation analysis for feature selection

## 📈 Models Evaluated

- ✅ **Random Forest Regressor** (Best performance)
- Gradient Boosting Regressor
- Support Vector Regressor
- K-Nearest Neighbors

**Best Model: Random Forest**
- R² Score: 0.8524
- MAE: 27.23
- MSE: 1065.48
- RMSE: 32.64

## 📌 Key Insights

- Battery capacity, energy consumed, and ambient temperature are strong predictors of EV mileage
- Random Forest outperformed all other models in predictive power and error minimization

## 🔮 Future Scope

- Integrate more real-world variables like road type, traffic, and weather
- Expand the model to recommend EVs based on cost-efficiency and user preferences
- Explore advanced models like Neural Networks

## 🛠️ Technologies Used

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Regression Models (ML)

## 👨‍💻 Team Members

- Chetan Bhangare  
- Ujjwal Pandit  
- Vedant More  
- Hari Prasath K P  
- Chetan Kharkar  

---

**💡 Contact**  
Have questions or feedback? Feel free to connect on [LinkedIn](https://www.linkedin.com/in/chetanbhangare-ai-ml/) or open an issue!

