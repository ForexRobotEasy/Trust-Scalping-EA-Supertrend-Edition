# Trust Scalping EA - Supertrend Edition

This is a sample code for the Trust Scalping EA - Supertrend Edition, developed by Forex Robot Easy Team. 

## Product Description

Trust Scalping EA - Supertrend Edition is an expert advisor (EA) designed for scalping trading strategy. It uses the Supertrend indicator to identify potential trading opportunities. The EA opens buy positions when the Supertrend value is above the closing price and there is no open position. Similarly, it opens sell positions when the Supertrend value is below the closing price and there is no open position.

The input parameters for the EA include:
- `lotSize`: Trading lot size
- `stopLossMultiplier`: Stop loss multiplier for Average True Range (ATR)
- `trailingStop`: Trailing stop value
- `supertrendPeriod`: Supertrend period
- `supertrendMultiplier`: Supertrend multiplier

The EA calculates the Average True Range (ATR) using the `iATR` function and the Supertrend value using the `iCustom` function. It checks if the Supertrend value is above or below the closing price and if there is no open position. If the conditions are met, it opens a buy or sell position using the `OrderSend` function.

The EA also includes a custom function `PositionSelect` to check if there is any open position for the current symbol.

Please note that Forex Robot Easy Team is not the official developer of this product. We only provide a sample code that can work as described in the product. For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/trust-scalping-ea-review-maximize-gold-trades-on-m1/). To find the official developer of this product, please use MQL5.
