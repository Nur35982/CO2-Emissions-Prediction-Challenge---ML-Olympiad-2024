# CO2 Emissions Prediction Challenge - ML Olympiad 2024

## 🏆 Achievement
Team **NSU_Sickle** secured **22nd place** in the **ML Olympiad 2024**, held in Dhaka, Bangladesh, and organized by **United International University (UIU)**.

---

## 🌍 Challenge Overview
The **CO2 Emissions Prediction Challenge** focused on addressing the critical issue of **carbon dioxide (CO2) emissions** and their impact on the environment. Participants were tasked to predict **CO2 emissions per capita for 2030** using global development indicators spanning socio-economic and environmental domains.  

This competition served as a platform for data scientists and environmental enthusiasts to contribute towards mitigating climate change and promoting sustainability by leveraging machine learning.

---

## 🎯 Objective
- Build predictive models that forecast **CO2 emissions per capita** for the year **2030**.  
- Use historical data (2000-2020) of global development indicators as input.  
- Provide insights to inform **policy decisions** and promote **sustainable development practices**.

---

## 📊 Dataset
- **Source**: World Bank DataBank.  
- **Indicators Included**:
  - Access to electricity.
  - Agricultural land, arable land, and forest area.
  - Annual freshwater withdrawals.
  - Energy consumption and renewable energy output.
  - Population growth and GDP per capita.  

The dataset captures essential socio-economic and environmental factors influencing CO2 emissions, spanning **2000-2020**.

---

## 📈 Results

- **Leaderboard Rank**: Secured **22nd place** out of numerous teams, showcasing our capability in tackling real-world environmental challenges.

### 🧠 Model Details

To address the forecasting task, we developed and evaluated several time-series models:

- **ARIMA (AutoRegressive Integrated Moving Average)**  
  - Classical statistical model used to establish a baseline and analyze temporal trends.

- **LSTM (Long Short-Term Memory)** Neural Network  
  - Leveraged deep learning to capture long-term dependencies in multivariate time series.  
  - Employed `MinMaxScaler` for data normalization.  
  - Network architecture included:
    - **LSTM layers** to model sequence data.
    - **Dense layers** for output mapping.
    - **Dropout layers** to prevent overfitting and improve generalization.

These models were trained on historical data (2000–2020) and used to generate predictions for CO2 emissions per capita for 2030.

---

## 🔍 Insights

- Incorporating both economic and environmental indicators helped improve the model’s ability to understand emission trends.
- LSTM models outperformed ARIMA in capturing complex temporal patterns in high-dimensional datasets.

---

## 📫 Contact

For more information, collaboration, or access to the project code, feel free to reach out to **Team NSU_Sickle**.
