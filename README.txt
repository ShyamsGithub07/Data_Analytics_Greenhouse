Objective:
To realize a controlled environment for plants, temperature, humidity, soil moisture, CO₂, and light intensity must be constantly monitored. To do this, I created a Python pipeline that would take in, clean, and analyze the hourly IoT sensor data from the greenhouse operation. The project included EDA, KPI computation for time spent in the perfect range, anomaly detection with rule-based methods z-scores, and M.L. (Isolation Forest), analysis of cross-correlation between variables, forecasting future temperature trends, and automated reporting with visualizations. The pipeline provides greenhouse operators with the tools to make sustainable plant growth decisions based on the data.

About the Dataset:
The data are  simulated hourly IoT sensor readings for temperature (°C), humidity (%), soil moisture (%), CO₂ (ppm), and light intensity over a specific period of time. Each recording has the following fields: 'timestamp': The moment of measurement 'temperature': in Celsius 'humidity': in percent 'soil_moisture': in percent 'co2': in parts per million 'light': in lux. Initially, the raw data is cleaned, resampled to hourly intervals, interpolated for small gaps, and analyzed to detect anomalies, compute KPIs, and forecast future conditions.

Guidelines to Use the Script:
1.  Place the dataset in the raw/greenhouse_raw.csv path. 
2.  Run greenhouse_analytics.py to execute the full pipeline. 
3.  The pipeline will generate cleaned data, anomaly reports, visualizations, forecast outputs, and an auto-generated Markdown report.

Conclusion of Project: 
1. The whole process of the data pipeline is depicted as one of the most important steps, as 
2. it clears the raw data that contain sensors' information and also organizes it in a way that can be used for further analysis.
3. Rule-based approaches, statistics and machine learning methods are deployed to spot anomalies in temperature, humidity, soil moisture, CO₂ and light.
4. KPIs act as a mirror reflecting the conditions that are very often in optimal ranges.
5. The light and temperature areas has been connected through a cross-correlation analysis done by the researchers.
6. The forecasting predicts that the coming week would have certain temperature trends which can help the manager to keep the environment management proactive.
7. Greenhouse optimization is supported by the combination of visualizations and automated reports that enable fast and easy decision-making.

