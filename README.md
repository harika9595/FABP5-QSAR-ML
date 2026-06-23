# FABP5-QSAR-ML
Machine learning prediction of FABP5 inhibitors using ChEMBL bioactivity data and Morgan fingerprints.
# FABP5-QSAR-ML

A QSAR machine learning project for predicting FABP5 inhibitors using ChEMBL bioactivity data.

## Objective

To build a machine learning model capable of distinguishing active and inactive FABP5 compounds using molecular fingerprints.

## Workflow

1. Retrieve bioactivity data from ChEMBL
2. Clean and preprocess IC50 measurements
3. Generate Morgan fingerprints (1024 bits)
4. Train a Random Forest classifier
5. Evaluate using ROC-AUC
6. Perform 5-fold cross-validation

## Dataset

* Target: FABP5 (Fatty Acid Binding Protein 5)
* Source: ChEMBL
* Activity type: IC50

## Tools Used

* Python
* RDKit
* Pandas
* Scikit-learn
* ChEMBL Web Resource Client

## Results

* Test ROC-AUC ≈ 0.94
* Cross-validation ROC-AUC ≈ 0.81 ± 0.16

## Future Work

* Scaffold split validation
* Applicability domain analysis
* Feature importance interpretation
* Virtual screening of natural products

## Author

Harika Reddy
