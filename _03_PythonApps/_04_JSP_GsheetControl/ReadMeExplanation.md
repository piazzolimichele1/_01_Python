
# JSP GSheet Control

The Python application that turns a Google Sheet into a live control panel for
the whole trading operation.

It reads everything running on the VPS: the strategies, the MT5 terminals and
accounts, the open positions, the trade updater and the machine's own health,
and writes it all to a Google Sheet every couple of seconds. The sheet only
receives, so it stays a clean live dashboard. Nothing is hardcoded: it finds
the strategies and the running terminals on its own, so the sheet always
follows whatever the machine is really doing.

## Full content
The application is attached in the release:
https://github.com/piazzolimichele1/_01_Python/releases/tag/_JSP_GsheetControl_
