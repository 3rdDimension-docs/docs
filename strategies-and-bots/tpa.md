---
description: >-
  (Trade Personal Assistant) It’s a bot that can help you manage your trades in
  advance, automate your entry and exit, to have the ability to apply complex
  trading scenarios.
---

# TPA

### Every trader needs to take 3 decisions in each trade:

1- when to **enter** (the price of entering the trade).

2- when to **exit** (an exit price).

3- The **quantity** (capital percentage).

Those three decisions have to be taken regardless of the applied strategy, here TPA comes in handy. TPA allows you to configure entry and exit conditions in advance.

You can choose to enter the trade in so many different situations, whether it’s resistance breakout, buy support, to enter when the price hit a certain value, to enter when a bar or candle close, or to enter when you break resistance and retest it, and to choose a type of your order whether it’s a limit or market or local limit.

The same concept or conditions are applied in the exit behavior whether it’s “take a profit TP or stop loss SL or exit when entry condition fail (false breakout)”&#x20;

What is even more unique about TPA is that you can apply all these scenarios by drawing on the chart.

It literally can take 3 seconds to apply a complex trading strategy and run it. From that point forward, TPA will handle the execution of your conditions and strategy automatically without even sleeping. In addition, the TPA manager lists all TPA strategies across charts, so it becomes easy and convenient to see and manage all your trades and even change any value or condition live.

Another unique benefit of TPA is the ability to keep your capital free and not reserved in a limit order while you are waiting for the price to activate the order. And that’s by using the local-limit order type where it saves the condition inside the strategy and not sending it to the exchange, therefore you have free capital (margin) to run multiple TPA trades on multiple charts (opportunities) at the same time the TPA will activate the trades that respect your conditions first so you save time by not waiting your orders to be filled and you take advantage of liquid and fast base pairs.

## **How To Run TPA?**

To run TPA you have 2 options:

<figure><img src="../.gitbook/assets/1Open Tpa 3Rddimension GIF-downsized.gif" alt=""><figcaption></figcaption></figure>

**First:**    by opening a chart then choosing TPA from drawing tools at the left side and the just click anywhere in the chart then TPA will appear with its default values.

**Second:**   open the TPA manager from the main menu and click **+** and choose a pair that you want to trade on. Next, click settings and fill all the conditions according to your scenario.&#x20;



<figure><img src="../.gitbook/assets/2Open Tpa Manager GIF-downsized_large.gif" alt=""><figcaption></figcaption></figure>

## TPA Settings

<figure><img src="../.gitbook/assets/TPA New 1.jpg" alt=""><figcaption></figcaption></figure>

## <mark style="background-color:blue;">1-</mark> General:

<figure><img src="../.gitbook/assets/TPA settings general 1strategy.png" alt=""><figcaption><p>TPA General Settings</p></figcaption></figure>

1.1. **Strategy**, you choose the general behavior of the trade:\
\
1.1.1 **Default Settings**: In this option, you will find a dropdown list containing five different settings. Use the Apply button to apply your chosen setting.

**Settings 0**: This is the default setting, meeting the same conditions as when you draw the TPA on the chart.\
\
**Settings 1-4**: These are optional settings that provide more flexibility and a faster way to set your TPA parameters. Once you've configured your options, you can save the TPA to one of these settings, allowing you to quickly apply any of them as you prefer for your trade or any other upcoming TPA.

1.1.2 **Strategy**: In this Method, you will find a dropdown list containing Three options: (BuySupport/SellResistanse, ResistanceBreakout/ResistanceBreakDown,TPnSL).\
\
In the context of Mode 1.1.3, where the trading direction is Long, the 'Strategy' function provides the option to select 'ResistanceBreakout.' This strategy is suitable when aiming to trade the breakout of a specific resistance level or price. It's important to note that for this strategy to be triggered, the current market price should be below the entry price. Conversely, when the trading mode is set to Short in Mode 1.1.3, the corresponding option is 'SupportBreakDown.' This strategy is applicable when looking to capitalize on the breakdown of a particular support level. To initiate this strategy, the current market price should be above the entry price.

