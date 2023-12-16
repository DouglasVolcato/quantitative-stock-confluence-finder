# Quantitative Stock Confluence Finder

## Overview

The Quantitative Stock Confluence Finder is a Pine Script designed to assist traders in identifying potential confluence areas within a stock's price chart. By combining various technical indicators and visualizations, this script highlights key levels and conditions that may influence trading decisions.

## Author

- **Author:** Douglas_Volcato

## Usage

1. **Intraday Analysis:** Set whether to use the day opening price as the source or provide a specific source price using the `intraday_analysis` and `source_price_input` parameters.

2. **Simple Moving Average (SMA):** Adjust the SMA parameters to fit your analysis. Parameters include length, distance from the source price, line width, and line color.

3. **Distance from Source Price Bands:** Define the distance from the source price bands, along with width, line color, line width, and background colors for bands above and below the source price.

4. **Slow Stochastic Parameters:** Configure parameters for the slow stochastic indicator, such as length, signal levels above and below, as well as arrow colors for upper and lower signals.

5. **Percentage Distance Zones:** Customize the percentage distance zones, specifying line width, line color for both above and below the source price.

6. **Daily Open, High, Low:** The script automatically retrieves daily open, high, and low prices to establish the source price.

## Installation

To use this script on TradingView:

1. Copy the entire script.
2. Open [TradingView](https://br.tradingview.com) and create a new Pine Editor script.
3. Paste the copied script into the Pine Editor.
4. Save and apply the script to your desired chart.

## Disclaimer

This script is subject to the terms of the Mozilla Public License 2.0, available at [https://mozilla.org/MPL/2.0/](https://mozilla.org/MPL/2.0/).
