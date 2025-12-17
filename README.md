# NBA_Hall_of_Fame_Predictor
Machine learning models trained on historic NBA data to classify current NBA players as future hall of fame candidates or not. 

Models:
- Logistic Regression (baseline)
- Random Forest
- XGBoost

Results:     
                       Precision |   Recall  |    F1     |  ROC-AUC  |  PR-AUC  | 
Logistic Regression |  0.54±0.03   0.84±0.08   0.66±0.04   0.90±0.04   0.47±0.05
                    ---------------------------------------------------------------
Random Forest          0.75±0.07 | 0.78±0.07 | 0.76±0.06 | 0.97±0.02 | 0.83±0.07 |
                    ---------------------------------------------------------------
XGBoost                0.75±0.06 | 0.77±0.08 | 0.76±0.06 | 0.96±0.02 | 0.82±0.07 |
                    ---------------------------------------------------------------
