# Summary of 88_Xgboost

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: binary:logistic
- **eta**: 0.15
- **max_depth**: 8
- **min_child_weight**: 1
- **subsample**: 0.6
- **colsample_bytree**: 0.5
- **eval_metric**: f1
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **shuffle**: True
 - **stratify**: True
 - **k_folds**: 5

## Optimized metric
f1

## Training time

24.6 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.340645 | nan           |
| auc       | 0.929105 | nan           |
| f1        | 0.872705 |   0.463067    |
| accuracy  | 0.87125  |   0.526097    |
| precision | 0.992126 |   0.985371    |
| recall    | 1        |   9.09987e-05 |
| mcc       | 0.743293 |   0.568971    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.340645 |  nan        |
| auc       | 0.929105 |  nan        |
| f1        | 0.870113 |    0.526097 |
| accuracy  | 0.87125  |    0.526097 |
| precision | 0.881226 |    0.526097 |
| recall    | 0.859278 |    0.526097 |
| mcc       | 0.742753 |    0.526097 |


## Confusion matrix (at threshold=0.526097)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 704 |                 93 |
| Labeled as 1.0  |                 113 |                690 |

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
