# Summary of 2_DecisionTree

[<< Go back](../README.md)


## Decision Tree
- **n_jobs**: -1
- **criterion**: entropy
- **max_depth**: 2
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **shuffle**: True
 - **stratify**: True
 - **k_folds**: 10

## Optimized metric
f1

## Training time

7.4 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.636627 |  nan        |
| auc       | 0.677789 |  nan        |
| f1        | 0.703024 |    0.258312 |
| accuracy  | 0.63125  |    0.469613 |
| precision | 1        |    0.967742 |
| recall    | 1        |    0.182209 |
| mcc       | 0.291359 |    0.258312 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.636627 |  nan        |
| auc       | 0.677789 |  nan        |
| f1        | 0.667043 |    0.469613 |
| accuracy  | 0.63125  |    0.469613 |
| precision | 0.609907 |    0.469613 |
| recall    | 0.73599  |    0.469613 |
| mcc       | 0.267752 |    0.469613 |


## Confusion matrix (at threshold=0.469613)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 419 |                378 |
| Labeled as 1.0  |                 212 |                591 |

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
