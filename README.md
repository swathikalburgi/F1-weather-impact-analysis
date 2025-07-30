# F1 weather impact analysis
Can the weather decide the outcome of a Formula 1 race? 
This project says **yes** (and models how wind, temperature, and rain impact race strategy and lap time for the 2025 Italian Grand Prix at Monza).<br/>

# About this project 
Using historical weather data and race outcomes, this project analyzes how temperature, humidity, and rainfall influence race performance. We draw correlations between weather conditions and driver results, helping us understand when weather is a game-changer.<br/>

# Features 
🌦️ Analysis of wind speed, pressure, and temperature on lap time<br/>
📊 Weather impact score to quantify race-day variability<br/>
⚡ Strategy insights based on predicted weather<br/>
⏱️ Lap time forecasting under different weather scenarios<br/>
📁 Trained model exported as f1_weather_model.pkl<br/> 

# Tech stack
- Python, pandas, seaborn, matplotlib<br/>
- scikit-learn<br/>
- Historical F1 and weather datasets<br/>
- Streamlit<br/>

# How it works
1. Load historical weather and performance data<br/>
2. Analyze the impact of each weather parameter<br/>
3. Train the ML model to predict the lap time deviation<br/>
4. Simulate Monza 2025 using forecasted values<br/>
5. Recommend a race strategy based on the prediction<br/>

# More
This is Part 2 of a 3-part F1 AI/ML series:
- [Race outcome analysis](https://github.com/swathikalburgi/F1-race-outcome-analysis) *(cool)*
- Weather impact analysis *(you're here)*
- Fan sentiment analysis *(also cool)*

