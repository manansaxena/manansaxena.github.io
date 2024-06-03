---
cardtitle: Forecasting SARS-CoV-2 Concentrations in Wastewater
cardsummary: "Forecasting SARS-CoV-2 Concentrations in Wastewater at State College using Prophet, MLflow, Docker and Jenkins"
title: Forecasting SARS-CoV-2 Concentrations in Wastewater
template: page
summary: ""
img: images/sars-proj.jpg
importance: 1
category: fun
---


A project on forecasting SARS-CoV-2 concentrations in wastewater at State College.

Data Used: [NWSS Public SARS-CoV-2 Wastewater Metric Data](https://data.cdc.gov/Public-Health-Surveillance/NWSS-Public-SARS-CoV-2-Wastewater-Metric-Data/2ew6-ywp6/about_data)

Provided By: National Wastewater Surveillance System

# Tools Used:
-   Time Series Analysis: Statsmodel, Facebook Prophet (Forecasting at Scale)
-   Machine Learning Development and Packaging: mlflow 
-   Containerization: Docker
-   Continuous Integration/ Continuous Development(CI/CD): Jenkins

<b>[`Project Link`](https://github.com/manansaxena/forecasting_wastewater)</b>

# Results:

-  **Data Plot**: Plot of SARS-CoV-2 concentrations in wastewater across two years 

!TEMPLATE!
<div class="d-flex justify-content-center align-items-center mx-auto">
    {{ figure(path="images/wastewater-forecast/wastewater_data_plot.png",width="600px", height="300px", title="Plot of SARS-CoV-2 concentrations in wastewater across two years", class="img-fluid rounded z-depth-1") }}
</div>
!TEMPLATE!

-   **Timeseries Decomposition**: Season-Trend decomposition of the timeseries data

!TEMPLATE!
<div class="d-flex justify-content-center align-items-center mx-auto">
    {{ figure(path="images/wastewater-forecast/timeseries_decomposition.png",width="600px", height="300px",title="Season-Trend decomposition of the timeseries data", class="img-fluid rounded z-depth-1") }}
</div>
!TEMPLATE!

-   **Train Test Split**: Splitting the data for training and testing

!TEMPLATE!
<div class="d-flex justify-content-center align-items-center mx-auto">
    {{ figure(path="images/wastewater-forecast/train_test_split.png",width="600px", height="300px",title="Splitting the data for training and testing", class="img-fluid rounded z-depth-1") }}
</div>
!TEMPLATE!

-   **Prophet Forecast**: Prophet forecast with actual observations, changepoints and comparison with naive forecast

!TEMPLATE!
<div class="d-flex justify-content-center align-items-center mx-auto">
    {{ figure(path="images/wastewater-forecast/prophet_forecast_obs.png",width="600px", height="300px",title="Prophet forecast with actual observations, changepoints and comparison with naive forecast", class="img-fluid rounded z-depth-1") }}
</div>
!TEMPLATE!

-   **Model Components**: Time series components learnt by Prophet Model

!TEMPLATE!
<div class="d-flex justify-content-center align-items-center mx-auto">
    {{ figure(path="images/wastewater-forecast/model_components.png",width="600px", height="300px",title="Time series components learnt by Prophet Model", class="img-fluid rounded z-depth-1") }}
</div>
!TEMPLATE!