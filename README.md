
# Satellite Data Correction for Improved PM10 Predictions
Objective:
The primary objective of this project is to correct satellite data using in situ stations, specifically utilizing an XGBoost model. The corrected satellite data aims to enhance the accuracy of predicting PM10 levels.

# Methodology:
The correction process involves the utilization of XGBoost, a machine learning model. The input data is sourced from CAMS satellites and 'TOAR' (Tropospheric Ozone Assessment Report) in situ stations. Notably, the correction addresses challenges arising from dirty and inaccurate data in the TOAR dataset. Statistical tests were employed to identify and exclude problematic stations, ensuring the quality of the training data.
