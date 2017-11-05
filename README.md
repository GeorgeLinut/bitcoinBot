# bitcoinBot
Simple bitcoin trading bot
Implemented over the guidelines of Brian from CryptoCurrencyTrading  https://www.youtube.com/channel/UCme3b9GKKSjZsI8AGth-VlA 
The robot has a few basic rules.
    The most important thing that the bot takes into account is the moving average.
    The strategy is very simple:
        If the price on the chart drops below the moving average --> POTENTIAL BUY position
        If the price on the chart stars increasing again --> BUY position
        If the price on the chart rises over the moving average --> POTENTIAL SELL position
        If the price on the chart starts decreasing again --> SELL position

The implementation is not done for real usage, it's just a learning exercise, this bot will most likely lose your money! :))

How to use it:
    Create a poloniex account and replace the 'API_KEY'and 'SECRET_KEY' from r2d2.py.
