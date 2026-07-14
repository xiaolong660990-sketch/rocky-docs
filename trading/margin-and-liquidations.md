# Margin & Liquidations

## Margin modes

* **Cross margin** — all your positions share one collateral pool. More resistant to liquidation on any single position, but a bad position can draw down your whole balance.
* **Isolated margin** — margin is capped per position. A liquidation only costs the margin assigned to that position.

## Margin ratio & maintenance

Each position has a **maintenance margin** requirement. As price moves against you, your margin ratio falls. If it drops below maintenance, the position becomes eligible for **liquidation**.

## Liquidation

When a position is liquidated, it is closed to protect the system from further loss. Backstops:

* **Insurance fund** — absorbs shortfalls from liquidations.
* **Auto-deleveraging (ADL)** — in extreme moves, offsetting positions may be reduced to keep the system solvent.

{% hint style="warning" %}
To avoid liquidation: use lower leverage, keep spare margin, and set a stop-loss above your liquidation price. Monitor your **liquidation price** as the market moves.
{% endhint %}
