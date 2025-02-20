---
description: It is the improved version of Divscanner
---

# Swing Divergence Integration

## Swing Divergence Settings:

### **Hide Chart Line:**&#x20;

When this option is checked, the Divergence is hidden from the chart

<figure><img src="../.gitbook/assets/siwing Div settings.png" alt=""><figcaption><p>Swing Divergence Settings</p></figcaption></figure>

### &#x20;**Indicator Base**&#x20;

The **IndicatorBase** setting allows traders to select one or more technical indicators to detect divergences between price action and the chosen indicator(s). Each indicator uses a unique methodology to identify potential trend reversals or continuations. Below is a breakdown of the indicators listed:

<figure><img src="../.gitbook/assets/siwing Div settings 1.png" alt=""><figcaption></figcaption></figure>

#### **1. RSI (Relative Strength Index)**

* **Purpose:** Measures overbought/oversold conditions by comparing recent price gains to losses.
* **Divergence Detection:**
  * **Bullish Divergence:** Price makes a _lower low_, but RSI forms a _higher low_ (signals upward reversal).
  * **Bearish Divergence:** Price makes a _higher high_, but RSI forms a _lower high_ (signals downward reversal).

***

#### **2. Momentum**

* **Purpose:** Tracks the rate of price change over time.
* **Divergence Detection:**
  * Momentum diverges from price direction (e.g., price rises but momentum declines), indicating weakening trend strength.

***

#### **3. MACD (Moving Average Convergence Divergence)**

* **Purpose:** Combines moving averages to identify trend direction and strength.
* **Divergence Detection:**
  * **Bullish:** Price makes a lower low, but MACD histogram forms a higher low.
  * **Bearish:** Price makes a higher high, but MACD histogram forms a lower high.

***

#### **4. Stochastic Oscillator**

* **Purpose:** Compares closing prices to a price range over a period to identify overbought/oversold levels.
* **Divergence Detection:**
  * Price trends in one direction while Stochastic trends oppositely (e.g., price rises but Stochastic falls).

***

#### **5. CD (Likely Commodity Channel Index - CCI)**

* **Purpose:** Measures price deviation from its statistical average.
* **Divergence Detection:**
  * Price and CCI move in opposite directions, signaling potential trend exhaustion.

***

#### **6. OBV (On-Balance Volume)**

* **Purpose:** Uses volume flow to predict price changes.
* **Divergence Detection:**
  * Price trends up/down, but OBV trends oppositely, signaling weak volume support for the price move.



### **Divergence Type:**&#x20;

<figure><img src="../.gitbook/assets/siwing Div settings 2.png" alt=""><figcaption></figcaption></figure>

#### **1. Reversal Divergence**

* **Purpose:** Predicts a **trend reversal**.
* **Types:**
  * **Regular Bullish Divergence:** Price makes a _lower low_, but the RSI forms a _higher low_. Suggests a potential upward reversal.
  * **Regular Bearish Divergence:** Price makes a _higher high_, but the RSI forms a _lower high_. Suggests a potential downward reversal.
* **Example:** If the price hits a new low while the RSI fails to confirm it, traders may anticipate a bullish reversal.

***

#### **2. Continuation Divergence (Hidden Divergence)**

* **Purpose:** Signals that the **current trend will continue** after a retracement.
* **Types:**
  * **Hidden Bullish Divergence:** Price forms a _higher low_, but the RSI forms a _lower low_. Indicates strength in an uptrend.
  * **Hidden Bearish Divergence:** Price forms a _lower high_, but the RSI forms a _higher high_. Indicates weakness in a downtrend.
* **Example:** During an uptrend, if the price pulls back slightly but the RSI shows stronger momentum, the trend is likely to resume upward.

### **Divergence Accuracy:**&#x20;

<figure><img src="../.gitbook/assets/siwing Div settings 4.png" alt=""><figcaption></figcaption></figure>

* **Confirmed:** Triggers alerts for **validated divergences** (e.g., when price action confirms the RSI signal).
* **Potential:** Flags **early-stage divergences** that may form but are not yet confirmed.
* **Premature:** Marks signals that are **too early** to act on, requiring further validation.
* **VISW:** Likely an abbreviation for a specific divergence subtype (context-dependent, e.g., "Visible Swing").
* **Combined States:**
  * **ConfirmedWithPotential:** Alerts when a confirmed divergence coexists with a potential signal.
  * **PotentialWithPremature:** Highlights when a potential divergence appears alongside premature signals.

### Swing Divergence in Divscanner:&#x20;

<figure><img src="../.gitbook/assets/image (156).png" alt="" width="375"><figcaption></figcaption></figure>

Open Strategy manager and then select [DivScanner](divscanner.md)&#x20;

<figure><img src="../.gitbook/assets/image (157).png" alt=""><figcaption></figcaption></figure>

## Enter By Divergence:

New enter option in TPA “Enter” settings. It can be used alongside the standard enter pattern or by itself.&#x20;

This option is available for both spot and futures trading and is only supported when using the “Buy Support” strategy.&#x20;

