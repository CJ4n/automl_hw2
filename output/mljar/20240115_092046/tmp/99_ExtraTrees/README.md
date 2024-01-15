# Summary of 99_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.7
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

22.1 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.467721 | nan         |
| auc       | 0.900361 | nan         |
| f1        | 0.835206 |   0.500683  |
| accuracy  | 0.835    |   0.500683  |
| precision | 1        |   0.808533  |
| recall    | 1        |   0.0433628 |
| mcc       | 0.67001  |   0.500683  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.467721 |  nan        |
| auc       | 0.900361 |  nan        |
| f1        | 0.835206 |    0.500683 |
| accuracy  | 0.835    |    0.500683 |
| precision | 0.837297 |    0.500683 |
| recall    | 0.833126 |    0.500683 |
| mcc       | 0.67001  |    0.500683 |


## Confusion matrix (at threshold=0.500683)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 667 |                130 |
| Labeled as 1.0  |                 134 |                669 |

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
