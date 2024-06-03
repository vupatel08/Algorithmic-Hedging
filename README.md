# Algorithmic-Hedging

## Forex Hedging Strategy
- TraderMade Forex API

Hedging Ratio:
<img width="745" alt="Screenshot 2024-06-03 at 7 12 42 PM" src="https://github.com/vupatel08/Algorithmic-Hedging/assets/41951347/5242f032-61df-473d-af02-828e3fc72c1c">

Annualized Return:
<img width="750" alt="Screenshot 2024-06-03 at 7 10 20 PM" src="https://github.com/vupatel08/Algorithmic-Hedging/assets/41951347/bb93b003-2407-4960-847c-3be96175ef53">

Monthly Total Return:
- Daily Data: 0.19%
- Hourly data: 0.03%

Annualized Total Return: 
- Daily data: 61.63%
- Hourly data: 70.07%

## Multi-Greek Hedging

Case:
A colleague currently has a short position in 1000 NVDA calls, she wants to hedge her exposure to changes in volatility, movements in the underlying asset, and the speed of movements in the underlying asset. You're on the risk-management desk and offer to construct a dynamic hedge to be rebalanced daily (more on this later). How can we neutralize her exposure to the option's vega, delta, and gamma?

- Final Delta, Gamma, and Vega Neutral Portfolio
  - -1000 NVDA Calls
  - 8641 Call A Options
  - -8006 Call B Options
  - 46 Shares of NVDA

