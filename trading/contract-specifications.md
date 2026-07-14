# Contract Specifications

Each market defines its own leverage limits, tick size, and settlement asset.

| Market | Max Leverage | Tick Size | Settlement |
| --- | --- | --- | --- |
| BTC-PERP | 50x | 0.1 | USDC |
| ETH-PERP | 50x | 0.01 | USDC |
| Selected RWA | 20x | 0.01 | USDC |

* **Max leverage** — the highest leverage allowed on the market.
* **Tick size** — the minimum price increment for orders.
* **Settlement** — the asset used for margin and PnL.

{% hint style="info" %}
Example values for layout. The full market list and final parameters will be published before launch and will expand over time.
{% endhint %}
