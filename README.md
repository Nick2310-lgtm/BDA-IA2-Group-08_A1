# Secure Data Orchestration – Case Study Implementation

## Overview

This repository implements the experimental evaluation described in
Section 5 of the case study using the MIMIC-III Clinical Database Demo (v1.4).

## Dataset

Download the MIMIC-III Clinical Database Demo from PhysioNet:

https://physionet.org/content/mimiciii-demo/1.4/

After downloading:

1. Extract the ZIP file.
2. Place `CHARTEVENTS.csv` in the same directory as the notebook.

The dataset is not included due to licensing restrictions.

## Workflow

1. Vital sign extraction from CHARTEVENTS
2. Mean aggregation per patient
3. Mean imputation
4. Binary risk classification (Logistic Regression)
5. Execution time measurement
6. K-Means clustering (k=3)
7. Performance visualization

## Execution

Install dependencies:
# Secure Data Orchestration – Case Study Implementation

## Overview

This repository implements the experimental evaluation described in
Section 5 of the case study using the MIMIC-III Clinical Database Demo (v1.4).

## Dataset

Download the MIMIC-III Clinical Database Demo from PhysioNet:

https://physionet.org/content/mimiciii-demo/1.4/

After downloading:

1. Extract the ZIP file.
2. Place `CHARTEVENTS.csv` in the same directory as the notebook.

The dataset is not included due to licensing restrictions.

## Workflow

1. Vital sign extraction from CHARTEVENTS
2. Mean aggregation per patient
3. Mean imputation
4. Binary risk classification (Logistic Regression)
5. Execution time measurement
6. K-Means clustering (k=3)
7. Performance visualization

## Execution

Install dependencies:
pip install -r requirements.txt
