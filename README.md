# Costa-Rica-Household-Prediction
Supervised multi-class classification problem - Classifying households into income levels as poverty and non-poverty

The file is a set of household characteristics from a representative sample of Costa Rican Households. The dataset has observations for each member of the household but the classification is done at the household level. That is, households cannot have two different classifications. Data is not presented at the household level. So, I created my own household features from individual data.

Methodology:

•	Predicted the poverty level of household by aggregating the individual level data in a Supervised multi-class classification problem

•	Derived new features from the data, built Random Forest, KNN, SVM, XG Boost, Extra Trees, Multilayer Perceptron predictive models. Using variable importance plot, examined the most important attributes that affect the standard of living

•	Implemented Recursive Feature Elimination with cross validation in Random Forest and early stopping of Gradient Boosting to improve the computational efficiency 

Target classes represents the poverty level on a 1-4 scale

1 - extreme poverty

2 - moderate poverty 

3 - vulnerable households

4 - non vulnerable households


Information about other variables can be found at https://www.kaggle.com/c/costa-rican-household-poverty-prediction/data
