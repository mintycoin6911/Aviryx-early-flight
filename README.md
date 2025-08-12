# Aviryx — Early Flight Aurora Skywyrm Event

🪽 **Aviryx ($AVX)** — Bird of the Chain. Guardian of Memes.  
Official repository for the **Early Flight** event, including:

- Cute pastel premium Aurora Skywyrm cards (5 tiers + Shiny Celestial)
- Leaderboard integration
- Telegram bot commands
- Social media teaser assets

## 📂 Structure
```
aurora_cards/         # Static & animated PNG/GIF cards
community_tools/      # Rules & holders data (for leaderboard)
web/landing/          # Leaderboard HTML
bots/telegram/        # Bot integration snippets
```

## 🚀 Quick Start

### 1. Clone this repo
```bash
git clone https://github.com/YOURUSERNAME/aviryx.git
cd aviryx
```

### 2. Hook up the bot
Follow `bots/telegram/PATCH_AURORA.md` to integrate `/myaurora` and the Tweet button.

### 3. Update holders data
Your bot should update `community_tools/aurora/holders.json` with:
- `wallet`
- `handle`
- `highest_balance`
- `tier_index`
- `tier`

### 4. Deploy leaderboard
Serve `web/landing/aurora-leaderboard.html` or host via GitHub Pages.

---
**Legal Note:** All rewards in this event are cosmetic digital collectibles only. No financial yield, staking, or monetary payouts.


> This repo includes the **Aurora Skywyrm Early Flight** assets, leaderboard page, and Telegram bot patch snippets pre-installed.
