# Stock-Catch
The stock market equivalent of [coin-catch](https://github.com/TobiahRex/coin-catch)

## MISSION
To be a single source of truth for the entire user experience as it relates to investing in the stock market.

## GOALS
Remove the multi-step, multi-platform, multi-access requirements to trade stocks on today's leading platforms, 4 specific targets are:
  1. Yahoo Finance
  2. ThinkOrSwim
  3. E-trade
  4. MetaTrader

## VALUES
  - Automation
  - Speed
  - Useability

## KEYS TO SUCCESS
The user is easily able to participate in stock investing with **Minimal requirements for specialized skills** of:
  1. _Digital Tools_ e.g. Composing a stock scanner with a 3rd parties proprietary platform that is variable broker-to-broker.
  2. _Scripting languages_
     - python
     - mql4
     - c++
     - R
  3. _Platform Features_ setups across platforms that offer different functionality. This platform would compose and consolidate skills from all 4 broker targets.
  4. _Placing Trades_ can be difficult given the platform. It's a highly technical, highly specific process that has many optional parameters. (example of order types from TOS)[https://www.thinkorswim.com/tos/displayPage.tos?webpage=servicesOrderTypesCanada]
  5. _Portfolio Management_ can vary based on platform. This is problematic since our portfolio can be atomized across multiple platforms/brokers to truly cast the widest possible net.

## PRODUCTS & SERVICES
This platform will sit atop multiple brokers' API's, and be a single source of truth for interacting with the stock market. To do that we offer our customers the following services.
  1. **One Portfolio Dashboard**: The user can see, and asses their entire portfolio across any and all brokerages they are signed up with. From this dashboard the user can _reblanace their porfolio_ across all assets. WHY?  Because different platforms have different transactional costs, different Volume, ...
  2. **One Trade Tool**: The user can enter, exit, modify their trades across multiple platforms in a single location.  
  3. **Alerts & Notifications**: The true inspiration for this application was spawned from this idea. Across different platforms, creating customized alerts for stocks universally requires the user to be familiar with alert setup, and be very proficient in the broker's platform tools. Furthermore, the platforms do not ask for the users follow-on action after serving the alert to the user.  The user is simply informed, then ignored. The user must log back into their account at some point in the future,
  then initiate the "next-step".  True automation/augmented trading allows for the user input request-for-action **(RFA)** and be updated on the status of the RFA's result, and perhaps, be given another RFA.
  4. **Scanning 4 Opportunity**: Scanners are universal across platforms. However they require a highly proficient level of understanding of either scripting languages, or platform specific interface tools. We will provide the customer with a single source of truth for scanning across all brokerages with either scripting languages (JavaScript or Python), or with proprietary tools. Furthermore, we will have an AI assistant to scan the market for anomalies not capable of being detected with traditional investment tools.  These AI assistants require both news and indicators to be properly efficient. News can vary from platform to platform. This platform ingests all the news across all the platforms and composes those multiple inputs to a single output thus creating awareness of the market not currently available on any platform individually.
  5. **Risk Management & Metrics**: Based on the users current asset portfolio, an assisted risk management dashboard will allow users to explore different portfolio metrics given different risk profiles, and capital input. The user can answer questions such as:
     - How much risk is required to achieve 30% growth per quarter, given my capital?
     - What is my P/L when initiating trades with a volatility score above 3 compared to a volatility score of 2?
     - Based on my current performance, what is my expected growth rate in 2 years, assuming a 15% decrease in long term market trends?
     - My portfolio has decreased 15% over the last quarter, what is the recommended improvement to my risk appetite to reduce that percentage to 5% over the next quarter, assuming my confidence in current strategy is high.
  6. **RFA customizations**: Once an alert has been created on an asset from the users "WatchList", or group of assets from the users "ActiveScan" criteria, the user can automate a list of RFA's. Example.
     - _**Scenario Setup**_ User has created a scan to detect the following stock attributes
       1. Greater than $1, and less than $5.
       2. Has volatility score greater than 3 of 5.
       3. Has a signal initiated in the past 5 periods from custom indicator X.
     - The user now has an **RFA Customizer** setup with the following steps.
       1. If the top 3 assets on the list of results from the scan (described in the previous step) has changed, send me a text message with the following options.
        - Mock RFA Message to User:
        ```
        *** ALERT ***
        Stock AAPL has been seen as the #2 stock on your current scan report.
        ========================
        CURRENT TRADE SETTINGS
        ------------------------
        Size:         1%    of 'Available' Capital
        Target:       +10%  of Entry
        Stop:         -10%  of Entry
        Stop-Alert:   -5%   of Entry

        Text "E" to Edit
        ========================
        RFA-options
        ------------------------
        Text (Letter) to respond.

        A) Enter an OCO-MARKET order.

        B) Enter an OCO-LIMIT order.

        C) Create "Hawkish Alert" on AAPL.

           Text "Show-Hawk" to see current Hawkish Alert settings.

        D1) See screenshot of price chart.

        D2) See screenshot of price chart w/Indicators.
        ```
      2. The user can customize the "RFA-options" actions to different potential options.
         - The current answer as to "WHY" is simply due to the fact that we need not create a mobile app in the short-term to have the best feature of this APP be available.
