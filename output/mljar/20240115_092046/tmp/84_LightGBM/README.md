# Summary of 84_LightGBM

[<< Go back](../README.md)


## LightGBM
- **n_jobs**: -1
- **objective**: binary
- **num_leaves**: 95
- **learning_rate**: 0.1
- **feature_fraction**: 0.8
- **bagging_fraction**: 0.8
- **min_data_in_leaf**: 15
- **metric**: custom
- **custom_eval_metric_name**: f1
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **shuffle**: True
 - **stratify**: True
 - **k_folds**: 5

## Optimized metric
f1

## Training time

23.3 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.363681 | nan           |
| auc       | 0.924221 | nan           |
| f1        | 0.873918 |   0.491094    |
| accuracy  | 0.8725   |   0.491094    |
| precision | 0.981982 |   0.995223    |
| recall    | 1        |   1.54196e-05 |
| mcc       | 0.745066 |   0.491094    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.363681 |  nan        |
| auc       | 0.924221 |  nan        |
| f1        | 0.873918 |    0.491094 |
| accuracy  | 0.8725   |    0.491094 |
| precision | 0.867485 |    0.491094 |
| recall    | 0.880448 |    0.491094 |
| mcc       | 0.745066 |    0.491094 |


## Confusion matrix (at threshold=0.491094)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 689 |                108 |
| Labeled as 1.0  |                  96 |                707 |

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
