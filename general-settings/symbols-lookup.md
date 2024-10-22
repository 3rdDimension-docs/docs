---
description: >-
  Symbols lookup manager allowing to search and select any available symbol from
  active connections
---

# Symbols lookup

Symbols lookup manager — is a special screen, allowing to search and select any available symbol from active connections. There are various panels in 3rd Dimension terminal, that require to have a Symbol parameter being set up (Watchlist, Chart, Symbol info etc.). Depending on the requirements, symbols lookup can allow single or multiple symbols selection.

Each time you successfully connect with some integration, you will get a list of its symbols in Symbol lookup manager screen. Due to 3rd Dimension allows a multiple integrations connection, you may have several similar symbols with data, that can vary a bit. This is normal because different providers can give us different quotes data.

## Lookup field <a href="#lookup-field" id="lookup-field"></a>

Symbols lookup screen usually invoked from a lookup field. This field consists of two parts that allow you to open lookup screen:

* Symbol name (with connection name)
* “_**Lookup**_” icon in the form of three vertical points

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-LEodIDzmGvm\_1cq-Zi6%2F-LEodZeuGTDWFyNcZANa%2FlookupField.png?alt=media\&token=f70a7af3-e6e7-4117-bce8-efbcdbc4f099)

Symbol lookup field

If you click on symbol name you will see that Lookup screen will pop up and the symbols, entered by you will be applied as filtering for the Symbols list.

If you click on “_**Lookup**_” icon you will see the popped up Lookup screen without any filtering applied to symbols list.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-LZFsrT-K-\_sZf\_fFJEd%2F-LZFxHyNm8relwoGBUGZ%2FSymbol%20lookup%20screen.png?alt=media\&token=36096c34-fba5-4eef-9fec-656898c8e9e2)

Symbol Lookup screen

Anyway, you will get the Lookup screen, ready for Symbol selection. Lookup screen consists of three elements:

* Toolbar with Search field and filter
* The list of Connections and their symbols
* Footer section

If you want to close it just click outside of it.

## Searching & Filtering <a href="#searching-and-filtering" id="searching-and-filtering"></a>

Usually, each connection gives you a numerous list of trading Symbols to select from. If you know name, you can start typing it in “_**Search field**_”, and the below list will be instantly filtered to the items, containing the entered phrase.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-LEodIDzmGvm\_1cq-Zi6%2F-LEoeXccZ3xQAjKGiqsf%2FlookupFiltered.png?alt=media\&token=8291908f-f0ba-44bf-b32a-7519e333e028)

Symbol lookup filtering

By the way, you can apply more general filtering to the list; just click the “_**Filter**_” icon on the right side of the search field and you will see the second level of symbols filtering.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-LEodIDzmGvm\_1cq-Zi6%2F-LEoerdCWFiOoQB9HD-i%2FlookupFilter2.png?alt=media\&token=5889941b-7dc0-4453-90fb-ec1b00acb89e)

General filtering of trading Symbols

Here you will be able to filter the list by three parameters:

* Connection (currently active connections)
* Symbol type (FOREX, CFD’s, Options etc.)
* Exchange (Off-Exchange, NYSE, NASDAQ etc.)

Once selecting some items among filtering parameters, the list becomes filtered to the selected values only.

Be careful. While the Searchfield is become reset each Lookup screen invoke, the second level filters stay as they were set up last time. So if you can’t find the required Symbol type — please check if you have this type enabled.

## Symbols list <a href="#symbols-list" id="symbols-list"></a>

The list of symbols is a result of filtering in Lookup screen. Here you can see the nested tree of Symbols, grouped in the following order:

* Connection
* Exchange
* Type
* Subtypes

The Symbol types are marked with additional icons to help you identify the required one more quickly. The Symbol item row consists of Name and description.

To select the Symbol — click on it; to apply the symbol to the required panel, just double-click on it. This action closes the Lookup screen

## Multiple symbols select <a href="#multiple-symbols-select" id="multiple-symbols-select"></a>

In some cases, when panel can accept more than one Symbol item from lookup (like the Watchlist), you have an ability to select multiple items by holding the "_**Ctrl key**_" and clicking on the list. Once you ready to apply multiple items — press the "_**blue circle icon**_" on the right bottom corner of the list. You may also select any category level item to apply all its contents to the required panel.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-LEodIDzmGvm\_1cq-Zi6%2F-LEogAPHWtBdFZFLHnge%2FlookupMultiple.png?alt=media\&token=9067c19b-eeb8-466d-a74f-806a189bcdfc)

Multiple Symbols select

To help you deal with the big lists of Symbols, there is a footer toolbar with a set of mass actions. It allows to:

* Collapse all nodes
* Expand head nodes (top-level nodes, usually Connections)
* Expand first-level child nodes

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-LZFsrT-K-\_sZf\_fFJEd%2F-LZFzQf2-tDHmZGRj9Vr%2Fcollapsing.gif?alt=media\&token=9a9daa8b-537f-4f64-bce8-8a1edebc71f1)

Managing of multiple nodes in the Lookup Screen

The other useful information is placed on the right side of footer toolbar — items count. It may show the total amount of available Symbols (after the filtering was applied) as well as 3/235 (3 from 235) value, saying that you have selected multiple items among available.
