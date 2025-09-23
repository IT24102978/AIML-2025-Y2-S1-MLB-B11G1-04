# Airline Delay Analysis – Progress Review I (Data Preprocessing \& EDA)



## Overview



This project explores and prepares a large U.S. airline on-time performance dataset to understand delay patterns and to build a clean feature set for downstream modelling (e.g., predicting arrival/departure delays). Each team member contributes one preprocessing technique plus an EDA visualization; the group integrates everyone’s work into a single pipeline notebook.



---



## Dataset


**Name:** Airline Delay Analysis  
- **Source:** Kaggle (CSV, ~778 MB; 1M+ records; 25+ features)  
- **Link:** https://www.kaggle.com/datasets/sherrytp/airline-delay-analysis/data  
- **Targets/labels:** `ARR_DELAY`, `DEP_DELAY`  
- **Feature types (examples):**  
  - Numerical: `CRS_DEP_TIME`, `DEP_TIME`, `DEP_DELAY`, `TAXI_OUT`, `WHEELS_OFF`, `AIR_TIME`, `DISTANCE`, `TAXI_IN`, `CRS_ARR_TIME`, `ARR_TIME`, `ARR_DELAY`, `CARRIER_DELAY`, `WEATHER_DELAY`, `NAS_DELAY`, `SECURITY_DELAY`, `LATE_AIRCRAFT_DELAY`  
  - Categorical: `OP_UNIQUE_CARRIER`, `ORIGIN`, `DEST`, `DIVERTED`, `CANCELLED`, `CANCELLATION_CODE`  


---


## Roles & Individual Contributions


| IT24102978 | Handling Missing Data | Before/after null counts |

| IT24102889 | Encode Categorical Variables | Cardinality check |

| IT24102834 | Outlier Removal | Rule (IQR/z-score) |

| IT24102856 | Scaling/Normalization | Distribution/scatter before/after |

| IT24102942 | Feature Engineering | New features - correlation/importance |

| IT24102979 | Dimensionality Reduction  | PCA |


---


## How to Run



1. Download Jupyter Notebook
2. Install these packages - pandas numpy matplotlib seaborn scikit-learn jupyter
3. Run ..results/outputs/finalpipeline.ipynb



