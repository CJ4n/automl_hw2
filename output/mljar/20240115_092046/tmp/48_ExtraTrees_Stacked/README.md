# Summary of 48_ExtraTrees_Stacked

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
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

25.6 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.288253 |  nan        |
| auc       | 0.952306 |  nan        |
| f1        | 0.902349 |    0.469814 |
| accuracy  | 0.90125  |    0.469814 |
| precision | 0.989474 |    0.998338 |
| recall    | 0.998755 |    0        |
| mcc       | 0.802576 |    0.469814 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.288253 |  nan        |
| auc       | 0.952306 |  nan        |
| f1        | 0.902349 |    0.469814 |
| accuracy  | 0.90125  |    0.469814 |
| precision | 0.895706 |    0.469814 |
| recall    | 0.909091 |    0.469814 |
| mcc       | 0.802576 |    0.469814 |


## Confusion matrix (at threshold=0.469814)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 712 |                 85 |
| Labeled as 1.0  |                  73 |                730 |

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
