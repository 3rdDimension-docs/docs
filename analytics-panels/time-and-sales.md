# Time & Sales

## What is Time and Sales <a href="#what-is-time-and-sales" id="what-is-time-and-sales"></a>

**Time & Sales** panel displays all trades that occur for selected instrument and provides details for each trade including date, time, price, and quantity. Each line is color-coded to indicate whether the trade was a result of an aggressive buyer or seller.

Time & Sales panel keeps a running record of trades for selected instruments displayed in chronological order. Each new entry is added to the top of the list, causing the panel screen to auto-scroll downward.

![Time & Sales panel in action - BTC/USD via Bitfinex connection](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-LMgTK3667YaMXaKhtC7%2F-LMgXK8s6OConIbMrZzH%2FTime%26Sales.gif?alt=media\&token=f81067f2-548e-4151-9005-5187a445d81b)

## General settings <a href="#general-settings" id="general-settings"></a>

The basic settings in Time & Sales are similar to the parameters of most panels in 3rd Dimension— full flexibility in color settings, fonts, columns visibility, data position relative to the column, etc.

![General settings of Time & Sales panel](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-LMgTK3667YaMXaKhtC7%2F-LMgZf1UtlK6DBIeEoKP%2FTime%26Sales%20general%20settings.png?alt=media\&token=91d9ad95-81f9-4023-b512-257f677d5657)

But some settings are unique for this panel:

* **Rows limit** — this is the number of lines that will be displayed in the table, to save the memory of your computer. When the number of lines exceeds the specified value, the old values will be deleted as new ones appear
* **Time format** — allows setting the time accuracy for executed trades.
*   **Coloring scheme** — this option sets the color scheme for all rows of the table, depending on the selected condition: If you chose **“By Aggressor Flag”**, then for the trades with the Buy direction the line will be blue, and for the Sell trades, the line will be red. If the Aggressor flag is not defined (None) then the color lime will be white.

    If you selected **“By Tick Direction”**, then the lines will be colored according to the change in the last price.

## Export Data <a href="#export-data" id="export-data"></a>

Time & Sales panel allows exporting executed trades to _CSV_ or _HTML_ files for further analysis. Soon we will add the ability to auto-update the data directly in the external file via DDE and RTD functions.

![T & S panel allows exporting data into external files](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-LMh0wM\_Hye\_-2UNcoOC%2F-LMh5cMPEfRtzcuVwp6A%2FExport%20in%20T%26S.png?alt=media\&token=703434bd-3e53-42fd-b23a-22326fc652b5)

Select the "**Export Data**" in the panel's menu

* Select the necessary data that you want to export and click on the **\[Export File]** button
* Specify the type of files and the path to save it

## Setup Actions - Filters & Actions <a href="#setup-actions-filters-and-actions" id="setup-actions-filters-and-actions"></a>

We wrote about this functionality in the [**Advanced table filters and actions**](../general-settings/table-management.md#advanced-table-filter) section, which explains in details the process of adding filters and creating different notifications. Here we briefly describe the filtering process in the table and the settings of various actions.

### Filtering in the Time & Sales table <a href="#filtering-in-the-time-and-sales-table" id="filtering-in-the-time-and-sales-table"></a>

Rows in the table can be filtered by some data value in their column. There are two ways to apply the filtering:

* **Quick filtering** can be accessed by clicking the “_**Filter**_” icon in any table column’s header.

![Quick filtering per column](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-LSZlUr\_Myk0rKIIPYb3%2F-LSZtsdnR8ZXyAorsvkj%2FQuick%20filtering.png?alt=media\&token=ccff8243-c69e-427c-8825-00c8ce9e1818)

Once you select some option — the table rows will be filtered to that ones, containing the selected value. Quick filter can be cancelled by pressing “_**Cancel filtering**_” option.

{% hint style="info" %}
Quick filtering can be applied only to one column of the table. For filtering multiple columns, we recommend to use “_**Setup actions**_”.
{% endhint %}

* **Advanced filtering,** for applying more complex filtering (multi-filtering). Select in the panel's context menu option “_**Setup actions**_”. This screen has two tabs on the left side, where the first one is an Advanced filter.

![Advanced filtering in Time\&Sales table](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-LSZlUr\_Myk0rKIIPYb3%2F-LS\_5SP-opC1CiDG-iws%2Fadvanced%20filtering.png?alt=media\&token=e2d74d74-7ee5-4533-ae11-09d4db0ab09c)

This screen allows you to Enable/Disable filtering as well as set up filtering Conditions. These conditions are set up as:

&#x20;_IF (condition1 AND condition2 ...) OR (conditionN...) …_

You can setup as many conditions as you like. Due to the possible complex logic of filtering, you are required to apply the changes once you finished the filter set up.

If you have additional questions or proposals about this functional, feel free to contact us. We are here to help you!
