# Summary of 1_DecisionTree

[<< Go back](../README.md)


## Decision Tree
- **n_jobs**: -1
- **criterion**: entropy
- **max_depth**: 4
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **shuffle**: True
 - **stratify**: True
 - **k_folds**: 10

## Optimized metric
f1

## Training time

7.7 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.54808  |  nan        |
| auc       | 0.825435 |  nan        |
| f1        | 0.761853 |    0.333333 |
| accuracy  | 0.758125 |    0.54717  |
| precision | 0.972222 |    0.992248 |
| recall    | 0.997509 |    0        |
| mcc       | 0.518449 |    0.54717  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.54808  |   nan       |
| auc       | 0.825435 |   nan       |
| f1        | 0.747883 |     0.54717 |
| accuracy  | 0.758125 |     0.54717 |
| precision | 0.784153 |     0.54717 |
| recall    | 0.714819 |     0.54717 |
| mcc       | 0.518449 |     0.54717 |


## Confusion matrix (at threshold=0.54717)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 639 |                158 |
| Labeled as 1.0  |                 229 |                574 |

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
