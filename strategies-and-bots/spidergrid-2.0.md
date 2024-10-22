---
description: >-
  Spider Grid is an advanced automated strategy which includes many versions of
  Grid and DCA each optimized to a certain market condition.
---

# SpiderGrid 2.0

The Quote in a currency pair is the second symbol.

Such as:

BTC/ETH, BTC/USDT, BTC/BNB  - where USDT, ETH and BNB are the Quotes.

The first part is the base currency, which is BTC.\
\


To contact technical support:

\-Live Chat: on the website thirddimension.exchange

\-Telegram: @ThirdDimensionSupport&#x20;



### What is Spider Grid Bot and how does it work?

Market volatility is one of the unique features of the cryptocurrency market. To use this volatility to your advantage, Spider Grid Bot from any price movements no matter up or down, the important thing is just to move to the right, which is certain.

In Spider Grid 2.0 this be done considering the appropriate mode:

Bearish or. Bullish

In Bullish mode, the bot starts with a buy order first, then places a sell order above it by the amount of the chosen step.

<figure><img src="../.gitbook/assets/image (132).png" alt=""><figcaption><p>Bullish mode</p></figcaption></figure>

In Bearish mode, the bot starts with a sell order first, then places a buy order below it by the amount of the chosen step.

<figure><img src="../.gitbook/assets/image (124).png" alt=""><figcaption><p>Bearish mode</p></figcaption></figure>



Spider Grid Bot needs just to set a price range, the number of levels in that range, and the capital for each level or for the whole Grid, then you'll milk the market whether it's moving up or down in that range.

The longer the market moves in this range, the higher the profit.

<figure><img src="../.gitbook/assets/image (103).png" alt=""><figcaption></figcaption></figure>

In a bear market the price will be close to the bottom of its’ all time high, and that is the best time to use your Grid strategy because you are protected from the downside.

{% hint style="info" %}
\*Since the Spider Grid 2.0 update, the strategy includes optional SL and TP orders.
{% endhint %}

In the Bullish Mode, when the price hits TP, the bot will just stop. When the price hits SL the bot will stop and sell all sell limit orders at the SL price.

<figure><img src="../.gitbook/assets/image (104).png" alt=""><figcaption></figcaption></figure>

In the Bearish Mode, when the price hits TP, the bot will just stop. When the price hits SL the bot will stop and buy all buy limit orders at the SL price.

<figure><img src="../.gitbook/assets/image (122).png" alt=""><figcaption></figcaption></figure>

&#x20;

### What is Spider Grid Scanner and how does it work?

The Spider Grid Scanner is a complementary strategy to the Spider Grid Bot. It scans the whole trading pairs (ex. USDT pairs) on a certain exchange like Binance, Kucoin, Huobi, OKx, or FTX, to give the best 5 pairs to run the Spider Grid Bot on.

&#x20;

The outcome of the scanning will be the following information:

\-Step percentages

\-Lower Limit price

\-Upper Limit price

\-TP price

\-SL price

Then you can pick any of the 5 best pairs, enter the outcome parameters in the Spider Grid Bot, enter the capital per trade, or the total amount of capital for the whole grid, then hit run.

Spider Grid Bot will then keep buying and selling this pair at each level in the specified range until the price hits TP or SL then it will stop.



### Where to find Spider Grid:

<figure><img src="../.gitbook/assets/spider grid 1.jpg" alt=""><figcaption></figcaption></figure>

In 3rdDimension Open, Strategy Manager (STM)

Then you can choose Spider Grid Bot or Spider Grid Scanner.



### Spider Grid Scanner Settings:

<figure><img src="../.gitbook/assets/image (127).png" alt=""><figcaption></figcaption></figure>

1-License: Select your active license which should include Spider Grid.

2- Quote : the Quote currency for the pairs you want to scan.

3- Date depth: The time period that will be considered while scanning.

4- Scanner type: There are three options for the type of scanner:

high risk \ high reward

medium risk \ medium reward

low risk \ low reward

5- Preferred range size: It is the minimum price range the bot will run.

6- The minimum trading volume for the currencies to be scanned.

7- The maximum trading volume for the currencies to be scanned.

8- Name the strategy version: Name the scanner to easily manage it from the Strategy Manager.



### Spider Grid Bot Settings:

&#x20;

<figure><img src="../.gitbook/assets/image (105).png" alt=""><figcaption></figcaption></figure>

1- License: select your active license which should include Spider Grid.

2- Mode: to choose between Bullish and Bearish.

3- Symbol: the pair you want to trade on.

4- Trigger price: If you want the bot to work at a certain price level.

price range:

5- The lower limit of the Grid.

6- The upper limit of the Grid.

7- TP. Take Profit Order

8- SL. Stop Loss Order

The TP and SL orders work according to the GRID mode, depending on whether it is bullish or bearish

9- Level Mode: The number of levels in your chosen price range, Spider Grid allows you to choose one of these three types:

Fixed step: fixed numerical value between every two levels.

Fixed ratio: between each level there is a fixed (price) percentage.

Fixed number of levels: The price range is divided into a specified number of levels

10-The numerical value of the previous parameter.

Then you are free to choose - 11 the quantity you want to enter per each trade, and the bot will be calculate the capital for the entire Grid

Or 12-  the capital for the entire Grid.

{% hint style="warning" %}
(11-12) Note that when you change the mode to Bearish this amount will be calculated in the base currency.\
While it calculated in the quote currency in the bullish mode.
{% endhint %}

13- Name the strategy version: Name each bot to easily manage it from the Strategy Manager.

&#x20;

•Example:



You can run Spider Grid on any pair you want, but we chose to run the bot on the scanner recommendations in this example:

&#x20;

<figure><img src="../.gitbook/assets/image (115).png" alt=""><figcaption></figcaption></figure>

We enter our custom settings in the scanner; in this example we chose to search for USDT pairs with one day history depth, medium reward to risk ratio, and 5% preferred range.

Then when running the scanner, it will begin to show suggestions:

<figure><img src="../.gitbook/assets/spider scanner run.png" alt=""><figcaption></figcaption></figure>

&#x20;If we want to choose the best 5 of them, we stop the scanner

<figure><img src="../.gitbook/assets/spider scanner 1.png" alt=""><figcaption></figcaption></figure>

&#x20;Then enter the recommendations settings that appeared in the scanner in the bot

Choose your license, then depending on your strategy choose Bearish or Bullish mode

The currency pair is MKR-USDT and we want the bot to start immediately on the current price so, we leave the trigger price 0

The upper limit, lower limit, TP, SL and level type -fixed percentage- are filled from the Scanner recommendations.

<figure><img src="../.gitbook/assets/image (133).png" alt=""><figcaption></figcaption></figure>

&#x20;

<figure><img src="../.gitbook/assets/image (121).png" alt=""><figcaption></figcaption></figure>

&#x20;



&#x20;



### &#x20;<a href="#id-411c" id="id-411c"></a>

&#x20;

&#x20;

&#x20;

