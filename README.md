# ChatGPT_Trading_Bot


## Overview

First, a disclaimer - Do NOT invest any money in any type of trading bot or algorithmic engine that you are not willing to lose. I gave this trading bot $2000 because I was willing to lose $2000 to make a great video for my AI Wizards out there. The entire codebase is contained in a single iPython notebook file, first published by the FinRL team as an example. Inside the notebook, 5 steps are performed.

1. Pull 30 days of trading data for (Insert your stock or crypto) with Yahoo Finance Downloader API
2. Create a simulated trading environment using real trading data with FinRL
3. Train an neural network to predict that Stock Price using reinforcement learning inside this simulation with FinRL
4. Once trained, backtest the predictions on the past 30 days data to compute potential returns with FinRL
5. If the expectd returns are above a certain threshold, buy, else hold. If they're below a certain threshold, sell. (using Alpaca API)

In order to have this Colab run automatically once a day, we can deploy it to a hosting platform like Vercel with a seperate file that repeatedly executes it. 

![alt text](https://i.ibb.co/4KJx9y0/Screen-Shot-2023-01-13-at-10-04-39-AM.png)

