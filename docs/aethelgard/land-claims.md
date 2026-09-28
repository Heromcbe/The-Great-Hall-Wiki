# Land Claims

Claim your land to protect your builds. Inside your claim, only you and the players you add can build, break blocks, or open your containers.

## Claim Limits

| | Default | VIP |
|---|---|---|
| **Cost per chunk** | 100 EP | 75 EP |
| **Max claims** | 7 | 7 |
| **Max chunks in one claim** | 256 | 1,024 |
| **Max chunks in total** | 312 | 1,113 |
| **Members per claim** | 6 | 8 |
| **`/claim tp` delay** | 5 seconds | Instant |
| **Distance from other claims** | None | None |

Creating a claim is free. You only pay for the chunks in it. There's **no minimum distance** between claims, so you can claim right next to your friends. A chunk is a 16 × 16 area, from the bottom of the world to the top.

You can claim land in the **Overworld** and **the End**.

!!! note "The Nether is shared"
    The Nether is small, so it **can't be claimed**. This keeps fortresses, biomes, and other key spots open to everyone.

## Commands

| Command | What it does |
|---|---|
| `/claim` | Claim your starting area: a **4 × 4 chunk** square (64 × 64 blocks, 16 chunks) |
| `/claim radius <n>` | Claim a square around you (`/claim radius 1` = 3 × 3 chunks) |
| `/claim addchunk` | Add the chunk you're standing in to your claim |
| `/claim merge` | Merge claims that touch into one |
| `/unclaim` | Unclaim the land you're standing on |
| `/claims` | Open a menu to view and manage all your claims |
| `/claim see` | Show your claim's borders for 10 seconds |
| `/claim seenear` | Show the borders of claims near you |
| `/claim tp` | Teleport to one of your claims |
| `/aclaim add <claim-name> <player>` | Add a player as a member of a claim. Use `*` instead of a claim name to add them to all your claims |
| `/aclaim remove <claim-name> <player>` | Remove a player from a claim (or `*` for all your claims) |
| `/claim permissions` | Choose what members and visitors can do |
| `/claim flags` | Choose claim-wide settings (explosions, fire, mob spawns, and more) |
| `/claim sell` | Put a claim up for sale to other players |
| `/cc` | Claim chat: talk only to players in your claim |

`/territory`, `/unterritory`, and `/territories` also work in place of `/claim`, `/unclaim`, and `/claims`.

!!! tip "Your first claim"
    `/claim` covers a 4 × 4 chunk area (64 × 64 blocks). Claims follow Minecraft's chunk grid, so a 50 × 50 build still needs the full 64 × 64. It costs 16 chunks at your rank's chunk price.

## What's Protected

**Visitors** (players who aren't members) can walk through your claim, but by default they **can't**:

- build or break blocks
- open chests, barrels, furnaces, or other containers
- use buttons, levers, doors, or redstone
- harm your animals, ride your mounts, or use your item frames and armor stands

**Members** can do everything except destroy spawners.

**Inside every claim, by default:**

- no creeper, TNT, or other explosion damage
- no fire spread
- no mob griefing (like endermen taking blocks)

You can change any of these with `/claim permissions` and `/claim flags`.

## Good to Know

- **Borders:** particles show the edges of a claim as you claim it. You'll also see a message when you enter or leave someone's claim.
- **Live map:** claims appear on the [Live Map](live-map.md) with their name and owner.
- **Selling:** claims can be bought and sold between players with `/claim sell`.

!!! tip "Claim before you build"
    Unclaimed builds are at your own risk. Claim first, then build.

---

*Last verified: 2026-09-28*
