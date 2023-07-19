# Short-term-volatility-predictor

**Goal**: A model for predicting short term volatility for hundreds of stocks in different sectors.

**Solution**: The target volatility can be written as a sum of estimated volatility and an error factor. Error factor can be modelled as a product of correlation factor (β) and the change in volatility of S&P500 index. In this report we will observe the success rate of β and the short-comings of the model.

**Addressed Problem**: We sought to develop a lower sophistication but low-cost, explainable approach to modelling volatility, in the meantime also investigating the correlation of volatility between stocks and the market. Achieving this outcome can lead to faster adaptability in novel market events and provide Traders with additional signals to inform their trading and risk management.