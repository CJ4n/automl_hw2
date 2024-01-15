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
 - **k_folds**: 5

## Optimized metric
f1

## Training time

6.4 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.626535 |  nan        |
| auc       | 0.695482 |  nan        |
| f1        | 0.703428 |    0.264535 |
| accuracy  | 0.645    |    0.471154 |
| precision | 0.786517 |    0.762626 |
| recall    | 1        |    0.174296 |
| mcc       | 0.304565 |    0.524476 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.626535 |  nan        |
| auc       | 0.695482 |  nan        |
| f1        | 0.656174 |    0.471154 |
| accuracy  | 0.645    |    0.471154 |
| precision | 0.638398 |    0.471154 |
| recall    | 0.674969 |    0.471154 |
| mcc       | 0.290317 |    0.471154 |


## Confusion matrix (at threshold=0.471154)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 490 |                307 |
| Labeled as 1.0  |                 261 |                542 |

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
