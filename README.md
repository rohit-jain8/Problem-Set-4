# Problem Set 4 – The Model That Fit Too Well

I simulated monthly revenue for 400 stores and built a model to predict it. The original model had an in-sample R-squared of 0.94, but it overpredicted monthly revenue for the 40 largest stores by about 7,840 dollars on average.

I compared five models and used cross-validation to choose one. The model I picked uses floor area, foot traffic, local median income, and years open, plus a term that lets revenue grow more slowly for larger stores. The nested cross-validation RMSE was about 20,870 dollars. The learning curve leveled off after about 160 training stores, so I’d look for better predictors before collecting more of the same data.

To run the project, open `Econ_3916_PS4.ipynb' in Google Colab and run the cells from top to bottom.
