# Summary of 3_DecisionTree

[<< Go back](../README.md)


## Decision Tree
- **n_jobs**: -1
- **criterion**: gini
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

8.3 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.628486 |  nan        |
| auc       | 0.690439 |  nan        |
| f1        | 0.703024 |    0.258312 |
| accuracy  | 0.64375  |    0.474286 |
| precision | 0.774194 |    0.762963 |
| recall    | 1        |    0.182209 |
| mcc       | 0.299237 |    0.522936 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.628486 |  nan        |
| auc       | 0.690439 |  nan        |
| f1        | 0.657452 |    0.474286 |
| accuracy  | 0.64375  |    0.474286 |
| precision | 0.635308 |    0.474286 |
| recall    | 0.681196 |    0.474286 |
| mcc       | 0.288055 |    0.474286 |


## Confusion matrix (at threshold=0.474286)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 483 |                314 |
| Labeled as 1.0  |                 256 |                547 |

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