In the context of Mode 1.1.3, where the trading direction is Long, the 'Strategy' function offers the option 'BuySupport.' This strategy is employed when entering a trade as the price descends to a specific level. It's important to note that for this strategy to activate, the current market price should be above the entry price. Conversely, when the trading mode is set to Short in Mode 1.1.3, the corresponding option is 'SellResistance.' This strategy enables the selling of assets when the price reaches a predetermined resistance level. To execute this strategy, the current market price should be below the entry price.

Choose the 'TPnSL' option in the 'Strategy' function if you intend to utilize TPA solely for Take Profit (TP) and Stop Loss (SL) purposes. With this strategy, you will need to manually specify the quantity percentage(1.3.3) you want to sell. 'TPnSL' allows you to set predefined levels for taking profits and limiting losses, providing you with greater control over your trading strategy.

1.1.3 **Mode**: In this dropdown list, you will find two options:(Long, Short). **LONG**: Select this option to open a long trade, indicating your intention to buy and profit from an expected increase in the asset's value.

**SHORT**: Choose 'SHORT' to open a short trade, signaling your intent to sell and potentially profit from a decline in the asset's value. Short trades allow you to benefit from falling prices in the market.

1.1.4 **Without Exit Behavior** : enabling this option will hide the Exit window (3) in the TPA's menu, indicating that no conditions are set for exiting trades.\
\
1.1.5 **Without SL Behavio**r : enabling this option will hides the SL window (5) in the TPA's menu, meaning the TPA won't apply any Stop Loss conditions.

1.1.6 **Repetition behaviour** : this option is enable just for ResistanceBreakout/ResistanseBreackDown strategy.\
&#x20;**One time**: strategy will stop after it executes enter and exit behaviour. **Continuous**: strategy will run enter behaviour each time if exit behaviour occurs.

{% hint style="info" %}
continuous behaviour applies only after exit behaviour and not after TP and SL behaviour.
{% endhint %}

## 1.2 Time frame:&#x20;

<figure><img src="../.gitbook/assets/tpa time frame.png" alt=""><figcaption><p>Time Frame</p></figcaption></figure>

Choose the time frame of the chart you want to trade on. The same time frame will be applied to the candlesticks in the condition behavior.

{% hint style="info" %}
The time parameters are disabled and set according to the time frame on which you draw the TPA. However, if you add the TPA from the TPA Manager (+), the time frame parameters will be enabled.
{% endhint %}

## 1.3 Order Parameters :&#x20;

<figure><img src="../.gitbook/assets/tpa order parameter.png" alt=""><figcaption><p>TPA order parameters </p></figcaption></figure>

1.3.1 **Account**: Here, you can find all your availabe connections. Or it will be already sellected if you drow the TPA on the chart.&#x20;

1.3.2 **Symbol**: Here, you can select your trading pair. Or it will be already sellected if you drow the TPA on the chart.&#x20;

1.3.3 **Quote Percentage**: This represents the percentage of your quote quantity that you want to use to enter the trade (BTC/USDT = Base/Quote).

1.3.4 **Calculate Quantity at Run Time:** enabling this parameter means that the TPA will dynamically adjust the quantity trade size based on the percentage specified and the quote in the portfolio at placing order time rather than using a fixed amount on run . This flexibility will optimize the trade for improved risk management and potential returns.

&#x20;1.3.5 **Save Fees:** **Save Fees:** The purpose of this function is to refund the fees deducted from your balance by replacing the order below the entry price in the market. This functionality is enhanced and made more flexible with the following options, allowing you to define the exact percentage equivalent to your exchange. Furthermore, you have the choice to specify from which side (Enter Price, Exit Price, or Both) of the trading you would like the percentage to be reclaimed.

1.3.6 **Save Fees Behavior Function:** This function allows you to specify at which stage you would like to reclaim the fees. If you choose **'At Open,'** the order will be placed below the entry price within the specified percentage range in the 'Save Fees %' (1.1.7). Alternatively, if you select **'At Close,'** the percentage range will be applied for the Exit order, adding this percentage to the Exit Price. For the **'From Both'** option, the entered percentage will be divided into two. This means that half of the fees will be deducted below the entry price ('At Open'), and the second half will be deducted at the exit price ('At Close').

