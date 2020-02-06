# PrecisionFDABrainC
Brain Cancer Predictive Modeling and Biomarker Discovery Challenge

This Repository is created for PrecisionFDA Brain Cancer Predictive Modeling and Biomarker Discovery Challenge.

The submission is from the 
FDA-CBER-HIVE team at the Food and Drug Administration/Center for Biologics Evaluation and Research/ Office of Biostatistics and Epidemiology.  
The main participants are:  1) Kural Kamil, 2) Anton Golikov 3) Ilya Mazo and 4) Luis Santana-Quintero.  
Participants would like to acknowledge the help and support provided by the entire CBER-HIVE team. 

The files that end with FS, describe the Feature Selection Process.
SubChallenge files are the files which contain the Machine learning models.

In our feature selection, we used P-values computed with permutation importance : https://academic.oup.com/bioinformatics/article/26/10/1340/193348

Here is a kaggle kernel with a great implementation of the feature selection method described in the paper:
https://www.kaggle.com/ogrellier/feature-selection-with-null-importances

The models created for prediction of Survival Status use a combination of LR, LGBM, KNN, XGB RF, Voting and Stacking Classifiers.
