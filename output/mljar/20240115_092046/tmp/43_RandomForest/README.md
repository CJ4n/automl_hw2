# Summary of 43_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.7
- **min_samples_split**: 50
- **max_depth**: 3
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

16.4 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.551808 | nan         |
| auc       | 0.791477 | nan         |
| f1        | 0.74042  |   0.503795  |
| accuracy  | 0.7375   |   0.503795  |
| precision | 1        |   0.845388  |
| recall    | 1        |   0.0524277 |
| mcc       | 0.475017 |   0.503795  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.551808 |  nan        |
| auc       | 0.791477 |  nan        |
| f1        | 0.74042  |    0.503795 |
| accuracy  | 0.7375   |    0.503795 |
| precision | 0.734969 |    0.503795 |
| recall    | 0.745953 |    0.503795 |
| mcc       | 0.475017 |    0.503795 |


## Confusion matrix (at threshold=0.503795)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 581 |                216 |
| Labeled as 1.0  |                 204 |                599 |

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
