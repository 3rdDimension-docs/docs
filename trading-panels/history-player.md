# History Player

## What is History Player <a href="#what-is-history-player" id="what-is-history-player"></a>

Testing of trading strategies is one of the most important and necessary steps for successful trading. If you are an experienced algotrader, then the automatic testing method is ideal and you can use our Extension for Visual Studio. But unfortunately, many traders don't know the programming language, which makes testing their strategies difficult.

![Launch History Player](<../.gitbook/assets/223322 (1).png>)

Therefore 3rd Dimension provides the **History Player panel** for simple manual backtesting of any trading strategy.

![General view of History Player panel](<../.gitbook/assets/History player general.png>)

History Player allows you to test on any trading instruments with any vendor or broker. This is especially useful when you have access to the data feed that does not allow execution of orders (quotation date feeds like IQFeed or crypto exchange).

How to backtest a trading strategy with History Player

## First launch of the History Player <a href="#first-launch-of-the-history-player" id="first-launch-of-the-history-player"></a>

* Start the panel from the main application menu
* Add a trading instrument for testing
* Set the data type — Tick, 1 minute, 1 day
* Set the execution type — Last or Bid/Ask/Last
* Click on the "Start" button to start testing

{% hint style="warning" %}
If you click on the "**Stop"** button, all test progress will be canceled.
{% endhint %}

&#x20;When the testing is started you can open all the necessary panels for testing by clicking on the “Open panel” button.

![Open necessary panels to create a workspace for backtesting](<../.gitbook/assets/available panels in History Player.png>)

In our blog, we showed in detail the process of [manual backtesting of trading strategies using the History Player](http://thirddimension.exchange/index.php/blog/).

## General and instruments settings <a href="#general-and-instruments-settings" id="general-and-instruments-settings"></a>

Before you start testing the strategy, you need to set up an initial trading balance, a simulation (or modeling) scheme for downloaded data, a commission size for a trading instrument, and the netting type.

![Set up the initial trading balance and modeling scheme](../.gitbook/assets/Screenshot\_18.png)

Strategy testing can be performed by one of three schemes to choose from:

* **OHLC** - in this mode the sequence is constructed only by the OHLC prices of the minute bars, the number of the generated control points is significantly reduced - hence, so is the testing time.
* **Open** - in this mode, all trades are opened at the opening price of the next bar. This mode is well suited for testing strategies, which process deals only at the opening of the bar and do not use pending orders, as well as StopLoss and TakeProfit orders.
* **Close** - in this mode, all trades are opened at the closing price of the current bar.

{% hint style="info" %}
"Open" and “Close” modes have the fastest testing time, but they are not suitable for all of the trading strategies. Select the desired test mode based on the characteristics of the trading system.
{% endhint %}

Now let's look at the main settings of the selected trading instrument

![Basic settings for trading instrument - Netting type and additional fees](../.gitbook/assets/Screenshot\_20.png)

In the **Netting type** section, you can choose the method by which to summarize existing and new positions:

* **One position** - it is possible to open one position for one instrument in one direction in this mode. If you previously opened a position to buy 1 lot, adding a position to sell 1 lot will close the previous position. New trades for buy will be summed by volume, and the entry price will be averaged.

![Positions are overlapped by the netting type called "One Position"](<../.gitbook/assets/orders-matching-mode-one-position (1).gif>)

**Multiple per Side** - this mode allows you to open many different positions in one direction. For example, opening several positions in the sequence, they will be opened separately. Opposite trades (for sale) will close them.

![Positions are overlapped by the netting type called "Multiple Per Side"](<../.gitbook/assets/orders-matching-mode-multiple-per-side (1).gif>)

**Multiple Positions** - each new trade will be opened as a separate item, including the opposite trades.

![Positions are overlapped by the netting type called "Multiple Position"](<../.gitbook/assets/orders-matching-mode-multiple-positions (1).gif>)
