# Jane-Street-Stock-Market-Prediction-Kaggle-Competition
Stock Market Prediction Kaggle Competition

Developing trading strategies to identify and take advantage of inefficiencies is challenging. Even if a strategy is profitable now, it may not be in the future, and market volatility makes it impossible to predict the profitability of any given trade with certainty. As a result, it can be hard to distinguish good luck from having made a good trading decision.

In the first three months of this challenge, you will build your own quantitative trading model to maximize returns using market data from a major global stock exchange. Next, you’ll test the predictiveness of your models against future market returns and receive feedback on the leaderboard.

# Approach:
1) First build an ANN with an encoder/decoder bottleneck arhitecture. The bottleneck arhiture is basicaly acts like a PCA, the ANN is foreced to keep only the most valuble information in the encodin layer.
2) Keep only the enocded values as explanatory variables
3) Train a XGBoost model with hyperparameter tuning (using Optuna)

# Conclusion:
The validation strategy was essential in this competition, I used an "PurgedGroupTimeSeriesSplit" approach.
