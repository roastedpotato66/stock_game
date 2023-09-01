# Stock game checker
This short program can check whether you win the stock game in UMich class ECON 310 by Dr. Maciej Dudek for extra credits. Here is how the game works:

1. Pick a stock weekly and submit it before Monday.
2. If the stock's overall performance (price change) is higher than the benchmark, it was S&P 500 for the class, you win for that week.
3. There were a total 10 weeks of games. You will get $(x - 5) * 2 \\%$ point to your final grade. $x$ is the time you win the game.

This program will not be able to help you track how many times you win, but you will know whether you win that week by entering the stock tick and period.

I use the close price on Friday minus the open price on Monday to get the difference. Otherwise, if you see the number differ, it maybe count as the price change during after-market trade.


