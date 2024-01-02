# Module14

# Code found in machine_learning_trading_bot.ipynp
# Code to fine tune baseline trading algorithm found in machine_learning_trading_bot_optimize
# Associated reference data found in emerging_markets_ohlcv.csv


# Step 1: Tune the training algorithm by adjusting the size of the training dataset. 
# Updated time frame with an offset of 6 months -training_end = X.index.min() + DateOffset(months=6)
# Answer the following question: What impact resulted from increasing or decreasing the training window?  
# Resulted in a large difference in both LR and SVM strategy returns (signficant)

# Step 2: Tune the trading algorithm by adjusting the SMA input features. 
# Set the short window and long window
# short_window = 1
# long_window = 10

# Answer the following question: What impact resulted from increasing or decreasing either or both of the SMA windows?
# SVM model resulted in continous strategy returns, while LR model strategy returns decreased significantly over 2020-2021.


# Step 3: Choose the set of parameters that best improved the trading algorithm returns. 
# Save a PNG image of the cumulative product of the actual returns vs. the strategy returns, and document your conclusion in your `README.md` file.
