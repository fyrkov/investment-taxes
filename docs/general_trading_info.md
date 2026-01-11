# General info about trading and investments

Lets take a look at the different roles involved in trading and investments.
```
Investor → Broker → Exchange → CCP → Custodian → CSD
                     ↑
                Market maker
```
### Custodian
A custodian holds securities on behalf of investors and handles post-trade processes such as settlement,
safekeeping, corporate actions, and income payments.

Examples:
* J.P. Morgan
* Clearstream Banking Luxembourg

### Depositary (CSD)
Central securities depository (CSD) operates at the market-infrastructure level. 
It maintains the central register of securities for a market and enables settlement between custodians.
Investors and brokers do not interact with a CSD directly.\

Relationship
```
Investor → Broker → Custodian → Depositary (CSD)
```

Examples:
* Clearstream Frankfurt
* Euroclear Belgium

### Broker
A broker is the intermediary between the investor and the market. 
It receives client orders, routes them for execution, and maintains the client account. 

### Exchange
An exchange is an organized marketplace where buy and sell orders are matched according to 
defined rules (price–time priority, auctions, etc.). 
It provides price discovery and trade execution.

Examples:
* Xetra
* NYSE
* Euronext

### Market makers
Market makers continuously quote buy and sell prices for certain instruments. 
They provide liquidity and reduce spreads by standing ready to trade from their own inventory.

### Clearing house / CCP
A clearing house sits in the middle of every trade and becomes the buyer to the seller and the seller to the buyer.
Its job is to make sure both sides get what they are owed, even if one party fails.\
Examples: Eurex Clearing

### Issuer
The company or entity that issues the security.

### Regulator / Supervisor
Oversees market integrity and compliance.
Examples: BaFin, ESMA

### Data vendors
Provide market data, reference data, and corporate actions.
Examples: Bloomberg, WmDaten

### How a typical market order works

1. The investor submits a market order to the broker (buy or sell, quantity only).
2. The broker routes the order to an exchange or trading venue.
3. The order is executed immediately against the best available prices, often provided by market makers or existing limit orders in the order book.
4. The trade is confirmed to the broker and investor.
5. Post-trade, the exchange reports the trade.
   The trade is then cleared by a central counterparty (CCP) and settled via custodians and the CSD.

Key point:
With a market order, the execution price is not guaranteed — only immediate execution is.

