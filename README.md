# Tradingview Syariah Indicator

## What it does
Add a small indicator in tradingview.com, unfortunately currently only cover Malaysian stocks.

source data:
[bursa malaysia](https://www.bursamalaysia.com/market_information/equities_prices?legend%5B%5D=%5BS%5D&sort_by=short_name&sort_dir=asc&page=1)

inspired from
https://github.com/amree/tradingview-shariah-indicators

## Install
<a target="_blank" rel="noopener noreferrer"
   title="Download Tradingview Shariah indicator in chrome now"
   href="https://chrome.google.com/webstore/detail/tradingview-shariah-indic/eogackkjbjbbmlkbakekhaanphmnpkgf">
    <img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_128x128.png" width="48" />
</a>

<a target="_blank" rel="noopener noreferrer"
   title="Download Tradingview Shariah indicator in firefox now" 
   href="https://addons.mozilla.org/en-US/firefox/addon/tradingview-shariah-indicator/">
    <img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_128x128.png" width="48" />
</a>

<a target="_blank" rel="noopener noreferrer"
   title="Download Tradingview Shariah indicator in Edge now" 
   href="https://support.microsoft.com/en-my/help/4027935/microsoft-edge-add-or-remove-browser-extensions">
    <img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_128x128.png" width="16" />
    Please install this extension from chrome store.
</a>

## Release 
[https://github.com/AzrizHaziq/tradingview-syariah-indicator/releases](https://github.com/AzrizHaziq/tradingview-syariah-indicator/releases) 

[Symbol Page](https://www.tradingview.com/symbols/MYX-MI/)
![Symbol page](https://github.com/AzrizHaziq/tradingview-syariah-indicator/blob/mid-and-small-cap/docs/ori_chrome/cutted_page_symbol.png?raw=true)
![Symbol page](https://github.com/AzrizHaziq/tradingview-syariah-indicator/blob/mid-and-small-cap/docs/ori_ff/cutted_page_symbol.png?raw=true)

[Chart page](https://www.tradingview.com/chart/)
![Chart page](https://github.com/AzrizHaziq/tradingview-syariah-indicator/blob/mid-and-small-cap/docs/ori_chrome/cutted_page_chart.png?raw=true)
![Chart page](https://github.com/AzrizHaziq/tradingview-syariah-indicator/blob/mid-and-small-cap/docs/ori_ff/cutted_page_chart.png?raw=true)

<p float="left">
  <img src="https://github.com/AzrizHaziq/tradingview-syariah-indicator/blob/mid-and-small-cap/docs/ori_chrome/cutted_page_chart_with_stock_screener.png?raw=true" width="200px" />
  <img src="https://github.com/AzrizHaziq/tradingview-syariah-indicator/blob/mid-and-small-cap/docs/ori_ff/cutted_page_chart_with_stock_screener.png?raw=true" width="200px" /> 
</p>

[Screener page](https://www.tradingview.com/screener/)
![Screener page](https://github.com/AzrizHaziq/tradingview-syariah-indicator/blob/mid-and-small-cap/docs/ori_chrome/cutted_page_screener.png?raw=true)
![Screener page](https://github.com/AzrizHaziq/tradingview-syariah-indicator/blob/mid-and-small-cap/docs/ori_ff/cutted_page_screener.png?raw=true)

## Youtube video
[![tradingview-syariah-indicator](https://img.youtube.com/vi/4U8mu_5UfUQ/0.jpg)](https://www.youtube.com/watch?v=4U8mu_5UfUQ)

Feel free to contact me if any bug or more features here  
[azrizhaziq@gmail.com](mailto:azrizhaziq@gmail.com)


## Developers
1. Need to have node and npm (please look at package.json > engine)
2. Type in terminal `$ npm install`
3. Type in terminal 
    Firefox: `$ npm run start` 
    Chrome: `$ npm run start:chrome`
   
   
## Generate Production ready extension
1. Type in terminal `$ npm run build`


## Update Stock list data (will take a few X minutes)
1. Type in terminal `$ npm run scrapping`
    
