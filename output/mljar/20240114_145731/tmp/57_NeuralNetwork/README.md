# Summary of 57_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 32
- **dense_2_size**: 4
- **learning_rate**: 0.1
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **shuffle**: True
 - **stratify**: True
 - **k_folds**: 10

## Optimized metric
f1

## Training time

17.9 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.475904 | nan           |
| auc       | 0.894585 | nan           |
| f1        | 0.831615 |   0.225912    |
| accuracy  | 0.82125  |   0.492347    |
| precision | 1        |   1           |
| recall    | 1        |   2.44866e-10 |
| mcc       | 0.643396 |   0.492347    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.475904 |  nan        |
| auc       | 0.894585 |  nan        |
| f1        | 0.826667 |    0.492347 |
| accuracy  | 0.82125  |    0.492347 |
| precision | 0.805195 |    0.492347 |
| recall    | 0.849315 |    0.492347 |
| mcc       | 0.643396 |    0.492347 |


## Confusion matrix (at threshold=0.492347)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 632 |                165 |
| Labeled as 1.0  |                 121 |                682 |

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
