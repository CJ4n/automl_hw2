# Summary of 70_NearestNeighbors

[<< Go back](../README.md)


## k-Nearest Neighbors (Nearest Neighbors)
- **n_jobs**: -1
- **n_neighbors**: 7
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

9.4 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.395343 |  nan        |
| auc       | 0.945717 |  nan        |
| f1        | 0.882611 |    0.428571 |
| accuracy  | 0.883125 |    0.428571 |
| precision | 0.987113 |    0.857143 |
| recall    | 0.985056 |    0        |
| mcc       | 0.766362 |    0.428571 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.395343 |  nan        |
| auc       | 0.945717 |  nan        |
| f1        | 0.882611 |    0.428571 |
| accuracy  | 0.883125 |    0.428571 |
| precision | 0.889873 |    0.428571 |
| recall    | 0.875467 |    0.428571 |
| mcc       | 0.766362 |    0.428571 |


## Confusion matrix (at threshold=0.428571)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 710 |                 87 |
| Labeled as 1.0  |                 100 |                703 |

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
