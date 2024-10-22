# Historical Symbols

If you need to import trading quotes to 3rd Dimension from a third-party data provider for performing a backtest or technical analysis, Historical Symbols will be indispensable in this case. For example, you can download any price data from Quandl, IQFeed, NASDAQ or Yahoo and test your trading idea on them.

![General view of Historical Symbols panel](<../.gitbook/assets/Historical  Symbols.png>)



Let's take a brief look at how it works.

## How to add a new historical symbol? <a href="#how-to-add-a-new-historical-symbol" id="how-to-add-a-new-historical-symbol"></a>

* First, you need to [configure parameters](historical-symbols.md#symbol-settings) of the symbol that you want to load. If you want to perform backtesting, it is important to correctly set all the parameters - asset class, tick size, etc. You can borrow parameters from an existing symbol.
* Import historical quotes from a .csv file or from an existing symbol. For example, download the trading history of Crude Oil from Quandl.

![Import trading history from file](<../.gitbook/assets/Historical symbol settings - import from file.gif>)

Press “Import History” button, select “Import from file” and specify the path to the required file.

* After you have imported the file, you need to parse it. In the settings, carefully select the Separator, Date / Time format, specify all the necessary columns (OHLC, Volume).

![Main settings for parsing a file](<../.gitbook/assets/Settings for imported file.png>)

You can modify **Date/Time** format manually according to format in the file.

* Select the aggregation (Tick, Minute, Day) and the data type (Ask, Bid, Last) at the bottom of the table.
* After the import is completed you can work with this history - performing a backtesting through History Player or make your technical analysis.

To view the chart of the imported history right from the Historical Symbols panel, right-click on the data line and open the chart.

![Open a chart to check the uploaded history](<../.gitbook/assets/historical symbol - open chart.png>)

If the chart does not load, check the selected Data type on the chart. It must match to the loaded history.

## **How to change or remove a historical symbol?** <a href="#how-to-change-or-remove-a-historical-symbol" id="how-to-change-or-remove-a-historical-symbol"></a>

To change a trading symbol settings, you need to select the desired symbol and click on the gear icon.

To delete a trading symbol, you need to select the required symbol and click on the trash bin icon. You can also delete only the imported history for the selected symbol. To do this, right-click on the imported data and select _**"Remove selected history"**_.

## Symbol settings <a href="#symbol-settings" id="symbol-settings"></a>

To correctly perform the backtesting, you need to configure parameters of the symbol that you want to load. If the requiring history refers to the existing trade symbol in 3rd Dimension, then the settings can be simply borrowed by pressing _**“Get from real symbol”**_ button.

![Symbol settings](<../.gitbook/assets/Historical symbol settings - first step.gif>)
