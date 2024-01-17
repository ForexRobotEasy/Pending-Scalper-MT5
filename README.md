# Pending Scalper MT5

**Pending Scalper MT5** is a MetaTrader 5 Expert Advisor (EA) designed to trade breakouts using pending orders. It is developed by Forex Robot Easy Team and you can find detailed reviews and trading results of this product [here](https://forexroboteasy.com/forex-robot-review/pending-scalper-mt5-review-breakout-focused-forex-software/).

## Expert Advisor Input Parameters

- `LotSize`: Initial lot size for trading.
- `StopLoss`: Stop loss in points.
- `TakeProfit`: Take profit in points.
- `MaxOrders`: Maximum number of pending orders allowed.
- `PendingDistance`: Distance from current price for placing pending orders.
- `Slippage`: Maximum allowed slippage in points.
- `MagicNumber`: Unique identifier for the EA.

## Currency Pair Settings

The EA supports trading on multiple currency pairs with different settings. The following currency pairs and their corresponding lot multipliers are defined:

- `EURUSD`: Lot multiplier - 1.0
- `GBPUSD`: Lot multiplier - 0.8
- `USDJPY`: Lot multiplier - 0.9
- `AUDUSD`: Lot multiplier - 0.7
- `USDCHF`: Lot multiplier - 0.6
- `USDCAD`: Lot multiplier - 0.5

## How it Works

The EA operates by placing pending orders based on predefined breakout levels. Here's how it works:

1. On each tick, the EA loops through each currency pair.
2. It checks if the current currency pair is enabled for trading.
3. If enabled, it calculates the lot size for the current currency pair based on the initial lot size and lot multiplier.
4. It then checks if there are already pending orders for the currency pair. If the number of pending orders is less than the maximum allowed, it proceeds to the next steps.
5. It calculates the pending order levels for buying and selling based on the current price and the pending distance.
6. It places buy stop and sell stop pending orders using the calculated levels and lot size.
7. If any error occurs while placing the pending orders, it prints an error message.

## Product Description

**Pending Scalper MT5** is a powerful breakout-focused Forex software that aims to take advantage of price volatility and breakouts in the market. It uses a unique strategy to identify potential breakout levels and places pending orders to capture profitable trades.

With its user-friendly interface and customizable input parameters, the EA provides flexibility and control to traders. Whether you are a beginner or an experienced trader, **Pending Scalper MT5** can help you automate your trading and improve your trading results.

Please note that Forex Robot Easy is not the official developer of this product. We only showcase the sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.
