# Fees

Trading fees are charged **per fill** and depend on whether you add or remove liquidity, and on your recent volume. Network (gas) costs are abstracted — you pay a single trading fee, not a separate per-click gas fee.

| Role | Fee | Notes |
| --- | --- | --- |
| Maker | 0.010% | Adds liquidity by resting on the order book |
| Taker | 0.035% | Removes liquidity by matching immediately |
| High volume | lower | Fees decrease as your 30-day volume grows |

{% hint style="info" %}
Figures above are **illustrative** and will be confirmed before public launch.
{% endhint %}

## What's not a fee

* **Funding** is not a fee to Rocky — it is exchanged between longs and shorts. See [Funding & Mark Price](funding-and-mark-price.md).
* **Deposits/withdrawals** settle on-chain and may incur a network fee shown at confirmation.
