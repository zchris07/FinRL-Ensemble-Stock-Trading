# Reinforcement Learning Stock Trading Algorithm
This is Chris Zou's implementation of FinRL's Ensemble Stock Trading notebook. FinRL is an open source framework for financial reinforcement learning. Trading environments incorporating market frictions are provided on their main repository.  

My model utilizes Markov Decision processes to train 3 deep reinforcement learning agents, A2C, PPO, and DDG, using a rolling window ensemble method. The model is built to make individual trades on multiple stocks, and is trained on stock data of the largest 30 DOW companies from 2015 to 2023. The model's environment has a stock dimension of 29 and and state space of 175, and is trained on basic indicators like MACD, RSI, CCI, and, of course, stock price. The testing period, from 2024 YTD, demonstrates a performance that out-returns the DJIA.
