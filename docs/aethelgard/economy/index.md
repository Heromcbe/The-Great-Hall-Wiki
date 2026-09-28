# Electrum (EP)

**Electrum (EP)** is Aethelgard's currency. Your EP balance is tracked by the server. Most of the time it's just a number, but when you trade at a shop your money becomes a physical coin. See [Aethelgard Coins](coins.md).

## Checking Your Balance

```
/bal
```

## Earning EP

| How | What happens |
|---|---|
| **Sell ores at the market** | The NPCs in the market at **spawn** buy ores from you. |
| **Sell to player shops** | Players run shops that buy items from you. See [Buying & Selling](../shops/buying.md). |
| **Run your own shop** | Sell your goods to other players. See [Running a Shop](../shops/running-a-shop.md). |

When you sell to a shop (the market or a player's), you're paid in **Deposit Coins**. Run `/deposit` to turn them into EP on your balance.

## Paying Another Player

There's no `/pay` command. Hand over coins instead:

1. Run `/withdraw <amount>` to turn EP into a **Deposit Coin**.
2. **Give the coin** to the other player (drop it or trade it to them).
3. They run `/deposit` to add it to their balance.

## Spending EP

- **Player shops:** buy goods from other players with Deposit Coins.
- **Land claims:** claiming land costs EP. See [Land Claims](../land-claims.md).

## Quick Commands

| Command | What it does |
|---|---|
| `/bal` | Check your EP balance |
| `/withdraw <amount>` | Turn EP from your balance into a Deposit Coin |
| `/deposit` | Cash in every Deposit Coin (and your own Balance Coins) in your inventory |
| `/coin balancecoin <amount>` | Make a Balance Coin to fund your shop |

---

*Last verified: 2026-09-28*
