# Kaggle
Kaggle Competition

### House Prices
The goal is to identify the important explanatory variables out of the 76 given and use the them to make prediction of house prices

<p align="center">
  <img src="https://github.com/Henry8r8w/Kaggle/blob/main/house%20prices/figures/cor-matrix.png" width="30%" style="margin: 0 10px;" />
  <img src="https://github.com/Henry8r8w/Kaggle/blob/main/house%20prices/figures/price_distributions.png" width="45%" style="margin: 0 10px;" />
  <img src="https://github.com/Henry8r8w/Kaggle/blob/main/house%20prices/figures/prediction_visualization.png" width="45%" style="margin: 0 10px;" />
</p>



The three figures above indicate correlation matrix as the preliminary analysis, ensemble price and predicted price, and distribution differences in prediction to true values. It make sense to use XGboost variant of random forest to help with imbalance dataset and our calling in the cross-validation should help us choose model performance

Reference: *https://kaggle.com/competitions/house-prices-advanced-regression-techniques*

