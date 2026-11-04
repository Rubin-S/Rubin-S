# Rubin S

ECE undergrad at NIT Puducherry (class of 2028). I build trading research tools in C++ and Python, and I test ideas honestly: pre-registered hypotheses, holdout data, and fees included.

## Start here

- **[market-making-simulator](https://github.com/Rubin-S/market-making-simulator)**: C++20 maker backtester on Binance BTCUSDT L2 data. Quoting the touch only breaks even at a -0.60 bp maker fee, a rebate bigger than Binance offers. Matches hftbacktest fill-for-fill in 16/16 configs.
- **[order-flow-imbalance](https://github.com/Rubin-S/order-flow-imbalance)**: reproduces Cont, Kukanov & Stoikov (2014) on 72.6M Binance events. Order flow explains about 60% of 1-second moves after the fact but predicts about 1% ahead: real, but not tradable after fees.
- **[l2-orderbook-replay](https://github.com/Rubin-S/l2-orderbook-replay)**: C++20 L2 book replay, 46,642/46,642 matches against Tardis snapshots, 263M events/s (12.4x a std::map book).
- **[probability-and-markets](https://github.com/Rubin-S/probability-and-markets)**: expected value, Bayes, gambler's ruin and Kelly sizing, each solved exactly and checked with Monte Carlo, plus a toy market maker facing informed traders.
- **[options-pricing-and-hedging-engine](https://github.com/Rubin-S/options-pricing-and-hedging-engine)**: Black-Scholes-Merton pricer, Greeks, implied-vol solver and a discrete delta-hedging simulator.

## Also

Campus software I built and shipped: AskIT, NEXUS, the NITPY alumni portal and conference sites.

**C++20 · Python · R · probability · statistics · market microstructure**

[LinkedIn](https://www.linkedin.com/in/rubin-s-355169255) · doyenchess@gmail.com
