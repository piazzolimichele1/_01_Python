# Json Market Data

MT5 price history in JSON, downloaded straight from MetaTrader 5 with Python.
This is the price data the Python strategies are built on.

The data is pulled for two brokers and three US indices, across the full
timeframe range. Every file is one JSON per timeframe, with its date range
written in the filename.

## Brokers
- Alpari (demo accounts)
- Alpha Capital Group / ACG (propfirm)

## Assets
- NAS100, US30, SP500

## Timeframes
M1, M2, M3, M4, M5, M6, M10, M12, M15, M20, M30, H1, H2, H3, H4, H6, H8, H12, D1, W1, MN1

## Format
One JSON per timeframe, date range in each filename.

## Full content
The full dataset is attached in the release:
https://github.com/piazzolimichele1/_01_Python/releases/tag/_MarketData_
