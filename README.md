# Kaggle
Kaggle Competition

### 
The goal is to identify the important explanatory variables out of the 76 given and use the them to make prediction of house prices

<p align="center">
<img src="https://github.com/Henry8r8w/Kaggle/tree/main/house-prices/figures/cor-matrix.png" />
<img src="https://github.com/Henry8r8w/Kaggle/tree/main/house-prices/figures/prediction_visualization.png" />
<img src="https://github.com/Henry8r8w/Kaggle/tree/main/house-prices/figures/price_distributions.png" />
</p>


The two figures above indicate linear regression (based on ridge selected features) correlation matrix as the preliminary analysis. It make sense to use XGboost variant of random forest to help with imbalance dataset and our calling in the cross-validation should help us choose model performance
source: https://kaggle.com/competitions/house-prices-advanced-regression-techniques