# asymetrex-bot-api
This small discordJS bot shows you how the asymetrex exchange api can be used.

Our API is very easy and straightforward to use. Asymetrex makes use of both private and public methods. The public methods consist of GET POST requests, while private are composed of POST. All of the requests are made through.
URL - https://asymetrex.com/api



General Server Information (GET)

Returns general information about the exchange:


Version: Current Exchange Version


Timestamp: Floating-point Precision


Volume: BTC Volume


URL - https://asymetrex.com/api



Currency List (GET)

Returns a list of all the coins on the exchange, including their ticker.


URL - https://asymetrex.com/api/currency_list



Ticker Information (GET)

Receive information about a specific ticker (e.g. ltcbtc).


URL - https://asymetrex.com/api/tickers/TICKER



Ticker List (GET)

Returns a list of all the tickers currently on the exchange.


URL - https://asymetrex.com/api/tickers



Market Trades (GET)

Shows the market trades for a given market. The limit parameter is optional and regulates length of the array.


URL - https://asymetrex.com/api/trades?market=MARKET&limit=LIMIT



Market Depth (GET)

Shows info about the market depth.


URL - https://asymetrex.com/api/depth?market=MARKET



Order Book (GET)

Returns a list of the order book. asks_limit and bids_limit parameters are optional.


URL - https://asymetrex.com/api/order_book?market=MARKET&bids_limit=BIDS_LIMIT&asks_limit=ASKS_LIMIT



K Line (GET)

Returns a list of all the graph data for a given market.


URL - https://asymetrex.com/api/k?market=MARKET&limit=LIMIT&period=PERIOD
