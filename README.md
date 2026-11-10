# HiveLoop

**Every Hive challenge. One loop.**

HiveLoop is a single-page, no-login guide to everything happening on the [Hive blockchain](https://hive.io): all current challenges, contests and power-up days from across Hive's communities in one live place — so nobody has to search everywhere to find out what they can join.

🌐 **Live site:** enable GitHub Pages for this repo (Settings → Pages → deploy from `main`) or open `index.html` in any browser.

## What it does

- **27 challenges, checked against the chain** — power-up days (HPUD, CPUD, LPUD, BPUD), Power Up Month, and weekly/daily contests for photography, writing, music, gaming, lifestyle and saving (MONOMAD, Shadow Hunters SMASh, Ladies of Hive, Hive Learners, Three Tune Tuesday, Splinterlands, HivePosh, Saturday Savers Club, Ecency quests and more)
- **A month calendar** — tap a power-up day to jump straight to its card
- **Live countdowns** ticking every second, sorted by what's ending soonest, with an "Up next" spotlight
- **Honest status labels** on every card — *Running now* / *Monthly date* / *Check latest post* — including warnings when a challenge has no current-month announcement
- **"New to Hive? Start here"** — a 3-step path for complete beginners
- **Tap any card** for the 1-2-3 steps, rewards, tags to use, organiser and the official link
- **Check your account** (optional, public data only): enter any Hive username to see Hive Power, LEO Power, wallet, voting power and RC — plus whether that account can join each power-up day (HPUD: reputation 39–70, 100–8,000 HP, 10 liquid HIVE; LPUD: under 25,000 Leo Power)
- **Live pulse** — latest Hive posts and trending tags, refreshed automatically
- **Light / dark mode** toggle

## Privacy

No login. No keys. Ever. The page reads only public blockchain data (via public Hive API nodes and Hive-Engine) directly from your browser. Nothing you type is sent anywhere except to those public APIs to fetch the public data you asked for.

## How it works

One self-contained `index.html` — no build step, no server, no dependencies. All data is fetched live in the browser from `api.hive.blog` (with public fallback nodes) and the Hive-Engine API.

## Credits

Built by [@arslanjapani](https://hive.blog/@arslanjapani). Challenge data verified on-chain, November 2026. Power-up days and contests belong to their organisers (HiveBuzz, LeoFinance, and each community) — HiveLoop only lists them and links to the official posts.
