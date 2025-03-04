# Volume analysis tools

3rd Dimension trading platform provides [**Volume analysis tools**](volume-analysis-tools.md), an advanced analytical functionality, which allows you to see the traded volume at each price level, assess the balance between buyers and sellers and understand the intentions of traders regarding the future price.

{% embed url="https://youtu.be/w5nad7j1Ycc" %}

Volume analysis tools include proprietary and well-known analytics, which we’ll explore in the further articles:

* **​**[**Cluster chart**](volume-analysis-tools-or-volume-profiles-or-footprint-chart-or-vwap/cluster-chart.md) (or Footprint chart)
* ​[**Set of volume profiles**](volume-analysis-tools-or-volume-profiles-or-footprint-chart-or-vwap/volume-profiles.md) — Step, Right, Left and Custom volume profiles
* ​[**Time Statistics**](volume-analysis-tools-or-volume-profiles-or-footprint-chart-or-vwap/time-statistics.md) (known as Bar Statistics) — in table form
* ​[**Time Histogram**](volume-analysis-tools-or-volume-profiles-or-footprint-chart-or-vwap/time-histogram.md) — in form of vertical histogram
*

&#x20;The screenshot below shows how you can activate the toolbar of volume analysis tools:

![](<../../.gitbook/assets/Volume analysis tools.png>)

{% hint style="info" %}
**Green color** indicates that selected volume analysis tool has entirely downloaded the data. \
**Yellow color** indicates that selected tool is downloading the data.
{% endhint %}

### Data types of Volume Analysis Tools

All volume analysis tools have the same **Data Types**, which can be specified in the settings:

* **Trades** — it's the number of contracts (trades) that executed at each price level.
* **Buy (or Sell) trades** — it's the number of Buy (or Sell) trades that executed at each price level.
* **Volume** — the total size of all positions that executed at each price level or price range.
* **Buy (or Sell) Volume** — the total size of all Buy (or sell) positions that executed at each price level or price range.
* **Buy (or Sell) Volume, %** — shows how many percent of the total volume relates to Buy (or Sell) trades
* **Delta and Delta %** — shows the difference in traded Volume between Buyers and Sellers. It allows evaluating who controls the price on the market at a given time. Delta % = Delta / Volume \* 100
* **Cumulative Delta** — the data is built by adding the current delta value with each subsequent delta value for the certain period of time (or number of bars).
* **Average size** — the average volume of the position that was executed at a certain price or price range.
* **Average Buy size** — the average volume of a Buy position that was executed at a specific price or price range.
* **Average Sell size** — the average volume of a Sell position that was executed at a specific price or price range.
* **Max one trade volume (value and %)** — shows the maximum volume of a single trade that has executed at a certain price or price range (depending on the Custom Step (ticks) setting).
* **Filtered volume (value and %)** — this parameter displays volumes that exceed the size specified in the filter. If the volume size is smaller than the one specified in the filter, then the values will be zero.
* **Buy (or Sell) filtered volume** — the parameter displays Buy (or Sell) volumes that exceed the size specified in the filter.
