# Stock market tracker in React

* Technologies
    -  IEX Cloud stock market API
        - iexcloud.io 
        - Endpoint: GET /stock/{symbol}/intraday-prices
        - Base URL: https://cloud.iexapis.com/stable
        - example URL: https://cloud.iexapis.com/stable/stock/aapl/intraday-prices?token=pk_9b7f5ff55fe7486bb3ad6cba7aa80b7d&chartLast=1
        - API token: pk_9b7f5ff55fe7486bb3ad6cba7aa80b7d 
        - use ChartLast=1 to get the last price
        - you get daily max 50 calls per ticker 
    - React JS
    - 

* [x] Setup React project 
    - npx create-react-app stock-tracker
    - react version 16.13.1
* [x] Install Bootstrap 
    - npm install react-bootstrap bootstrap 
* [x] Create StockRow component
    * [x] fetch stock data from iex using fetch
* [] Create service to get stock data
