# Summary of 46_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.7
- **min_samples_split**: 40
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

19.4 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.544762 | nan         |
| auc       | 0.802623 | nan         |
| f1        | 0.742892 |   0.501894  |
| accuracy  | 0.74     |   0.501894  |
| precision | 1        |   0.901459  |
| recall    | 1        |   0.0708505 |
| mcc       | 0.480017 |   0.501894  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.544762 |  nan        |
| auc       | 0.802623 |  nan        |
| f1        | 0.742892 |    0.501894 |
| accuracy  | 0.74     |    0.501894 |
| precision | 0.737423 |    0.501894 |
| recall    | 0.748443 |    0.501894 |
| mcc       | 0.480017 |    0.501894 |


## Confusion matrix (at threshold=0.501894)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 583 |                214 |
| Labeled as 1.0  |                 202 |                601 |

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
