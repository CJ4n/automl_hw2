# Summary of 72_NearestNeighbors

[<< Go back](../README.md)


## k-Nearest Neighbors (Nearest Neighbors)
- **n_jobs**: -1
- **n_neighbors**: 3
- **weights**: uniform
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **shuffle**: True
 - **stratify**: True
 - **k_folds**: 5

## Optimized metric
f1

## Training time

9.5 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.594962 |  nan        |
| auc       | 0.939335 |  nan        |
| f1        | 0.889167 |    0.333333 |
| accuracy  | 0.889375 |    0.333333 |
| precision | 0.961404 |    0.666667 |
| recall    | 0.965131 |    0        |
| mcc       | 0.778806 |    0.333333 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.594962 |  nan        |
| auc       | 0.939335 |  nan        |
| f1        | 0.889167 |    0.333333 |
| accuracy  | 0.889375 |    0.333333 |
| precision | 0.894207 |    0.333333 |
| recall    | 0.884184 |    0.333333 |
| mcc       | 0.778806 |    0.333333 |


## Confusion matrix (at threshold=0.333333)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 713 |                 84 |
| Labeled as 1.0  |                  93 |                710 |

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
