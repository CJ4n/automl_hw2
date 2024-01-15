# Summary of 49_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 1.0
- **min_samples_split**: 20
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

29.9 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.598354 | nan         |
| auc       | 0.762498 | nan         |
| f1        | 0.731959 |   0.498159  |
| accuracy  | 0.7075   |   0.498159  |
| precision | 1        |   0.901639  |
| recall    | 1        |   0.0514286 |
| mcc       | 0.421115 |   0.498159  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.598354 |  nan        |
| auc       | 0.762498 |  nan        |
| f1        | 0.731959 |    0.498159 |
| accuracy  | 0.7075   |    0.498159 |
| precision | 0.677625 |    0.498159 |
| recall    | 0.795766 |    0.498159 |
| mcc       | 0.421115 |    0.498159 |


## Confusion matrix (at threshold=0.498159)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 493 |                304 |
| Labeled as 1.0  |                 164 |                639 |

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
