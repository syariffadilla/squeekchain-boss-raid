# Squeekchain Boss Raid

A weekly boss-raid browser game for the Squeekchain Genesis Code lane.

Live: https://raid.x-mood.my.id/ (custom domain, Vercel DNS). Also at https://squeekchain-boss-raid.vercel.app/.

The boss HP is the live Squeek block progress from `https://api.squeekchain.com/v1/status`, polled every 15 seconds. Damage comes from Squeektoshi's real wheel work: settled rounds and cumulative work units. Players pick a raid class (Gnawer, Sprinter, or Bulwark), build Wheel Charge, and attack with crits, combos, and Frenzy mode when the wheel is actually spinning. The boss resets every Monday at 00:00 UTC.

No wallet, no token, and no betting — points only, with progress saved locally in the browser.

## Play

Open `index.html` in a browser, or deploy it to any static host. The game fetches live data from the public Squeekchain API (no key, CORS enabled). If the API is unreachable, the page shows an honestly labelled offline snapshot instead of fake live data.

## Squeekchain

- Genesis Code: https://squeekchain.com/genesis/code
- Docs: https://docs.squeekchain.com/
- API: https://api.squeekchain.com/v1/status
- Network: Ethereum Sepolia (chain ID 11155111)

Sepolia contracts (from the official docs):

- SqueekCore: `0x74665dAecA35A2303e767E76a2FF1FB6F93e119f`
- SqueekMining: `0x3beE588fC20dE788Bac17d33b41Da7346cb27EC4`
- SQK token: `0x6872bfa5ccc3e9e440c6c16e5ffdabb8dba4cc76`
- Squeek NFT: `0x0eAF3E0d40A0a8E5a6Ac030b2459E9FB0B7905c6`

## Genesis submission

This is a community project for the Squeekchain Buildooooor badge, submitted via Direct submission (self-built, not IMD): the live site runs on the builder's own domain, and verification needs the DNS record and page tag issued by Genesis plus this repository line in the README.

Status: live on https://raid.x-mood.my.id/ — submission form saved, verification in progress.

squeekchain-project: 12f4e5ee-b67b-4dc9-80e5-819166155a8e
