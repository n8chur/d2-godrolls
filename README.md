# d2-godrolls

My personal Destiny 2 gear wishlist for d2checklist.com and app.destinyitemmanager.com.

## How to update

Updating the god rolls requires that the updater be running on macOS with [Mint](https://github.com/yonaskolb/Mint) installed and have access to [d2-wishlist](https://github.com/n8chur/d2-wishlist) (it's a private repository at the time of writing this).

Run:

```bash
mint run n8chur/d2-wishlist d2-wishlist "./" --pve "Input/PvE.txt" --pvp "Input/PvP.txt"
```
