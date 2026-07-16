
# JSP Trade Journal

The Python application that keeps an automatic journal of every closed trade
in Google Drive.

It reads the closed trades of each strategy straight from MT5 and writes them
into their own Google Sheet, filed in Drive by asset, year and month. Every
strategy gets its own journal with a small dashboard on top, and the app keeps
it all in step on its own: when a strategy is added, removed or renamed, its
journal follows. It only ever adds new closed trades, so nothing already
written is touched.

## Full content
The application is attached in the release:
https://github.com/piazzolimichele1/_01_Python/releases/tag/_JSP_TradeJournal
