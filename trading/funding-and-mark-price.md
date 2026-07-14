# Funding & Mark Price

## Mark price

Positions are valued at a **mark price** derived from a robust oracle index — not the last traded price. Using an index resists manipulation and prevents unfair liquidations from a single bad print.

Your **unrealized PnL** and **liquidation checks** are based on the mark price.

## Funding rate

A **funding payment** is exchanged periodically between longs and shorts to keep the perpetual price anchored to the underlying index:

* When the perp trades **above** the index, longs pay shorts (positive funding).
* When it trades **below**, shorts pay longs (negative funding).

Funding is **not** a fee paid to Rocky — it flows between traders.

{% hint style="info" %}
If you hold a position through a funding timestamp, you either pay or receive funding depending on your side and the current rate.
{% endhint %}
