# COVID-19 prediction
Spatiotemporal Prediction of COVID-19 And Mobility

Citation: Nikparvar, B., Rahman, M.M., Hatami, F. et al. Spatio-temporal prediction of the COVID-19 pandemic in US counties: modeling with a deep LSTM neural network. Sci Rep 11, 21715 (2021). https://doi.org/10.1038/s41598-021-01119-3

# MTS-LSTM: Spatio-temporal Prediction of the COVID-19 Pandemic in US Counties: Modeling with A DeepLSTM Neural Network
MTS-LSTM is a deep learning model based on long short term memory to predict dynamics of new cases and deaths for contagious diseases (e.g., Covid-19).  

- The model is a multi-variate LSTM-based neural network with mobility. 
- It is trained on multiple time series samples at the same time. Compared to the single time-series LSTM, our model predicts the dynamics of disease within different sub-populations simultaneously.
- MTS-LSTM takes advantage of disease spread data from one sub-population to predict disease dynamics in other sub-populations. This is a very attractive feature at the beginning of pandemics.
- The model is capable of predicting the dynamics of disease in multiple levels of granularity (e.g. county or state) at the same time.
- The model is flexible to add new variables (e.g., hospital capacity, vaccination rates)

Some prediction results for confirmed cases, deaths, and foot traffic:
- Model 1: MTS-LSTM with confirmed cases and deaths
- Model 2: MTS-LSTM with confirmed cases, deaths, and foot traffic
- Ensemble: Predictions from ensemble model implemented by COVID-19 Forecast Hub in collaboration with CDC (benchmark)

![Large-Mid-small counties](https://user-images.githubusercontent.com/9162866/125010557-c2706880-e034-11eb-826f-5582a0c92535.jpg)

