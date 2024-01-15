# Summary of 113_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.05
- **depth**: 8
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

27.6 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.346759 | nan         |
| auc       | 0.935496 | nan         |
| f1        | 0.886279 |   0.494624  |
| accuracy  | 0.885    |   0.494624  |
| precision | 1        |   0.977903  |
| recall    | 1        |   0.0129416 |
| mcc       | 0.77007  |   0.494624  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.346759 |  nan        |
| auc       | 0.935496 |  nan        |
| f1        | 0.886279 |    0.494624 |
| accuracy  | 0.885    |    0.494624 |
| precision | 0.879755 |    0.494624 |
| recall    | 0.892902 |    0.494624 |
| mcc       | 0.77007  |    0.494624 |


## Confusion matrix (at threshold=0.494624)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 699 |                 98 |
| Labeled as 1.0  |                  86 |                717 |

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
