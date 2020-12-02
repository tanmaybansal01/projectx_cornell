# Ride-hailing emissions modeling and reduction through ride demand prediction

### Tanmay Bansal, Ruchika Dongre, Kassie Wang, Sam Fuchs
#### Cornell University

November 30, 2020

<hr>

Transportation is the largest contributor of greenhouse gas emissions in the United States.As Transportation Network Companies (TNCs), such as Uber and Lyft, grow in prevalence,it is imperative to quantify their emissions impact. We studied the case of Austin, Texasthrough its primary ride-hailing service - RideAustin - that has released data on 1.4+ millionindividual rides over an 11-month period. We estimated a total of 6014.95 metric tonnesof CO 2 emissions from deadheading (when there are no passengers in freight) over thegiven time period. We clustered Austin into different zones and built an LSTM-based neuralnetwork for hourly ride demand forecasting on each zone through spatiotemporal features(weather, federal holidays, day of the week, and a look-back interval). Despite a muchlarger out-of-time validation window (7 months), our model outperforms the XGBoost-basedbaseline model by 34.86\% and the next best comparable model in current literature by15.3\% in terms of MAE. In addition, we estimated a 10.624\% reduction in total deadheadingemissions for the same period given that the ride-hailing drivers on road are routed accordingto the proposed hourly ride demand forecasts.