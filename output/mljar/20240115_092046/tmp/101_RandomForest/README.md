# Summary of 101_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.7
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

27.2 seconds

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.422861 | nan          |
| auc       | 0.902897 | nan          |
| f1        | 0.836836 |   0.497116   |
| accuracy  | 0.835    |   0.497116   |
| precision | 1        |   0.95083    |
| recall    | 1        |   0.00569672 |
| mcc       | 0.670052 |   0.497116   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.422861 |  nan        |
| auc       | 0.902897 |  nan        |
| f1        | 0.836836 |    0.497116 |
| accuracy  | 0.835    |    0.497116 |
| precision | 0.830675 |    0.497116 |
| recall    | 0.843088 |    0.497116 |
| mcc       | 0.670052 |    0.497116 |


## Confusion matrix (at threshold=0.497116)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 659 |                138 |
| Labeled as 1.0  |                 126 |                677 |

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
