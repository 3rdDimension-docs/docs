# Watchlist

The Watchlist panel is the standard table-based panel, representing a various trading info for the specified list of symbols. The list of symbols can be customized using the symbol lookup screen, available by pressing **\[ + ]** button on the toolbar, or from table context menu — “_**Add symbols**_“ option.

![](../.gitbook/assets/watchlist.png)

Watch the required symbol info using Watchlist panel

Each symbol added to watchlist can be removed via the context menu on the symbol’s row. You can also clear all list via the context menu.

When you add a symbol, that is already presented in current list, it will be added to the end of the list thus making a duplicates.

## Favorite lists <a href="#favorite-lists" id="favorite-lists"></a>

You may want to have a possibility to save several lists for Watchlist panel. To save some list as Favorite, you can use the \[ Saved lists ] button on the toolbar. If you have no saved lists yet, it will open a “Save current list” popup, where you can set the name for the list, that you are saving.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-LHJBJoGspYTMs023Olp%2F-LHJCEyBtVsQjr0QR334%2Fwatchlist\_save.png?alt=media\&token=8aaf95cd-0714-4b37-89b7-328dba7be8ff)

Set the name for the Favorite list

Once you press the **\[ SAVE ]** button, the new list will be added to the Favorites and became available from the _**“Saved lists”**_ drop-down on the toolbar.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-LUW-CxrdQyHWtgMS1h\_%2F-LUW1DeZB7X2CnyWP3A7%2FLists%20in%20the%20Watchlist.png?alt=media\&token=4f6b6a46-709f-4c6d-aad5-50bb3eb5b0c1)

Favorite lists drop-down

Using the _**“Favorite lists”**_ drop-down, you can manage the current saved lists (edit name, remove) and initiate the current list save.

Please notice. When you click on any of favorite lists it will be added below the current list. If you want to see the selected list only, you should clear the Watchlist first.

## Indicators <a href="#indicators" id="indicators"></a>

The Watchlist panel supports the indicators value display in separate columns. In order to add some indicator, thare are two ways to to it:

* right-click on watchlist table and proceed to _**"Indicators" -> "Add indicator"**_ option. This opens an indicators lookup screen, where you should select the required one.

![](<../.gitbook/assets/indicators watchlist first way.png>)

Indicators in watchlist are very useful

* through the icon _**"Add indicator"**_ in the upper right corner of the Watchlist panel

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-LUW-CxrdQyHWtgMS1h\_%2F-LUW9frJUm69rf-o-DMD%2Findicators%20watchlist%20second%20way.png?alt=media\&token=988a92fd-48b9-4c8e-8c74-2e25bb22f4fd)

There are two ways to add indicators in the panel

When you select an indicator, you will see the new column (with the selected indicator name) added to the right side of watchlist table. To remove indicator, go to the Indicators category in the context menu and click the _**“Remove Indicator Name”**_ option.

{% hint style="info" %}
Some indicators need time to calculate their values. You will see the “Initializing...” text in such cells.
{% endhint %}

If you have created (or added) a custom indicator in the platform and want to add it to the Watchlist panel, you need to add an additional parameter to the code. More information about how to do this is given in our guide "[**Adding a custom indicator to Watchlist**](watchlist.md)".
