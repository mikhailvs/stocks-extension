# [stocks-extension](https://extensions.gnome.org/extension/1422/stocks-extension/)
A extension to display stock quotes in GNOME Shell Panel

![Screenshot](https://github.com/cinatic/stocks-extension/raw/master/images/extension.png)

*stocks-extension* integrates stock quotes to your GNOME Shell Panel =)

----

## Installation

### Over extensions.gnome.org (EGO)

Install via install button -> https://extensions.gnome.org/extension/1422/stocks-extension/

### Generic (Local installation)

Move files into your locale extension directory (~/.local/share/gnome-shell/extensions/stocks@infinicode.de) and enable the extension via the Tweak Tool, it is **important** to move it to **stocks@infinicode.de** otherwise the extension will not be recognized by GNOME.
Restart GNOME Shell (`Alt`+`F2`, `r`, `Enter`) and enable the extension through *gnome-tweak-tool*.

## Add Stocks

To add stocks you need a yahoo symbol-exchange pair. Search for stocks on yahoo finance and get your symbol

1. Open Settings
2. Click on the + icon on the bottom of the first tab
3. Enter the symbol-exchange pair (e.g. AHLA.DE) and give it a name

![Screenshot](https://github.com/cinatic/stocks-extension/raw/master/images/settings.png)

## ToDo
1. ~~Keep older Quotes in case no new quoates are available~~
2. ~~Add exchange information & currency data~~
3. ~~Avoid complete Rerender on Quote update~~
4. Add Watchlist functionality
5. Add new alternate services for data


## Troubleshooting
### Only n/a is shown or no change / previous close value 
Maybe crawler is broken or exchange is not open, in the case exchange is closed the current quote will be overwritten with null, this will be changed in a later version

## [icons8.com](https://www.icons8.com)
I used the beatiful and dank svg icons from [icons8.com](https://www.icons8.com), i really love you guys, best icon source every!11

:heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :point_right: [icons8.com](https://www.icons8.com) :point_left: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart:
