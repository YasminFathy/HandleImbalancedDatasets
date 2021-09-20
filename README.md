# Handle Imbalanced Datasets
Accompanying code for the paper: 

Y. Fathy, M. Jaber and A. Brintrup, "Learning With Imbalanced Data in Smart Manufacturing: A Comparative Analysis," in IEEE Access, vol. 9, pp. 2734-2757, 2021, doi: 10.1109/ACCESS.2020.3047838.


- **1_DataExploration.ipynb**: is to explore Scania Dataset, impute the missing values and apply dimensionality reduction

- **2_PredictiveModels_NoPCA.ipynb**: performance of classifiers (logistic regression, XGBoost, Random Forest) on original Scania data (without augmenting synthetic faulty data samples). This includes imputing the missing values and no dimensionality reduction.

- **2_PredictiveModels_PCA.ipynb (Reproduce results of Table 2 in the paper)**: performance of classifiers (logistic regression, XGBoost, Random Forest) on original Scania data (without augmenting synthetic faulty data samples). This includes imputing the missing values and dimensionality reduction on original using PCA (PCs = 11).

- **3_PredictiveModels_NoPCA-SMOTE.ipynb**: : performance of classifiers (logistic regression, XGBoost, Random Forest) with augmenting artificial faulty data samples obtained using SMOTE to original data (this includes data imputation of original data to fill missing values).

- **3_PredictiveModels_PCA-SMOTE.ipynb**: : performance of classifiers (logistic regression, XGBoost, Random Forest) with augmenting artificial faulty data samples obtained using SMOTE to original data (this includes data imputation of original data to fill missing values and dimensionality reduction on original using PCA (PCs = 11)).
- 
*Note: this repo provides some depth behind the paper and I am not quiite actively maintaining it.*
