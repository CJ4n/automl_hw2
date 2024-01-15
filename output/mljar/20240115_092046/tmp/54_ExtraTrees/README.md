# Summary of 54_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.8
- **min_samples_split**: 40
- **max_depth**: 6
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

16.5 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.471996 | nan         |
| auc       | 0.896777 | nan         |
| f1        | 0.8356   |   0.496679  |
| accuracy  | 0.83375  |   0.496679  |
| precision | 1        |   0.849917  |
| recall    | 1        |   0.0288846 |
| mcc       | 0.667552 |   0.496679  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.471996 |  nan        |
| auc       | 0.896777 |  nan        |
| f1        | 0.8356   |    0.496679 |
| accuracy  | 0.83375  |    0.496679 |
| precision | 0.829448 |    0.496679 |
| recall    | 0.841843 |    0.496679 |
| mcc       | 0.667552 |    0.496679 |


## Confusion matrix (at threshold=0.496679)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 658 |                139 |
| Labeled as 1.0  |                 127 |                676 |

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
