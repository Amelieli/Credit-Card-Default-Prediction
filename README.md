Background Introduction - Credit Default Prediction

Credit default prediction is central to managing risk in a consumer lending business. 
Credit default prediction allows lenders to 
- Optimize lending decisions, which leads to a better customer experience and sound business economics and, 
- Better manage cash flow.

Current models exist to help manage risk. But it's possible to create better models that can outperform those currently in use.

There are a few challenges for this dataset:
1. It is a large dataset, 5 million rows and 200 features
2. Almost all features were synthesized and masked, so it is hard to utilize feature names to make first assumptions for feature importance.

The typical thought process is:
1. EDA
2. Feature engineering
3. Build a baseline model
4. According to baseline model performance, select a different model to improve ROC-AUC.