1.3.7 **Save Fees(%):** This parameter allows you to specify a preferred exact numerical value range to be automatically applied, thereby modifying the Entry Price, Exit Price, or both.

1.3.8 Updated features of Save Fees parameter allow to put a prefered exact numerical value range with a percentage equivalent to exchange Fees.

1.3.9 **QuantityOption:** This option is enabled if you have set a Stop Loss (1.5 disable) for your trade. It contains a dropdown list of two options.

\- **Manual:** If you want to set the Base or the Quote quantity manually.

**- Risk Per Trade:** Choosing this option hides the Quote Percentage (1.3.3) and disables the Base Quantity and Quote Quantity because this option automatically sets the quantity for the trade according to your Stop Loss setting by the formula quantity = balance \* RiskPerTrade / SL

1.3.10 **Base – Quantity (applied):** is operated by automatically calculating the quantity based on either the 'Quote-Quantity' (1.3.8) or the 'Quote Percentage' (1.3.3) field at the current price of the pair. Alternatively, the Base-Quantity can be manually set by users. In this case, the corresponding 'Quote-Quantity' and 'Quote-Percentage' are automatically computed at the enter price specified, ensuring that accurate quantities and percentages are reflected in real-time.&#x20;

1.3.11 **Quote – Quantity:** is operated by automatically calculating the quantity based on either the 'Base-Quantity(applied)(1.3.7) or the 'Quote Percentage' (1.3.3) field at the current price of the pair. Alternatively, the Quote-quantity can be manually set by the user. In this case, the corresponding 'Base-Quantity(applied)' and 'Quote-Percentage' are automativally computed at the enter price specified, ensuring that accurate quantities and percentages are reflected in real-time.&#x20;

1.3.12 **Max Available:** Enabling this option will display your available quote amount.

## 1.4 Notes:&#x20;

<figure><img src="../.gitbook/assets/TPA Note.png" alt=""><figcaption><p>TPA Notes</p></figcaption></figure>

In this area, you can write any note you would like. For example, the Time Frame strategy applied to this trade.

## <mark style="background-color:yellow;">2.</mark> Enter

<figure><img src="../.gitbook/assets/enter N1.jpg" alt=""><figcaption></figcaption></figure>

## 2.1 Basic

2.1.1 **Enter Event**: This option allows you to specify the type of entry behavior event.

**On Price Hit:** Choose this option to execute a Buy (or Sell, depending on the trading mode) trade when the market price hits the specified Buy Price.

**On Bar Close:** Opt for this setting to execute a Buy (or Sell) trade when a Bar/Candlestick closes above the Trigger Price. This entry triggers based on the closing price of a complete bar.

**On Bar Retest:** Select this option to execute a Buy (or Sell) trade when a Bar/Candlestick closes above the Trigger Price and subsequently retraces or retests back to the Buy Price. This entry type allows for confirmation through a retest scenario.

**2.1.2 Enter order type:**

**Limit:** Choose this option to execute a limit buy order (or sell order, depending on the trading mode) when the specified condition is met.

**Market:** Opt for this setting to execute a market buy order (or sell order, depending on the trading mode) immediately when the specified condition is met.

**Local Limit:** This option is exclusively available for Buy/Sell Support. It executes a local limit buy order (or sell order, depending on the trading mode) when the condition is met. TPA will place a buy limit order when the price falls below the LocalLimit trigger price (2.1.5) and will automatically cancel this buy limit order when the price rises above the LocalLimit trigger price. The reverse applies in Sell order mode.

**2.1.3 Trigger Price (%):** a percentage that will be added to the Buy/Sell price allowing the TPA to place limit order when the current price hits it.

**2.1.4 Trigger Price:** it’s a specific price that’s calculated from the Trigger Price (%) or add manually to allow the TPA to place limit order when the current price hits it.

**2.1.5 LocalLimit Trigger Price (%):** it's percentage from the distance between enter and the take profit (TP) prices that will activate/deactivate the enter order. It will automatically calculate the LocalLimit Trigger Price (2.1.6) to add the price. revercal, if the LocalLimit Trigger Price added manually the percentage will be calculated and add here.

