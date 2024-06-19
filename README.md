# Project Title: Over-5-helpful-indicators-on-your-TradingView-chart (4HR & 1D Stock Charts)

## Description

This project displays two TradingView stock charts for AMEX:BTTR, one with a 4-hour interval and the other with a daily interval. The charts are embedded in an HTML page and are designed to provide a quick and efficient way to analyze the stock performance using multiple technical indicators.

## Features

- **Responsive Design**: The charts adjust for different screen sizes to ensure readability on various devices.
- **Technical Indicators**: Each chart includes the following indicators:
  - MACD
  - RSI
  - Exponential Moving Averages (EMA) with periods of 20, 50, and 250.
- **Dark Theme**: The charts use a dark theme for a modern and visually appealing look.
- **TradingView Integration**: The charts are embedded directly from TradingView, ensuring they are always up to date with the latest data.

## File Structure

- **index.html**: The main HTML file containing the embedded charts and necessary styling.

## How to Use

1. **Open the HTML File**: Open the `index.html` file in any web browser.
2. **View the Charts**: The page will display two side-by-side charts, one with a 4-hour interval and the other with a daily interval.
3. **Analyze the Data**: Use the embedded technical indicators to analyze the stock performance.

## Dependencies

- **TradingView**: The charts are embedded from TradingView, so an internet connection is required to load the charts.

## Customization

To customize the charts (e.g., change the stock symbol, intervals, or indicators):

1. **Edit the Iframe URLs**: Modify the `src` attribute of the iframes in the HTML file.
   - To change the stock symbol, update the `symbol` parameter.
   - To change the interval, update the `interval` parameter.
   - To add or modify indicators, update the `studies` parameter.

Example:

<iframe
  src="https://s.tradingview.com/widgetembed/?frameElementId=tradingview_9f1a0&symbol=YOUR_SYMBOL&interval=YOUR_INTERVAL&studies=YOUR_INDICATORS&theme=Dark&style=1&timezone=Etc%2FUTC"
  style="width: 100%; height: 93vh;"
  frameborder="0"
  allowtransparency="true"
  scrolling="no"
  allowfullscreen=""
></iframe>

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- **TradingView**: For providing the robust and versatile charting tools used in this project.

## Contact

For any questions or suggestions, please contact Me at https://wa.me/+254742125032 , or email mulu.bytes@gmail.com
