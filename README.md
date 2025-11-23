# 🇸🇦 Tura2030 — Saudi Tourism Forecasting  
Tourism forecasting and guiding Saudi Arabia toward global tourism presence.

---

## 📌 Overview  
Saudi Arabia aims to welcome **150 million tourists by 2030**.  
With major global events such as **LEAP**, **Expo 2030**, and the **2034 World Cup**, accurate forecasting becomes essential to support successful tourism planning and Vision 2030 goals.

This project analyzes and forecasts:
- **Visitors count**
- **Tourism spending**

for both:
- **Domestic tourism**
- **Inbound (international) tourism**

---

## 🎯 Problem Statement  
The rapid development of Saudi Arabia’s tourism sector requires **high-accuracy forecasting** to ensure:
- Resource and accommodation planning  
- Transportation and infrastructure readiness  
- Enhanced hospitality experiences  
- Smart data-driven decision-making  

Accurate predictions help guide the Kingdom toward a **global tourism presence**.

---

## 💡 Motivations  
- Support key tourism sectors with trusted insights  
- Strengthen long-term planning for events and regional development  
- Build smart models that reflect true Saudi hospitality  
- Help guide Saudi Arabia toward becoming a leading global tourism hub  

---

## 🔁 Forecasting Approach  
1. **Collect real Saudi tourism data**  
2. **Apply time-series forecasting models**  
3. **Predict visitor growth and tourism spending**  
4. **Analyze and visualize forecasts**

---

## 🤖 Models & Evaluation  
Four models were tested and compared:

### 🔹 **AutoARIMA**
Handles linear trends and shifting seasonal patterns.

### 🔹 **BlockRNN (Darts – Deep Learning)**
Captures nonlinear and complex multivariate relationships.

### 🔹 **AutoTBATS**
Best for:
- Multiple seasonalities  
- Complex oscillations  
- Monthly fluctuating tourism patterns  

### 🔹 **Prophet**
Great for trends, simple seasonality, and holiday effects.  
Best performer for domestic tourism.

---

## 🏆 Model Performance  

| Tourism Type | Best Model | Visitors Error | Spending Error |
|--------------|------------|----------------|----------------|
| **Domestic** | Prophet    | **7.6%**       | **10.6%**      |
| **Inbound**  | AutoTBATS  | **14.5%**      | **27.5%**      |

---

## 📈 Forecasting the Future  

- Increasing monthly visitor volume  
- Strong seasonal peaks  
- Growth in tourism spending  
- Clear upward long-term trends  
- Forecast confidence ranges  

(You can add figures inside the `results/` folder)

---

## 🎥 Project Demo 
 https://saudiarabiatourismforecast-yrjfkmor8tkwd9spo4fib9.streamlit.app/
The Streamlit app link is currently inactive, but here is a video demonstrating the dashboard and how the system works:


▶️ **https://github.com/shahadFawaz99/saudi_arabia_tourism_forecast/blob/main/turademo.mp4**  


---

## 🔮 Future Work  
- Forecast accommodation demand and regional tourism patterns  
- Improve model performance through further tuning and hybrid modeling  
- Apply NLP to extract insights from visitor reviews and feedback  
- Deploy the system as a live dashboard or API  

---

## 🛠️ Libraries & Tools  
- **Python**  
- **Pandas, NumPy**  
- **Darts (AutoTBATS, BlockRNN)**  
- **Prophet**  
- **scikit-learn**  
- **Matplotlib, Seaborn, Plotly**  
- **FastAPI**  
- **Streamlit**  
- **Jupyter Notebook**  
- **Docker**  
- **GitHub**  
- **Visual Studio Code**

