**Machine Learning-Based Energy Consumption Forecasting in Smart Grids**

This project focuses on predicting energy consumption in smart grid environments using Machine Learning techniques.

The goal is to build accurate regression models that can forecast total energy usage based on environmental and temporal features such as temperature, humidity, date, time, weekend, and holidays.

**Accurate forecasting helps in:**

  • Load balancing

  • Energy optimization

  • Renewable energy integration

  • Cost reduction

**🛠️ Technologies Used**

  • Python

  • Pandas

  • NumPy

  • Scikit-learn

  • Matplotlib

  • Seaborn

  • Feature Engine (Winsorizer)

  • Joblib

**📊 Dataset Description**

**The dataset contains the following features:**

  • DateTime
  
  • Temperature (°F)
  
  • Humidity
  
  • Hour, Minute, Day, Month, Year
  
  • Weekend (0/1)

  • Holiday (0/1)
  
  • TotalUsage (Target Variable)
  
  • Target Variable: Total Energy Consumption

**⚙️ Project Workflow**

  **Data Preprocessing**
  
  • Handling missing values
  
  • Outlier treatment using Winsorization
  
  • Feature scaling using StandardScaler
  
  • Feature selection using SelectKBest
  
  **Model Building**
  
  • Support Vector Regressor (SVR)
  
  • Random Forest Regressor
  
  **Model Evaluation**
  
  • Mean Squared Error (MSE)
  
  • Mean Absolute Error (MAE)
  
  • R² Score
  
  **Model Saving**

  • Models saved using Joblib for future use

**📈 Results**
| Model                   | R² Score | MSE   | MAE  |
| ----------------------- | -------- | ----- | ---- |
| SVM Regressor           | 0.58     | 89.83 | 7.31 |
| Random Forest Regressor | 0.93     | 15.00 | 2.84 |

