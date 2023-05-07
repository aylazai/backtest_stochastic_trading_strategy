# Backtest Stochastic Trading Strategy

This project is a backtesting platform for the stochastic trading strategy proposed by Rayner Teo. The strategy is based on the Stochastic Oscillator, which is a popular technical analysis indicator used in trading.

## Strategy Explanation

Rayner Teo's stochastic trading strategy involves using the Stochastic Oscillator to identify overbought and oversold levels in the market. The strategy involves buying when the Stochastic Oscillator crosses below 20 and selling when it crosses above 80.

More detailed explanation of the strategy can be found in this [YouTube video](https://www.youtube.com/watch?v=viLst9ZAC6Y&t=583s&ab_channel=RaynerTeo) by Rayner Teo.

## Features

The key features of this project include:

- Backtesting: The platform allows users to backtest the stochastic trading strategy on historical market data to assess its effectiveness.

- Customizable parameters: The platform allows users to customize the parameters of the strategy, such as the buy and sell thresholds, to test different variations of the strategy.

- Market data integration: The platform is integrated with market data sources, allowing users to test the strategy on real market data.

## Usage

To use this platform, follow these steps:

1. Clone the repository to your local machine.

2. Install the required dependencies using the following command:

```
pip install -r requirements.txt
```

3. Run the platform using the following command:

```
python backtest_stochastic_trading_strategy.py
```

4. The platform will prompt you to input the parameters for the strategy and the market data to use for testing.

5. Once the backtesting is complete, the platform will display the results, including the strategy's profitability and other relevant statistics.
