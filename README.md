# Credit_Risk_Analysis

<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/1.PNG" /></p>

## Background

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

### Deliverable 1: Use Resampling Models to Predict Credit Risk

Using imbalanced-learn and scikit-learn libraries, evaluate three machine learning models by using resampling to determine which is better at predicting credit risk. First, use the oversampling RandomOverSampler and SMOTE algorithms, and then use the undersampling ClusterCentroids algorithm. Using these algorithms, resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.


### Oversampling RandomOverSampler algorithm.

<p align="center">Accuracy score for the model.</p>
<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/2.PNG" /></p>

<p align="center">Confusion matrix algorithm.</p>
<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/3.PNG" /></p>

<p align="center">Imbalanced classification report.</p>
<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/4.PNG" /></p>



### Oversampling SMOTE 

<p align="center">Accuracy score for the model.</p>
<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/5.PNG" /></p>

<p align="center">Confusion matrix algorithm.</p>
<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/6.PNG" /></p>

<p align="center">Imbalanced classification report.</p>
<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/7.PNG" /></p>



### Undersampling ClusterCentroids algorithm.

<p align="center">Accuracy score for the model.</p>
<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/8.PNG" /></p>

<p align="center">Confusion matrix algorithm.</p>
<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/9.PNG" /></p>

<p align="center">Imbalanced classification report.</p>
<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Credit_Risk_Analysis/blob/main/Resources/10.PNG" /></p>
