# Summary of 7_Default_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.1
- **depth**: 6
- **rsm**: 1
- **loss_function**: Logloss
- **eval_metric**: F1
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **shuffle**: True
 - **stratify**: True
 - **k_folds**: 5

## Optimized metric
f1

## Training time

13.9 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.338134 | nan         |
| auc       | 0.934405 | nan         |
| f1        | 0.882647 |   0.503789  |
| accuracy  | 0.8825   |   0.503789  |
| precision | 1        |   0.978997  |
| recall    | 1        |   0.0035815 |
| mcc       | 0.765011 |   0.503789  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.338134 |  nan        |
| auc       | 0.934405 |  nan        |
| f1        | 0.882647 |    0.503789 |
| accuracy  | 0.8825   |    0.503789 |
| precision | 0.884856 |    0.503789 |
| recall    | 0.880448 |    0.503789 |
| mcc       | 0.765011 |    0.503789 |


## Confusion matrix (at threshold=0.503789)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 705 |                 92 |
| Labeled as 1.0  |                  96 |                707 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Kolmogorov-Smirnov Statistic

![Kolmogorov-Smirnov Statistic](ks_statistic.png)


## Precision-Recall Curve

![Precision-Recall Curve](precision_recall_curve.png)


## Calibration Curve

![Calibration Curve](calibration_curve_curve.png)


## Cumulative Gains Curve

![Cumulative Gains Curve](cumulative_gains_curve.png)


## Lift Curve

![Lift Curve](lift_curve.png)



[<< Go back](../README.md)
