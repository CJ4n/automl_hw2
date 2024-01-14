# Summary of 9_Default_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.9
- **min_samples_split**: 30
- **max_depth**: 4
- **eval_metric_name**: f1
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **shuffle**: True
 - **stratify**: True
 - **k_folds**: 10

## Optimized metric
f1

## Training time

24.3 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.461439 | nan         |
| auc       | 0.875408 | nan         |
| f1        | 0.820766 |   0.503039  |
| accuracy  | 0.81875  |   0.503039  |
| precision | 0.978261 |   0.951623  |
| recall    | 1        |   0.0360461 |
| mcc       | 0.637546 |   0.503039  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.461439 |  nan        |
| auc       | 0.875408 |  nan        |
| f1        | 0.820766 |    0.503039 |
| accuracy  | 0.81875  |    0.503039 |
| precision | 0.814724 |    0.503039 |
| recall    | 0.826899 |    0.503039 |
| mcc       | 0.637546 |    0.503039 |


## Confusion matrix (at threshold=0.503039)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 646 |                151 |
| Labeled as 1.0  |                 139 |                664 |

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
