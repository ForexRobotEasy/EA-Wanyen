# EA Wanyen - ReadMe File

This ReadMe file provides an overview of the code for EA Wanyen, a Forex software developed based on the ‘Trend Follow’ strategy. Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - EA Wanyen Review](https://forexroboteasy.com/forex-robot-review/ea-wanyen-review-trend-following-forex-software-with-auto-control/).

## Terms of Reference

1. Develop code for EA Wanyen, a Forex software that operates based on the ‘Trend Follow’ strategy.
2. Implement functionality to track and leverage the market’s trend using the Wanyen indicator.
3. Incorporate the Martingale technique to open additional orders with increased lot size when a trade plunges into the negative.
4. Include automatic control of capital feature to calculate stop loss and lot size based on the user's deposit.
5. Provide an option to halt trading on Fridays to give users increased control over their trading activities.
6. Ensure optimal performance with a minimum balance of $10 on a cent account or an equivalent standard account for 0.01 lot.
7. Focus on trading on XAUUSD, EURUSD, GBPUSD, AUDUSD, or USDJPY for the most effective results.
8. Provide only necessary trading functions in the technical specification.

## Code Description

The provided code is a sample implementation of the EA Wanyen strategy. It is designed to be executed on every tick in the market. Here is a breakdown of how the code works:

1. Retrieve the current market price using the `MarketInfo()` function.
2. Calculate the Wanyen indicator using the `iCustom()` function.
3. Check if the market is trending up by comparing the Wanyen indicator to 0.
4. If the market is trending up, place a buy order using the `OrderSend()` function with appropriate parameters.
5. If the market is trending down, place a sell order using the `OrderSend()` function with appropriate parameters.

Please note that this is a simplified code snippet and additional functionality, as mentioned in the Terms of Reference, needs to be implemented.

## Product Description

EA Wanyen is a Forex software developed based on the ‘Trend Follow’ strategy. It utilizes the Wanyen indicator to track and leverage the market's trend effectively. The software incorporates the Martingale technique to open additional orders with increased lot size when a trade goes into a negative direction.

One of the key features of EA Wanyen is its automatic control of capital. It calculates the stop loss and lot size based on the user's deposit, ensuring optimal risk management. Additionally, the software provides an option to halt trading on Fridays, giving users increased control over their trading activities.

EA Wanyen is designed to perform optimally with a minimum balance of $10 on a cent account or an equivalent standard account for 0.01 lot. It focuses on trading on popular currency pairs such as XAUUSD, EURUSD, GBPUSD, AUDUSD, or USDJPY for the most effective results.

Please note that ForexRobotEasy is not the official developer of this product. We are only showcasing a sample code that can work as described in this product. To find the official developer of EA Wanyen, please use MQL5.
