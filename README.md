# Heikin Ashi Dashboard ReadMe

This ReadMe file provides a brief description of the code for the Heikin Ashi Dashboard indicator. Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code that can work as described in the product. To find the official developer of this product, please refer to MQL5.

## Code Description

The Heikin Ashi Dashboard is a custom indicator for MetaTrader 5 (MT5) that displays the direction, strength, and number of bars of the ongoing trend in the market. It also implements color-coding to identify consolidation/reversal candles (dojis).

The code consists of several functions:

1. `OnInit()` - This function is called during the indicator initialization. It sets up the indicator buffers, styles, and labels.

2. `OnCalculate()` - This function is called for each new tick or bar. It updates the scanner panel if the indicator needs to be updated.

3. `CreateScannerPanel()` - This function is responsible for creating the visual panel that displays the trend information.

4. `UpdateScannerPanel()` - This function updates the scanner panel in real-time, reflecting any changes in the market.

5. `OnDeinit()` - This function is called when the indicator is removed from the chart. It can be used for any necessary cleanup logic.

6. `ObjectGetDescription()`, `ObjectGetValueByTime()`, `ObjectGetDouble()`, `ObjectGetInteger()`, and `ObjectGetString()` - These functions are custom indicator properties functions and are not used in the current code.

## Input Parameters

The code allows customization through input parameters. The available input parameters are:

- `Currencies` (string) - A comma-separated list of currencies to monitor. The default value is 'EURUSD, GBPUSD, USDJPY'.

- `Periods` (ENUM_TIMEFRAMES) - The period to use for the indicator. The default period is PERIOD_M15.

## Product Description

The Heikin Ashi Dashboard is a powerful indicator that provides traders with valuable insights into the market trends. With its visual panel, it allows traders to quickly identify the direction, strength, and number of bars of the ongoing trend in multiple currency pairs.

In addition, the indicator implements color-coding to highlight consolidation/reversal candles (dojis), helping traders make informed decisions.

Please note that this code is a sample implementation and not the official product. For detailed reviews and trading results of the official Heikin Ashi Dashboard, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/heikin-ashi-dashboard-unbiased-review-of-multi-currency-forex-software/).

For the official developer of this product, please refer to MQL5.
