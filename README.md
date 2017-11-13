# PredictiveMonitoring
Predictive Monitoring of Network Operations Data


Goals
-Automating warning and critical levels for checks which measure performance values
-Automatically learn what normal is and detect any anomaly in the network infrastructure

Background and strategic fit

Strategy to estimate the network up time by predicting the health of the access points and build models and tools to automate prediction. 
Parameters (Ruckus) to predict the Access Point status are (more to be added/removed depending on the performance of the model and the correlations) :

AP Name Status
Alarm	Clients	Clients (2.4G)	Clients (5G)	Airtime Utilization (2.4G)	Airtime Utilization (5G)	Channel (2.4G)	Channel (5G)	Mesh Mode	Mesh Role	AP Firmware	Last Seen	Traffic (uplink)	Traffic (downlink)	WLAN Group (2.4G)	WLAN Group (5G)	Control Plane	LBS Status
 
 Results:
 Test set : 5+319 = Positive predictions
                2+3 = Negatives Predictions
                
  
