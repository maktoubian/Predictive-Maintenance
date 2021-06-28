# Predictive-Maintenance

A common bottleneck in the development of data-driven predictive maintenance methods was the lack of availability of run-to-failure data sets.
The lack of common data sets, which researchers can use to compare their approaches, has been an impediment to progress in the field of prognostics.
To tackle this problem, a prognostics data repository was established. Several datasets have been since published that have been used by researchers around the world. 
Among these datasets are five datasets from a turbofan engine simulation model - C-MAPSS (Commercial Modular Aero-Propulsion System Simulation).

The Datasets consisting of multiple multivariate time series. 
Each time series is from a different engine unit – i.e., the data can be considered to be from a fleet of engines of the same type.
Each engine unit starts with different degrees of initial wear and manufacturing variation which is unknown to the user. 
This wear and variation are considered normal, i.e., it is not considered a fault condition. 
There are three operational settings that have a substantial effect on engine performance. These settings are also included in the data. 
However, in the dataset used in this project, df_FD001, the engines are only subjected to a single operational setting and hence does not contribute to degradation learning. 
Additionally, the data is contaminated with sensor noise.

In this project, the python programming language will be used following different modules that help to measure the RUL of turbofan engine using a linear regression model.
