# Santander-Customer-Transaction
![Kaggle-picture](https://github.com/mrpintime/Santander-Customer-Transaction/assets/120576828/f7e0a43b-b291-4935-b272-0bdaa5e9b6b5)

## Short Description:  
This is a kaggle competition that there In the challenge, we want to identify which customers will make a specific transaction in the future, irrespective of the amount of money transacted.

# Flow Chart:
**We create several notebooks because we use several sampling and we want to see how it works on the other hand we do not want to increase size of notebooks so we do that.**  

1. Preprocessing Dataset.
2. Exploratory Data Analysis
3. Data preprocessing for predictive analysis
   1. Dimensionality Reduction
      1. PCA
      2. T-SNE
   2. Data sampling for imbalance dataset
      1. Downsampling Technique
         1. Create model with downsample dataset
            - Base model (for estimate difference between downsample and original dataset)
            - SVM Classifier with Kernal Trick
            - Linear SVC
            - Random Forest
            - Gradient Boosting
            - Stacking and Voting Classifier **(In future)**
         2. Conclusion
      2. Class Weight
         **In future.**

## Details  
**Metrics**: `ROC_AUC`, `F1Score`, `Recall`, `Precision`, `Visualuzation`, ...  
**Libraries**: `Scikit-Learn`, `cuML`, `lightgbm`, `Mathplotlib`, `Seaborn`, `Pandas`, `Numpy`, ...  

- Note: There are so many Notes and Tips in notebook i hope these will help you. 
