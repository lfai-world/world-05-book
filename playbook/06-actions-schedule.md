# 06 · Actions on a schedule — the factory checks itself

- **Daily 06:00 KST** — the runner does a full check run even if nothing new arrived.
- **Quarterly (1 Jan · Apr · Jul · Oct)** — the parts scout searches open source for better parts for each station.

A schedule is a line of text (`cron`). Use it for chores, not for endless computing: GitHub's terms forbid using Actions as a general-purpose compute service.

## Say this
> "이거 매일 아침 6시에 한 번 돌게 해."
*(Run this every morning at 6.)*
