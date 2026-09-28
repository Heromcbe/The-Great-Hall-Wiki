# Aethelgard Coins

To trade at a shop, your EP needs to become a physical item: a **coin**. Aethelgard has two kinds. They look alike (both are a special compass), but they do very different jobs.

## Deposit Coin

**Spendable money in item form**, like a banknote.

| | |
|---|---|
| **How you get one** | Sell something to a shop (the market or a player's shop), or make one yourself with `/withdraw <amount>` |
| **How you cash it in** | `/deposit` cashes in **every** Deposit Coin in your inventory at once |
| **Who can use it** | **Anyone** holding it. It's freely transferable |

!!! warning "Treat Deposit Coins like cash"
    Anyone who picks one up can spend or deposit it. Don't leave a valuable one lying around, and deposit coins you don't need.

## Balance Coin

**A shop's savings account**, not personal spending money. It's what pays for the items your shop buys from other players.

| | |
|---|---|
| **How you make one** | `/coin balancecoin <amount>` takes EP from your balance and locks it into a coin tied to you |
| **What it's for** | Place it in your shop's chest to fund your shop. See [Running a Shop](../shops/running-a-shop.md) |
| **How you cash it in** | Take it out of your chest and run `/deposit` |
| **Who can use it** | **Only you** |

!!! success "Theft-proof"
    If anyone other than you picks up or moves your Balance Coin, the game notices right away, refunds its value straight to **your** balance, and tells them what happened. You can't lose a Balance Coin to theft, a chest raid, or dying with it.

## Deposit vs. Balance at a Glance

| | Deposit Coin | Balance Coin |
|---|---|---|
| **Job** | Spending money | Funds your shop |
| **Made with** | `/withdraw <amount>`, or selling to a shop | `/coin balancecoin <amount>` |
| **Anyone can use it?** | Yes | No, only the owner |
| **Cash in with** | `/deposit` | `/deposit` |

---

*Last verified: 2026-09-28*
