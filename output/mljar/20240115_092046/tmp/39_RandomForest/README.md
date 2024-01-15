# Summary of 39_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.8
- **min_samples_split**: 50
- **max_depth**: 7
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

18.0 seconds

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.415881 | nan          |
| auc       | 0.905192 | nan          |
| f1        | 0.8402   |   0.504415   |
| accuracy  | 0.84     |   0.504415   |
| precision | 1        |   0.95886    |
| recall    | 1        |   0.00216867 |
| mcc       | 0.68001  |   0.504415   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.415881 |  nan        |
| auc       | 0.905192 |  nan        |
| f1        | 0.8402   |    0.504415 |
| accuracy  | 0.84     |    0.504415 |
| precision | 0.842303 |    0.504415 |
| recall    | 0.838107 |    0.504415 |
| mcc       | 0.68001  |    0.504415 |


## Confusion matrix (at threshold=0.504415)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 671 |                126 |
| Labeled as 1.0  |                 130 |                673 |

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
