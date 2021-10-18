# Credit_Risk_Analysis

<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/1.PNG" /></p>

## Background

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

### Deliverable 1: Use Resampling Models to Predict Credit Risk

Using imbalanced-learn and scikit-learn libraries, evaluate three machine learning models by using resampling to determine which is better at predicting credit risk. First, use the oversampling RandomOverSampler and SMOTE algorithms, and then use the undersampling ClusterCentroids algorithm. Using these algorithms, resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.


### Oversampling RandomOverSampler algorithm.
- The balanced accuracy score is 66%.

#### For high-risk:
- Precision score is 1% (Positive Predictive value PPV).
- Recall score is 66% (sensitivity). 
- 66% high-risk cases are correctly predicted by the oversampling RandomOverSampler with a F1 score of 2%.

#### For low-risk.
- Precision score is 100% (Positive Predictive value PPV)
- Recall score is 67% (sensitivity). 
- 67% low-risk are correctly predicted by the oversampling RandomOverSampler with a F1 score of 80%.

#### Avg/F1 score of 80% (Marmonic Mean).

<p align="center">Accuracy score for the model.</p>
<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/2.PNG" /></p>

<p align="center">Confusion matrix algorithm.</p>
<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/3.PNG" /></p>

<p align="center">Imbalanced classification report.</p>
<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/4.PNG" /></p>



### Oversampling SMOTE 
- The balanced accuracy score is 63%.

#### For high-risk:
- Precision score is 1% (Positive Predictive value PPV).
- Recall score is 62% (sensitivity). 
- 62% high-risk cases are correctly predicted by the oversampling SMOTE with a F1 score of 2%.

#### For low-risk.
- Precision score is 100% (Positive Predictive value PPV)
- Recall score is 64% (sensitivity). 
- 64% low-risk are correctly predicted by the oversampling RandomOverSampler with a F1 score of 78%.

#### Avg/F1 score of 78% (Marmonic Mean).

<p align="center">Accuracy score for the model.</p>
<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/5.PNG" /></p>

<p align="center">Confusion matrix algorithm.</p>
<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/6.PNG" /></p>

<p align="center">Imbalanced classification report.</p>
<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/7.PNG" /></p>



### Undersampling ClusterCentroids algorithm.
- The balanced accuracy score is 52%.

#### For high-risk:
- Precision score is 1% (Positive Predictive value PPV).
- Recall score is 61% (sensitivity). 
- 61% high-risk cases are correctly predicted by the Undersampling ClusterCentroids algorithm with a F1 score of 1%.

#### For low-risk.
- Precision score is 100% (Positive Predictive value PPV)
- Recall score is 45% (sensitivity). 
- 64% low-risk are correctly predicted by the Undersampling ClusterCentroids algorithm with a F1 score of 62%.

#### Avg/F1 score of 62% (Marmonic Mean).

<p align="center">Accuracy score for the model.</p>
<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/8.PNG" /></p>

<p align="center">Confusion matrix algorithm.</p>
<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/9.PNG" /></p>

<p align="center">Imbalanced classification report.</p>
<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/10.PNG" /></p>


### Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk

### The combinatorial SMOTEENN algorithm.
- The balanced accuracy score is 63%.

#### For high-risk:
- Precision score is 1% (Positive Predictive value PPV).
- Recall score is 70% (sensitivity). 
- 70% high-risk cases are correctly predicted by the SMOTEENN algorithm with a F1 score of 2%.

#### For low-risk.
- Precision score is 100% (Positive Predictive value PPV)
- Recall score is 57% (sensitivity). 
- 57% low-risk are correctly predicted by the SMOTEENN algorithm with a F1 score of 73%.

#### Avg/F1 score of 72% (Marmonic Mean).

<p align="center">Accuracy score for the model.</p>
<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/11.PNG" /></p>

<p align="center">Confusion matrix algorithm.</p>
<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/12.PNG" /></p>

<p align="center">Imbalanced classification report.</p>
<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/13.PNG" /></p>



