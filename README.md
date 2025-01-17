# d3-reactjs-vehicle-event-ledger-ui

It serves as a front end UI to record vehicle maintenance actions.  Requests are sent to a REST API, found in the [go-demo-hedera-ledger-rest repository](https://github.com/Crypto-Brothers/go-gin-vehicle-event-ledger-api), that logs messages on the Hedera distrubuted ledger.  The go-demo-hedera-ledger-rest project runs on localhost:8082. 

The function of this demo app is to log noteable vehicle events, such as damage, malufunctions, repairs, performance metrics onto a public, immutable distibuted ledger.  In a real world implemetation, users could use this log to prove they did maintenance on their vehicle, which would be usefull for resale evalution purposes. The manufactureer and orgazizations, like insurance providers and independent reviewer, would also find the data invaluable.

## Setup

This demo assumes you have already installed [Node JS](https://nodejs.org/en/download/) & [Yarn package installer](https://classic.yarnpkg.com/en/docs/install/)

### Set url & port from REST endpoint (default is 8082)
/src/http-common.js
```
baseURL: "http://localhost:8082/",
```

## Project setup

In the project directory, you can run:

```
yarn install
```

or

### Compiles and hot-reloads for development

```
yarn start
```

Open [http://localhost:8080](http://localhost:8080) to view it in the browser.


Much of the UI was derived from forked repo, [jkuri/d3-car-dashboard](https://github.com/jkuri/d3-car-dashboard).

# D3 Car Dashboard Experiment

Car dashboard experiment with D3 data visualisation and React.

## Preview

![Preview](https://raw.githubusercontent.com/Crypto-Brothers/d3-reactjs-vehicle-event-ledger-ui/master/.github/images/democap.gif)

## Instructions

Use UP arrow key to add throttle.

