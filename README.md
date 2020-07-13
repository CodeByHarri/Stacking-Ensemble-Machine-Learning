# Stacked Generalization or Ensemble Machine Learning

The following notebook is a work in progress. 

<p float="left">
  <img src="IMGs/arch.PNG" width="99%" />
</p>

This notebook aims to be a template for regression tasks by stacking three machine learning models together. Using the hyper-optimisation library: Optuna, three of the above models are chosen, scaled uniquely and tunned.  These three predictions are then tunned inside the above equation.

Models used in this notebook: 

	- Multi-layer Perceptron 
	- K-Neighbours
	- Support Vector
	- Gaussian Process   +  Radial-Basis Function  
	- Gaussian Naïve Bayes
	- Quadratic Discriminant Analysis
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
