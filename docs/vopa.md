# 📈 Vorabpauschale (VOPA) - Advance Flat-Rate Tax

The Vorabpauschale is a "pre-paid" tax on the expected gains of investment funds (ETFs).
Collected once in a year and applied only if ETFs increased in price.
VOPA contributions decrease future tax if ETF is sold.

**Calculation Logic:**

```
If ETF grew: `Tax = (0.7 * Basiszins * (Value of the fund on Jan 1st) - Dividends) * 70% (if Equity ETF) * 26.375%`
else: `Tax = 0`
```

Brokers calculate VOPA on the 2 Jan (legal accrual date) for the previous year.\
Effective payout can happen later.

Brokers are obliged to track VOPA contributions and credit them against final sell of the ETF.\
Usually for that purpose acquisition cost of the corresponding ETF position is increased.
