# Price Statistic



**Price Statistic** is essentially a [**volume profile**](chart/volume-analysis-tools-or-volume-profiles-or-footprint-chart-or-vwap/volume-profiles.md) that is presented in tabular form. The panel aggregates the volume data for each price for a selected period of time. By activating the required columns, you will immediately see Trades, Volume, Delta, Average and Maximum Volumes. Filtering and notification system will show the data significant for the trader.

![General view of Price Statistic panel](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-L\_I24Yxv14WDjkEeL9J%2F-L\_I3DeKIuPEGmrBP-nl%2FPrice%20Statistic%20general%20view.png?alt=media\&token=fd3e5301-ae16-496e-9dab-88e1d4948e24)

## Price Statistic & Volume Profile. What's the difference? <a href="#price-statistic-and-volume-profile-whats-the-difference" id="price-statistic-and-volume-profile-whats-the-difference"></a>

As we have already said, the Price Statistic panel contains data in the form of a table that shows the volume profile. Below is an image showing how the panel is linked to the volumetric profile.

The main difference and advantage of the Price Statistic is that the table presents all available volume data for a particular price, which can be sorted or uploaded to an external csv file for further analysis.

![Price Statistic and Volume Profile](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-L\_NOm0eBpyrq5Cx9om2%2F-L\_NqstDgTx5MNmPDGQP%2FChart%20and%20price%20statistic.png?alt=media\&token=8d84f7aa-6695-4763-8272-879ab6f399f1)

Volume profile and data in the Price Statistic table are built for the current day. If you sort the volume column in descending order, the price in the table ($2,766) will correspond to the POC line on the volume profile.

## How to enable it? <a href="#how-to-enable-it" id="how-to-enable-it"></a>

In the main menu of the platform in the _**Analytics category**_, find the Price Statistic panel and click on it to launch it.

![Launch the Price Statistic panel](<../.gitbook/assets/3 (1).png>)

## Available Data types in Price Statistic <a href="#availalbe-data-types-in-price-statistic" id="availalbe-data-types-in-price-statistic"></a>

Each column in the table corresponds to a specific data type that you can show / hide through the panel settings or by right-clicking on the table.

![Adding columns to the Price Statistic table](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-L\_Nu19J5ilUz3Ofh\_bu%2F-L\_Nxx9HJONsoColTwZW%2Fadd%20columns%20to%20price%20statistic.gif?alt=media\&token=637e7c01-56ef-49d6-a852-a4f108b362da)

**Trades** — it's the number of contracts (trades) that executed at each price level.

* **Buy (or Sell) trades** — it's the number of Buy (or Sell) trades that executed at each price level.
* **Volume** — the total size of all positions that executed at each price level or price range.
* **Buy (or Sell) Volume** — the total size of all Buy (or sell) positions that executed at each price level or price range.
* **Buy (or Sell) Volume, %** — shows how many percent of the total volume relates to Buy (or Sell) trades
* **Delta and Delta %** — shows the difference in traded Volume between Buyers and Sellers. It allows evaluating who controls the price on the market at a given time. Delta % = Delta / Volume \* 100
* **Average size** — the average volume of the position that was executed at a certain price or price range.
* **Average Buy size** — the average volume of a Buy position that was executed at a specific price or price range.
* **Average Sell size** — the average volume of a Sell position that was executed at a specific price or price range.
* **Max one trade volume (value and %)** — shows the maximum volume of a single trade that has executed at a certain price or price range (depending on the Custom Step (ticks) setting).
* **Filtered volume (value and %)** — this parameter displays volumes that exceed the size specified in the filter. If the volume size is smaller than the one specified in the filter, then the values will be zero.
* **Buy (or Sell) filtered volume** — the parameter displays Buy (or Sell) volumes that exceed the size specified in the filter.
