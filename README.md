# Independent_Component_Analysis-
"A Machine learning automated pipeline for EEG artifact removal using Independent Component Analysis (ICA) and statistical thresholding (Kurtosis/Skewness)."
# Title: Automated EEG Signal Cleaning via FastICA
OverviewThis project provides an end-to-end pipeline to clean EEG data. It addresses common noise issues like eye blinks and muscle artifacts by decomposing signals into independent components and automatically flagging noise based on statistical "spikiness.
# Key Features
# Preprocessing:
Automated mean-imputation and standard scaling.
# Decomposition:
Utilizes the FastICA algorithm to isolate neural sources.
# Auto-Detection:
Uses Kurtosis ($>8$) and Skewness ($>2$) thresholds to identify and zero out artifacts without manual intervention.
# Reconstruction: 
Mathematically reconstructs the "clean" sensor data from filtered components.
<img width="1212" height="701" alt="image" src="https://github.com/user-attachments/assets/629428c7-3130-47d7-b5e1-94d164b0ecd4" />
<img width="1489" height="989" alt="image" src="https://github.com/user-attachments/assets/4d034a8e-0f64-40c2-bb48-1130f8e4ed8a" />
<img width="559" height="435" alt="image" src="https://github.com/user-attachments/assets/0de22249-22ea-4064-91eb-cfc33476b096" />
<img width="283" height="174" alt="image" src="https://github.com/user-attachments/assets/88a0865f-8fc6-4d91-b21d-f0f5d4a43d6b" />
<img width="546" height="174" alt="image" src="https://github.com/user-attachments/assets/39d5bbaf-709a-42a8-8e82-60161edd2174" />
