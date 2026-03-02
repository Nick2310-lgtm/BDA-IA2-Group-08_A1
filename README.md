# Secure Data Orchestration for Patient Monitoring – Case Study Implementation

This repository implements the experimental evaluation of the Secure Data Orchestration framework using ICU monitoring data from the MIMIC-III Clinical Database Demo (v1.4).

The implementation performs:

- Extraction and aggregation of vital signs from CHARTEVENTS  
- Mean imputation for incomplete attributes  
- Binary risk classification using Logistic Regression  
- Execution time measurement  
- K-Means clustering (k = 3) for patient stratification  
- Performance visualization  

## Setup

1. Download the MIMIC-III Clinical Database Demo (v1.4).
2. Place `CHARTEVENTS.csv` in the project directory.
3. Install dependencies: pip install -r requirements.txt
