# Summary of 69_NearestNeighbors_RandomFeature

[<< Go back](../README.md)


## k-Nearest Neighbors (Nearest Neighbors)
- **n_jobs**: -1
- **n_neighbors**: 3
- **weights**: distance
- **explain_level**: 1

## Validation
 - **validation_type**: kfold
 - **shuffle**: True
 - **stratify**: True
 - **k_folds**: 5

## Optimized metric
f1

## Training time

11.5 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.632674 |  nan        |
| auc       | 0.938015 |  nan        |
| f1        | 0.891224 |    0.367209 |
| accuracy  | 0.89     |    0.367209 |
| precision | 0.961739 |    0.788086 |
| recall    | 0.960149 |    0        |
| mcc       | 0.780072 |    0.367209 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.632674 |  nan        |
| auc       | 0.938015 |  nan        |
| f1        | 0.891224 |    0.367209 |
| accuracy  | 0.89     |    0.367209 |
| precision | 0.884663 |    0.367209 |
| recall    | 0.897883 |    0.367209 |
| mcc       | 0.780072 |    0.367209 |


## Confusion matrix (at threshold=0.367209)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 703 |                 94 |
| Labeled as 1.0  |                  82 |                721 |

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
