# Prepare Data
- prepare_rolling_train: Extracts training data for a rolling window by selecting data within a specified time range.
- prepare_rolling_test: Extracts testing data for a rolling window by selecting data within a specified time range.
- prepare_trade_data: Prepares data for trading by selecting data for a specific date.
# Train models with  hyperparameter tuning using GridSearchCV
- train_linear_regression
- train_recursive_feature_elimination
- train_lasso
- train_ridge
- train_random_forest
- train_svm
- train_lightgbm
- train_xgb
- train_ada
  # Evaluation
- evaluate_model:Evaluates the performance of a regression model using various metrics.
- append_return_table: Appends predicted returns to a DataFrame for a specific date.
- run_4model: Runs four regression models (Random Forest, XGBoost, LightGBM, and the best-performing model) for a rolling window, making predictions and evaluating performance.
- get_model_evaluation_table: Creates a table with evaluation metrics for each model.
- save_model_result: Saves model results, including predictions and evaluation metrics, to CSV files.
  # Calculation
- calculate_sector_daily_return: Calculates daily returns for a sector based on adjusted prices.
- calculate_sector_quarterly_return:Calculates quarterly returns for a sector based on adjusted prices.
  # Selection
- pick_stocks_based_on_quantiles_old: Picks stocks based on quantiles for different percentile ranges.
- pick_stocks_based_on_quantiles: Picks stocks based on quantiles for different percentile ranges.
- calculate_portfolio_return: Calculates portfolio returns based on a long dictionary and daily returns.
- calculate_portfolio_quarterly_return:Calculates portfolio returns on a quarterly basis based on a long dictionary and quarterly returns.
- long_only_strategy_daily: Implements a long-only trading strategy on a daily basis using a top quantile threshold.
- long_only_strategy_monthly: Implements a long-only trading strategy on a monthly basis using a top quantile threshold.
# Plotting
- plot_predict_return_distribution: Plots the distribution of predicted returns for different dates in the input DataFrame.




