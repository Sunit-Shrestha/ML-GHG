# ML-GHG

This repository accompanies the paper *"ML Driven Framework for GHG Scenario Assessment towards Sustainable Municipal Solid Waste Management in Data-Scarce Nepal."*

## Contents

- `code/ann-final-clean-full-prediction-pipeline.ipynb` — full ANN pipeline for municipal solid waste (MSW) generation prediction.

## What the notebook covers

- Data loading, preprocessing (log transform, RobustScaler, one-hot encoding), and stratified train/val/test splitting.
- ANN model definition (PyTorch) and training using the final, already optimized hyperparameters.
- Evaluation (R², MAE, RMSE, SMAPE) and predicted vs. actual plots.
- Mass, municipality-wise time-series prediction of MSW generation (2021–2051) from forecasted input features.

**Note:** Hyperparameter search was performed using Optuna, but the search code is not included here — only the final selected hyperparameters are used for training.

<img width="7520" height="2988" alt="GA_Low_Quality" src="https://github.com/user-attachments/assets/d0bd5c5d-0e35-486d-bfd6-dc4f9121b926" />