When selecting this enter option, the TPA will use the "Swing Divergence" indicator as a signal provider to either enter the trade directly or adjust the enter price to a better position. A divergence signal is considered valid if the divergence accuracy is "Potential" and if it satisfies the conditions specified by the user in the "Enter By Divergence" Settings.



<figure><img src="../.gitbook/assets/Enter By Divergence.png" alt=""><figcaption></figcaption></figure>

&#x20;

## Settings:

* Divergence Period: the time frame for the "Swing Divergence" indicator, it's recommended that this timeframe is equal to the TPA time frame or lower
* Divergence Enter Price (%): a percentage of the TP distance, the value of this field specifies a range around the enter price where a Divergence signal should be accepted as an enter signal. The lower and upper bands of the range are calculated based on the overall enter settings (standard and divergence enter settings)
* Divergence Type: the type of divergence that qualifies as an enter signal, could be either Reversal(regular) or Continuation(hidden).
* RSIMode: the desired mode for the RSI indicator that will be used by the "Swing Divergence" indicator. could be either "Simple" or "Exponential"

Allow more control over the TPA enter mechanism, the user can select either "Standard Enter" or "Enter By Divergence" or both, this behavior is supported for both spot and futures. and based on the chosen enter options the behavior of the TPA enter process will be different.

## TPA enter behavior based on the selected enter patterns:

1. Only the "Standard" enter option is selected: the usual enter pattern
2. Both "Standard" and "Enter By Divergence" are selected:&#x20;

* if an accepted divergence is conformed within the specified divergence range, the TPA will shift the enter price to a new price, the new price is in the middle between the divergence destination point and the current market price. then the TPA "Standard" enter mechanism will handle the entry as usual. notice that all "enter price" related settings such as "enter trigger price", "exit trigger price", and "exit price" will be shifted by the same distance.
*   the accepted range is specified by the "Enter By Divergence" percentage, the lower band of the range (upper band for short mode) is equal to the enter price, and the upper band(lower for short mode) is calculated based on the percentage.

    for instance, if the TPA mode is long and the percentage is 20%, the lower band of the accepted range equals the enter price and the upper band is above the enter price by 20% of the TP distance
* if no accepted divergence was conformed within the specified range, the TPA will handle entry as defined in the "Standard Enter" settings.

3. Only "Enter By divergence" is selected:

* the TPA will enter the trade directly with a market order, only if an accepted divergence is conformed within the specified divergence range.
* "Standard enter" behaviors such as "Limit" and "local limit" options are not available.
* The "Exit" option is not available.
* The "Enter By Divergence" percentage and the selected "SL" behavior specify the accepted divergence range.
* The upper range band (lower band for short mode) is calculated based on the percentage, and the lower band(upper for short mode) is calculated based on the selected "SL" behavior:
  * if the "SL" behavior is enabled, the lower band(upper for short mode) is equal to the "SL" price.
  * if the "SL" behavior is not enabled (the "Without SL" general option is selected), the lower band is calculated based on the percentage.
  * if the "SL" behavior is not enabled (the "Without SL" general option is selected), the lower band is calculated based on the percentage. For instance, if the mode is long, the percentage is 20%, and "SL" is disabled, the range upper band is above the enter price by 20%, and the lower band is below the enter price by 20%.
  * if no accepted divergence was conformed within the range, and a bar is closed below the lower band (for the timeframe specified in the "Divergence Period"), the TPA will be considered out of boundary and it will be stopped.

## TP By Divergence:

New “TP” option in TPA “TP” settings. It can be used alongside the standard TP pattern or by itself. This option is available for both spot and futures trading and is supported when using “Buy Support” or “TPnSL” strategies.

When selecting this enter option, the TPA will use the "Swing Divergence" indicator as a signal provider to close the trade.

A divergence signal is considered valid if the divergence accuracy is "Potential", the divergence type is “Reversal“ and if it satisfies the conditions specified by the user in the "TP By Divergence" Settings.

<figure><img src="../.gitbook/assets/image (158).png" alt=""><figcaption></figcaption></figure>

### Settings:

* Divergence Period: the time frame for the "Swing Divergence" indicator, it's recommended that this timeframe is equal to the TPA time frame or lower.
* Divergence Enter Price (%): a percentage of the TP distance, the value of this field specifies a range between the enter price and the TP price where a Divergence signal should be accepted as an TP signal. the upper band (lower for Short mode) equals TP price and the lower band (upper for short mode) is calculated based on the percentage value
* Divergence Type: the type of divergence that qualifies as an enter signal, could be either Reversal(regular) or Continuation(hidden).
* RSIMode: the desired mode for the RSI indicator that will be used by the "Swing Divergence" indicator. could be either "Simple" or "Exponential"

### TPA TP By Divergence behavior:

If the “TP By Divergence” option is selected, the TPA will close the trade if an accepted divergence signal is received within the TP divergence range, the range upper band (lower for short mode) equals TP price and the lower band (upper for short mode) is calculated based on the “TP By Divergence” percentage value.

For instance, if the TPA mode is long, and the percentage is 20%, the range upper band equals TP price and the range lower band is 20% (from TP distance) below TP price.

If no accepted divergence conforms with the range, the TPA will behave as specified in the standard TP settings.