**2.1.6 LocalLimit Trigger Price:** It's the specific price at which the enter order will be activated or deactivated. This price can be added manually, and the percentage in 'LocalLimit Trigger Price (%)' will be adjusted. Alternatively, it is calculated automatically from the 'LocalLimit Trigger Price (%)'.

**2.1.7 Enter Price:** It's the exact price that the trade will execute a buy order on. Notes:

* When Enter Event is set to OnBarClose then the trade will execute the buy order at the close price of the candle that closed above Buy Price.
* If the save fees (1.3.5) enabled it will place the order under the exact enter price with a percentage equivalent to exchange Fees.

## 2.2 Whale Splash Enter:

&#x20;in general Whale Splash follows significant market players ("whales"), aligning trades with their impactful one-second volume moves. The definition of "large volume" adjusts dynamically, accommodating different trading pairs and adapting to evolving market conditions.

**2.2.1 Whale Splash Enter Enabled:** Enabling 'Whale Splash Enter' allows the TPA to enter a trade when it identifies a WhaleSplash signal, based on the parameters you've entered, including 'Whale Splash Trigger Enter Price (%)' and 'Whale Splash Type

**2.2.2 Whale Splash Trigger Enter Price (%):** Here, you can set the percentage difference between the Enter Price and the TP Price to enable the TPA to take action and enter if the Whale Splash signal appeared. For example, if you enter 1 in this field, it means that if any signal appears within 1% of the distance (TP - enter price) above the Enter Price, the TPA will enter the trade at the same price as when the Whale Splash appered in this range.

**2.2.3 Whale Splash Type:** There are two types, Aggressive and Conservative. The difference depends on the base value of the whale type.

&#x20;For more information about Whale Splash, click [here](https://doc.thirddimension.exchange/strategies-and-bots/whale-splash).

## <mark style="background-color:orange;">3.</mark> Exit

<figure><img src="../.gitbook/assets/exit N1.jpg" alt=""><figcaption></figcaption></figure>

## 3.1 Basic

**3.1.1 Exit Order Type:**

**Limit:** execute limit sell/Buy order, when the condition is met.

**Market:** execute market sell order, when the condition is met.

**3.1.2 Exit trigger Price(%):** it's percentage from the distance below (or above, depending on the direction) your enter price, that will trigger the exit price. It will automatically calculate the Exit Trigger Price (3.1.3) and adding the accurate price to it. revercal, if the Exit Trigger Price added manually the percentage will be calculated and add here. For example, if you enter a trade at a certain price and set the "Exit Trigger Price(%)" to 5%, it means that when the current market price reaches 5% below (or above, depending on the direction) your entry price, an automatic exit action will be triggered.

**3.1.3 Exit Trigger Price:** is a predetermined price level that, when reached, automatically triggers the exit of a trade. It's used to enforce the strategy for limiting losses or profit-taking. In other words, if the price reaches the trigger price, a sell order (or a buy order, depending on the position you are in) will be automatically executed for the entered trade.

**3.1.4 Exit Price (%):** A percentage that will be subtracted from the Enter Price, and will set the Exit Price value.

**3.1.5 5.Exit Price:** It’s a specific price that’s calculated from the Exit Price (%), it’s the exact price that the trade will execute a sell order on.

### 3.2 Whale Splash Exit

**3.2.1 Whale Splash Exit Enabled:** To enable the Whale Splash for the Exit.

