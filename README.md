# RL-portfolio-opt
Master Thesis - Financial data analysis by means of Reinforcement Learning techniques

# Overview
This project explores the application of Reinforcement Learning (RL) techniques to multi-stock trading and portfolio allocation problems. It extends state-of-the-art RL algorithms by incorporating financial technical analysis data and a customizable reward function that allows traders to configure their risk-aversion profile.
Key Features

- Implementation of various RL algorithms (PPO, A2C, DDPG, TD3, SAC) for financial trading
- Incorporation of technical analysis indicators in the state space
- Customizable reward function considering metrics like Sharpe ratio, stability, and Gini index
- Performance evaluation on Dow Jones stocks (2001-2021)

# Methodology
The project uses historical price and volume data of Dow Jones stocks, enriched with technical indicators such as:

- Moving averages
- Historical volumes
- Trend momentum indicators
- Volatility-related information
- Correlation matrix between stocks

The reward function is designed to incorporate metrics associated with historical returns and asset allocation, allowing for customization based on risk preferences.
Results

- Improved average results across all algorithms compared to baseline models
- Achieved annual returns of up to 41% (vs. 30% baseline) when optimizing for Sharpe ratio
- Demonstrated ability to develop more stable and resilient strategies when focusing on stability and Gini index metrics

# Future Work

- Application to other markets (e.g., cryptocurrencies) and financial instruments
- Investigation of model interpretability
- Exploration of different RL algorithms and data preprocessing techniques

