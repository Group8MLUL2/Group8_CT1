# Retail RFM Analysis - Experiment Results

Report generated on: 2024-12-14 19:42:25

## Best Performing Model

- Model: SVR
- Test R² Score: 0.1523
- Test RMSE: 0.7279
- Test MAE: 0.1602
- Average CV R² Score: 0.0944

### Hyperparameters:
- C: 1.0
- epsilon: 0.1
- kernel: rbf

## Model Performance Comparison

| Model | Test R² | CV R² | RMSE | MAE |
| --- | --- | --- | --- | --- |
| SVR | 0.1523 | 0.0944 | 0.7279 | 0.1602 |
| ElasticNet | 0.0759 | 0.0341 | 0.7600 | 0.2335 |
| RandomForestRegressor | -0.2912 | -0.4139 | 0.8983 | 0.2118 |
| XGBRegressor | -0.5746 | -2.1837 | 0.9920 | 0.1985 |
| GradientBoostingRegressor | -2.4699 | -1.2892 | 1.4726 | 0.2542 |

## Detailed Model Information

### SVR

#### Metrics:
- Test R² Score: 0.1523
- Average CV R² Score: 0.0944
- Test RMSE: 0.7279
- Test MAE: 0.1602

#### Hyperparameters:
- C: 1.0
- epsilon: 0.1
- kernel: rbf


### ElasticNet

#### Metrics:
- Test R² Score: 0.0759
- Average CV R² Score: 0.0341
- Test RMSE: 0.7600
- Test MAE: 0.2335

#### Hyperparameters:
- alpha: 0.5
- l1_ratio: 0.5
- max_iter: 2000


### RandomForestRegressor

#### Metrics:
- Test R² Score: -0.2912
- Average CV R² Score: -0.4139
- Test RMSE: 0.8983
- Test MAE: 0.2118

#### Hyperparameters:
- max_depth: 15
- min_samples_split: 5
- n_estimators: 200


### XGBRegressor

#### Metrics:
- Test R² Score: -0.5746
- Average CV R² Score: -2.1837
- Test RMSE: 0.9920
- Test MAE: 0.1985

#### Hyperparameters:
- learning_rate: 0.1
- max_depth: 6
- n_estimators: 200


### GradientBoostingRegressor

#### Metrics:
- Test R² Score: -2.4699
- Average CV R² Score: -1.2892
- Test RMSE: 1.4726
- Test MAE: 0.2542

#### Hyperparameters:
- learning_rate: 0.1
- max_depth: 5
- n_estimators: 150

