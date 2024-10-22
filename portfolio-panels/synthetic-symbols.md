# Synthetic Symbols

## What is Synthetic Symbols <a href="#what-is-synthetic-symbols" id="what-is-synthetic-symbols"></a>

**Synthetic Symbols** panel allows to create any non-standard instruments (symbols) or spreads that you can both trade and use as an indicator of the current market situation or market divergences.

{% embed url="https://youtu.be/fYXb5NG8UH0" %}

Spread trading is a strategy that simultaneously creates a long and short position for different assets, in order to reduce the risk of the entire portfolio. Each side of the spread is called a "Leg", which is necessary to set the weighting factor for, i.e. the number of contracts for buy or sell. A market-neutral position, which does not depend on whether the market will go up or down is obtained with a proper selection of these coefficients.

![General view of Synthetic Symbols in 3rd Dimension platform](<../.gitbook/assets/Synthetic symbols.png>)

## How to Create a Custom Spread in 3rd Dimension? <a href="#how-to-create-a-custom-spread-in-quantower" id="how-to-create-a-custom-spread-in-quantower"></a>

For example, let's build a spread between different brokers within the same asset and see if there is a difference in prices. This is a classic example of Broker arbitrage.

* Open the Synthetic Symbols panel and click "**Create Synthetic**".
* Set the name for your spread and select a trading instrument.
* Click "**Add Leg**" to add another instrument. You can add an unlimited number of instruments by creating new "legs"
* Set the coefficients for each leg. In our example, we buy 1 lot of AUD/USD from the LMAX broker and sell 1 lot of AUD/USD from the OANDA broker.
* Click the "**Save**" button to calculate the received spread.
* Open the Chart panel and select your spread from the list of instruments.

![Spread between different brokers within the same asset — AUD/USD
](<../.gitbook/assets/synthetic chart of AUD\_USD beetwen two brokers.png>)

![Spread between WTI and Brent Crude Oil](<../.gitbook/assets/Spread between WTI and Brent crude oil.png>)