**3.2.2 Whale Splash Type:** There are two types, Aggressive and Conservative. The difference depends on the base value of the whale type. For more information about Whale Splash, [Click Here](https://doc.thirddimension.exchange/strategies-and-bots/whale-splash)

## <mark style="background-color:green;">4.</mark> TP&#x20;

<figure><img src="../.gitbook/assets/TP N1.jpg" alt=""><figcaption></figcaption></figure>

## 4.1 Basic

**4.1.1 TP order type:**

**Limit:** execute limit sell order, when the condition is met.

**Market:** execute market sell order, when the condition is met.

**4.1.2 TP event:** choose the type of the take profit behavior event.

**OnPriceHit:** execute Sell trade when the price hits TP Price.

**OnBarClose:** execute Sell trade when a Bar/Candlestick closes above TP price. 4.1.3 TP Price (%): a percentage that will be added to the Buy Price, and set in the TP Price.

**4.1.4 TP Price:** it’s a specific price that’s calculated from the Buy Price (%), it’s the exact price that the trade will execute a sell order on. (note: when TP Event is set to OnBarClose then the trade will close at the exact close price of the candle that closed above TP price).

## 4.2 Trailing TP:

**4.2.1 Trailing TP Type:** it defines the type for the trailing and has two options: Percentage trailing: it folows the price with a specified percentage - when the price goes down with the specified percentage after hitting the TP, it will close the trade.

Swing trailing: after the Take profit (TP) is hit it folows the price waves - when the price breaks the previous low in the trend swings it closes the trade (swing size and close event have there fields for the user to select).

## 4.3 Whale Splash TP:

**4.3.1 Whale Splash TP Enabled:** To enable the Whale Splash for the Exit.

**4.3.2 Whale Splash Trigger TP Price(%):** Here, you can set the percentage difference between the Enter Price and the TP Price to enable the TPA to take action. For example, if your TP is 10% and you enter 80% here, it means that if any signal appears above the Enter Price in 80% of the range between the Enter Price and the TP, the TPA will take the profit and exit the trade at the same price as when the Whale Splash appeared in this range (the last 20% of the TP).

**4.3.3 Whale Splash Type:** There are two types, Aggressive and Conservative. The difference depends on the base value of the whale type.

## <mark style="background-color:red;">5.</mark> SL&#x20;

<figure><img src="../.gitbook/assets/Sl N1.jpg" alt=""><figcaption></figcaption></figure>

## 5.1 Basic

**5.1.1 1. SL order type:**

**Limit:** execute limit sell order, when the condition is met.

**Market:** execute market sell order, when the condition is met.

**5.1.2 2. SL event:** choose the type of the stop loss behavior event.&#x20;

**OnPriceHit:** execute Sell trade when the price hits SL Price.

**OnBarClose:** execute Sell trade when a Bar/Candlestick closes below SL Price.

**5.1.3 3. SL Price (%):** a percentage that will be subtracted from the Buy Price, and set in the SL Price.

**5.1.4 4. SL Price:** it’s a specific price that’s calculated from the SL Price (%), it’s the exact price that the trade will execute a sell order on. (note: when SL Event is set to OnBarClose then the trade will close at the exact close price of the candle that closed below SL price).

**5.1.5 Trailing SL (%):** It replaces the sl percentage and it folows the price changes as it increases, for example if the value is 1%, the sl is always 1% under the highest price the symbol got to after entering.

## <mark style="background-color:purple;">6.</mark> Logs:



<figure><img src="../.gitbook/assets/13Logs GIF-downsized_large.gif" alt=""><figcaption></figcaption></figure>

Logs prints all necessary information about strategy behavior and orders executions, and it appears in two places: on the TPA in the chart and in the TPA Manager.

{% hint style="info" %}
After you finish setting up all your choices and parameters, you need to press the 'APPLY' button to apply your settings to the TPA before running it.
{% endhint %}

## **TPA manager:**



<figure><img src="../.gitbook/assets/15Runall GIF-downsized_large (1).gif" alt=""><figcaption></figcaption></figure>

### **TPA manager is the panel where you can manage all your TPA trades.**

_Every TPA that has been drawn on any chart will appear in the TPA manager, you can also add new TPA._

_Run all will run all TPAs that are listed in TPA manager._

_Stop all will stop all TPAs that are listed in TPA manager._



<figure><img src="../.gitbook/assets/14Save As GIF-downsized_large.gif" alt=""><figcaption></figcaption></figure>

### How to save TPA default values:

From the TPA manager right click on the TPA trade you want to save its values as default and then click set as default.

When you save default values or a certain TPA will save all the settings and the percentages.

<figure><img src="../.gitbook/assets/16Filter GIF-downsized_large.gif" alt=""><figcaption></figcaption></figure>

Pick which field or setting you want to show in the main bar

Open or close the settings section.



<figure><img src="../.gitbook/assets/17Select GIF-downsized_large.gif" alt=""><figcaption></figcaption></figure>
