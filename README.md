# ECG-clf
This is the data and code for ECG data classification.

## Dataset
Here are thee dataset: **normal_male**,**normal_female**,and **normal_AllGender**.\
**normal_male**: only consider ```Gender == 1 ```,
**normal_female**: only consider ```Gender == 0 ```\
The three datasets are extracted from our cleaned normal dataset. Here is the dataset link. https://drive.google.com/file/d/1zHCfricVejRTScSO69uQvxpLb7yKE2Dh/view?usp=share_link\
The detail of build the three dataset can be find in **build_data.ipynb**
## Group classifiers
**demo_svm_clf.ipynb** is the demo to run the above data use different classifer. We have the following benchmarks for the **normal_male**

| Method | Train F1 | Test F1 |
| --- | --- | --- |
| SVM linear  | 0.71 | 0.55 |
| SVM RBF  | 0.80 | 0.60 |
| MLP  | 0.80 | 0.55 |
| AdaBoost | 0.80 | 0.42 |
## Gender classifers
**gender clf.ipynb** is the demo to make gender classification on different age groups. 
