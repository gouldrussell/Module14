# Module14

# Code found in machine_learning_trading_bot.ipynp
# Code to fine tune baseline trading algorithm found in machine_learning_trading_bot_optimize
# Associated reference data found in emerging_markets_ohlcv.csv


### Step 1: Tune the training algorithm by adjusting the size of the training dataset. 
### Updated training data time frame with an offset of 6 months
### Answer the following question: What impact resulted from increasing or decreasing the training window?  Resulted in a large difference in both LR and SVM strategy returns (signficant)

### Step 2: Tune the trading algorithm by adjusting the SMA input features. 
### Set the short window (1) and long window (10)

### Answer the following question: What impact resulted from increasing or decreasing either or both of the SMA windows? SVM model resulted in continous strategy returns, while LR model strategy returns decreased significantly over 2020-2021.


### Step 3: Choose the set of parameters that best improved the trading algorithm returns. 
### SVM_Model_Pred.png was the best model (strategy returns) vs. actual returns.  
### Short window SMA of 4, long window SMA of 100 and training window of 3 months.  
