# Kenya-Rainfall-Forecasting

1. Project Overview
   
This project focuses on detecting extreme rainfall events using deep learning models: Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU) networks. The model is trained on historical rainfall data from different climate zones and counties to enhance rainfall prediction.
Traditional rainfall forecasting methods (e.g., statistical models and Numerical Weather Prediction) have limitations in capturing fine-grained, localized variations, and Recurrent Neural Networks (LSTM and GRU), offer a promising alternative.

2. Stakeholders
   
   (i)Farmers – Need rainfall forecasts for better crop planning.
   (ii)Government Agencies – Use insights for water and disaster management.
   (iii)Meteorologists – Enhance traditional weather forecasting with AI.
   (iv)Insurance Companies – Assess weather-related risks for crop insurance policies.
   (v)Non-Governmental Organizations (NGOs) – Support humanitarian efforts in flood-prone or drought-affected regions.
   
3. Analysis and Modeling
   
We cleaned the data to ensure accuracy and reliability. Inconsistencies were removed, and missing values were handled appropriately. Additionally, numerical features were normalized to enhance model convergence and stability.
Feature engineering played a crucial role in improving the model’s predictive power. Temporal features such as seasonality and lagged variables were created to capture trends in rainfall patterns. Rolling averages were also applied to smooth fluctuations and highlight long-term trends.
For modeling, both LSTM and GRU models were used to analyze sequential rainfall data. Various hyperparameter configurations were explored to optimize performance, including adjustments to the number of layers, learning rates, and dropout rates.
The models were evaluated using key metrics such as Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE). Additionally, performance was compared across different climate zones to assess generalizability and robustness.

4. Objective
   
The objective of this project is to develop a deep learning-based model for detecting extreme rainfall events using historical meteorological data. The model’s insights can help improve early warning systems, disaster preparedness, and climate adaptation strategies

5. Recommendations and conclusion
   
6. Tableau Dashboard
    
   Here we created a dashboard to show the average amount of rainfall per county from 1981-2025 and the Geographical Mapping. Here is the link https://public.tableau.com/app/profile/linda.temoet/viz/Kenya-Rainfall-Analysis/Dashboard1?publish=yes

7. Group Members
   (a) Delvin Osoro
   (b) Linda Temoet
   (c) Grace Mwega
   (d) Keith Kinyanjui
   (e) Godwin Mutuma
