# Summary of 38_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.025
- **depth**: 6
- **rsm**: 1.0
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

15.7 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.502248 | nan         |
| auc       | 0.908864 | nan         |
| f1        | 0.871446 |   0.504344  |
| accuracy  | 0.87     |   0.504344  |
| precision | 1        |   0.87597   |
| recall    | 1        |   0.0411237 |
| mcc       | 0.740065 |   0.504344  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.502248 |  nan        |
| auc       | 0.908864 |  nan        |
| f1        | 0.871446 |    0.504344 |
| accuracy  | 0.87     |    0.504344 |
| precision | 0.865031 |    0.504344 |
| recall    | 0.877958 |    0.504344 |
| mcc       | 0.740065 |    0.504344 |


## Confusion matrix (at threshold=0.504344)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 687 |                110 |
| Labeled as 1.0  |                  98 |                705 |

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
