# Summary of 56_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.7
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

18.6 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.559279 |  nan        |
| auc       | 0.816262 |  nan        |
| f1        | 0.740337 |    0.394395 |
| accuracy  | 0.74125  |    0.500677 |
| precision | 1        |    0.725793 |
| recall    | 1        |    0.114689 |
| mcc       | 0.483069 |    0.500677 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.559279 |  nan        |
| auc       | 0.816262 |  nan        |
| f1        | 0.736306 |    0.500677 |
| accuracy  | 0.74125  |    0.500677 |
| precision | 0.753585 |    0.500677 |
| recall    | 0.719801 |    0.500677 |
| mcc       | 0.483069 |    0.500677 |


## Confusion matrix (at threshold=0.500677)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 608 |                189 |
| Labeled as 1.0  |                 225 |                578 |

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
