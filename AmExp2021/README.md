# AmExp2021

This has my solutions for American Express datahack challenge hosted by analytics vidhya. I framed problem in two ways:
- Recommendation problem
  > I used lightfm model as it has hybrid support for both collaborative filtering and content based methods. I used lightfm for first time.
- Multi-label clasification problem
  > I used a simple 2-layered deep NN using keras api for multiclass multilabel classification. I used optuna for first time for hyperparameter search.

I didn't perform that well and I tried this all in 2 days, but learned a lot. I think the best way was to ensemble multiple classifiers or use decision trees based approaches
such as RFC, xgboost, catboost, etc. 
