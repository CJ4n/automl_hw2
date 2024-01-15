# Summary of 76_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.1
- **depth**: 7
- **rsm**: 1.0
- **loss_function**: Logloss
- **eval_metric**: F1
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **shuffle**: True
 - **stratify**: True
 - **k_folds**: 5

## Optimized metric
f1

## Training time

17.1 seconds

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.392267 | nan          |
| auc       | 0.922976 | nan          |
| f1        | 0.876404 |   0.501555   |
| accuracy  | 0.87625  |   0.501555   |
| precision | 1        |   0.955089   |
| recall    | 1        |   0.00557784 |
| mcc       | 0.752511 |   0.501555   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.392267 |  nan        |
| auc       | 0.922976 |  nan        |
| f1        | 0.876404 |    0.501555 |
| accuracy  | 0.87625  |    0.501555 |
| precision | 0.878598 |    0.501555 |
| recall    | 0.874222 |    0.501555 |
| mcc       | 0.752511 |    0.501555 |


## Confusion matrix (at threshold=0.501555)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 700 |                 97 |
| Labeled as 1.0  |                 101 |                702 |

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
