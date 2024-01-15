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
 - **k_folds**: 5

## Optimized metric
f1

## Training time

15.2 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.471955 | nan         |
| auc       | 0.868821 | nan         |
| f1        | 0.808669 |   0.498751  |
| accuracy  | 0.806875 |   0.498751  |
| precision | 1        |   0.902776  |
| recall    | 1        |   0.0522118 |
| mcc       | 0.613767 |   0.498751  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.471955 |  nan        |
| auc       | 0.868821 |  nan        |
| f1        | 0.808669 |    0.498751 |
| accuracy  | 0.806875 |    0.498751 |
| precision | 0.804187 |    0.498751 |
| recall    | 0.8132   |    0.498751 |
| mcc       | 0.613767 |    0.498751 |


## Confusion matrix (at threshold=0.498751)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 638 |                159 |
| Labeled as 1.0  |                 150 |                653 |

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
