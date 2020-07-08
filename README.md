# Stacked Generalization or Ensemble Machine Learning

The following notebook is a work in progress. Level 1: 0% complete | Level 2: 80% complete

<p float="left">
  <img src="IMGs/arch.PNG" width="99%" />
</p>

This notebook aims to be a template for regression tasks by stacking three machine learning models together. Using the hyper-optimisation library: Optuna, three of the above models are chosen, scaled uniquely and tunned.  These three predictions are then tunned inside the above equation.

Models used in this notebook: 

	- Linear Regression 
	- Lasso
	- Ridge
	- Ada Boost
	- Extra Trees
	- Random Forest
	- XGBoost
	- LightGBM

Areas for possible improvement: 

	- Additional parameters to tune
	- Classification models 
