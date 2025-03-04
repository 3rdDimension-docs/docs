# Power Trades

**​**[**Volume analysis tools**](volume-analysis-tools.md) allow you to understand the causes of price movement, clarify and confirm support and resistance levels, as well as assess the imbalance between buyers and sellers. But volume tools are link to a specific time (timeframe), not allowing to see an execution of large orders at the moment.

Using **Power Trades** you can see the execution of a large number of orders in a very short time, which will affect the price change with a high probability.

## What is **Power Trades** show? <a href="#what-is-power-trades-show" id="what-is-power-trades-show"></a>

First, let's take a look at a few examples.

![Power Trades tool shows huge executed trades for the short time](<../../.gitbook/assets/power trades 4.png>)

## Main settings of Power Trades <a href="#main-settings-of-power-trades" id="main-settings-of-power-trades"></a>

![Main settings of Power Trades tool](<../../.gitbook/assets/Power Trades settings.png>)



The following settings are involved in the calculation of the indicator, and directly affect the results.

* **Min Trade Volume** — the indicator calculation takes into account the executed trades, each with the size equal to or greater than the set value. For example, we can set 100 contracts, and all trades with the volume not less than the specified one will be taken into account in the calculation of the zone.
* **Max Trade Volume** — the indicator calculation takes into account the executed trades, each with the size not exceeding the set value.
* **Total Volume** — the minimum value of the volume that should be traded during the specified time interval
* **Time Interval, sec** — the time over which the Total Volume should be traded
* **Basis Volume Interval, sec** — this parameter shows how much % took the traded volume in the total volume for the specified time.
* **Zone Height, ticks** — this parameter will show only those zones where the height is less than or equal to the specified value (in ticks).
* **Level2 level count** — the number of levels that are involved in the calculation of **Imbalance** and the _Level 2 Ratio_ column in the table of results.
* **Filter by Delta,%** — the parameter will show zones that have a delta value greater than or equal to that specified in the setting. The value must be specified by module, so the table will show both positive and negative delta values. _We recommend to_ _**pay attention to the zones with the delta above/below 50%**_ (taking into account the specifics of each trading instrument).

Settings that do not affect the indicator calculation. These are mostly visual and sound settings

* **Play alert sound** — the option turns on / off the sound signal when a new zone appears.
* **Area color** — set color for all found areas on the chart
* **Highlight area color** — set color for the selected area on the chart
* **Show Market Depth** — the option shows / hides the Market Depth at the bottom of the table.
