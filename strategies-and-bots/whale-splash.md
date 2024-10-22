# Whale Splash

The main idea of WhaleSplash is to “move with whales”, this means that whenever a whale moves (places order), you move with him and place an order. A whale move is defined as a trade or several trades within one second that its volume is large enough, that may affect the market situation, or in other words, it’s a volume within a second that exceeds a threshold.\
The tricky part here is to define the “large volume”, for example, a large volume for BTC/USDT is different from a large volume for ETH/BTC, also a large volume today may be different from a large volume last month for the same symbol.\
\
WhaleSplash solves this by calculating statistics for the selected symbol and the direct last historical data so we get a volume suitable to the time we are using the tool (indicator or strategy).\
\
WhaleSplash tool is used for detecting whales’ moves and do some action about it, the indicator draws a whale on the positions of the signals (price and time), where the signal is a whale move, and it gives you an alert if you checked the option “Send Alert”, and the strategy places an order whenever a whale signal occurred with the parameters you choose in the settings, and tells you in logs (as well as alerts if you choose to be sent alerts).\
\
The threshold here (to detect the whale volume) is set based on statistics that result in two values:

⦁ Aggressive value: the value is taken corresponding to only high volumes which indicate big whale moves. \
⦁ Conservative value: this value is less harsh and it takes into account the medium whales.\
\
A set of trades are considered a whale signal if they are done within a second and the sum of its volumes is higher than or equal to the threshold (Aggressive or Conservative value based on the whale type chosen). These statistics are being recalculated every while (when some movement is detected in the market context). The amount of history used to calculate statistics is proportional to the time frame you select, when it’s too large you will get results for a long time ago and it will take more time to be done (but the very old data may be meaningless in the current time), if it’s too small you will have results for a very small period in the history (not enough to give an idea of the market) even though it will be very fast calculated, so be careful of the time frame you choose to use the tool for. When you set more than one instance of the indicator or strategy for the same symbol/time frame at the same time, the statistics will be calculated only once and you will have to wait only for the first one to be done.\


### WhaleSplash Indicator:&#x20;

When you choose the indicator, if the statistics are not done being calculated, you will see the sentence (Whale Splash: Loading...) on the bottom left corner till they are done.\
![](<../.gitbook/assets/image (74).png>)

When it’s done calculating if the option “Show statistics for history” is checked, the history signals will be drawn for the historical period that statistics were calculated for and based on the selected whale type. You can evaluate the results of statistics by looking at the history signals to make sure you selected a proper time frame. In the future, a whale icon will be drawn for each new signal, and you will get an alert if the “Send Alerts” option is checked.\


### WhaleSplash Strategy:&#x20;

\
You can get the strategy tool from chart drawings, and you can start it to have quick access to it.\
![](<../.gitbook/assets/image (99).png>)

After choosing the tool, draw a rectangle on the chart which indicates the bounds (time and price) you want your orders to be placed within.

![](<../.gitbook/assets/image (98).png>)

The Logs button shows/hides logs on the chart. The settings are as follows:\
![](<../.gitbook/assets/image (131).png>)\


⦁ If checked you will receive an alert for each order placed for you.&#x20;

⦁ Here you can select the license you want to use (you can find information about each license bounds on the prices page). \
⦁ The side to place the order (buy or sell). \
⦁ The number of signals you want to place orders for in the rectangle (for example, if it’s set to 2 then after 2 whale signals within the rectangle bounds, which means 2 orders placed, the strategy will stop). \
⦁ The whale type indicates the value from statistics results that you want to set as a threshold. \
⦁ If the side is bought, then the percentage is the percentage of the quote currency balance you want to use in each trade. If the side is selling then it’s the base currency balance percentage. \
⦁ The base quantity for the order. ⦁ The quote quantity for the order.

⦁ 6 & 7 & 8 are calculated from each other, you can enter any of them and the rest will be calculated automatically.

⦁ You can specify the Side and base/quote percentage directly from the tool on the chart.

⦁ After you run the strategy you can’t change the selected license anymore.\
⦁ You can’t enter quantity = 0 or a quantity higher than your balance.

⦁ You have license limits on the quantity and #Trades, #Trades is limited for all instances of the strategy, this means that if your limit is 10 trades then you can run several instances from the strategy where the sum of #Trades of them is less than or equal to 10. For example, if you have two instances of WhaleSplash strategy running for BTC/USDT each with 2 trades, and one running for ETH/BTC with 4 trades then your trades sum is 8 and you still can add and run strategies for any symbol/time frame but you have only 2 trades left. In this case, if you added a strategy with 3 trades it won’t run, and if you run a strategy with 2 trades you won’t be able to run any other instance of the strategy.

⦁ If your trades for a certain license are done and you have another one, you can add more instances using the other license and within its limits.
