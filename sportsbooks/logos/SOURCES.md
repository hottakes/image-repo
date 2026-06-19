# iGaming operator logo sources

41 operators, two variants each:

- `sportsbooks/icons/<slug>.png` — 1024×1024 opaque square icon (brand-colored background, centered mark).
- `sportsbooks/logos/<slug>.png` — 1024×1024 transparent logo (centered, full safe-area).

Assets were assembled from official brand sources where available (operator sites, app-store/PWA artwork, and the Brandfetch brand CDN), then normalized to a consistent square format. Provenance and brand-accuracy notes below.

| Operator | Slug | Official domain | Primary source | Confidence | Notes |
|---|---|---|---|---|---|
| 888 Casino | `888casino` | 888casino.com | Brandfetch (official brand CDN) | high |  |
| 888 Sport | `888sport` | 888sport.com | Brandfetch (official brand CDN) | high |  |
| Baba Casino | `baba` | babacasino.com | Official site SVG | high |  |
| Bally's Casino | `ballys-casino` | ballys.com | Brandfetch (official brand CDN) | high |  |
| BetNova | `betnova` | betnova.ca | casino.guru brand SVG + apple-touch icon | medium | Ontario/Canada brand (not US); updates existing icon |
| betPARX | `betparx` | betparx.com | Official site SVG (logo) + Brandfetch (icon) | high |  |
| BetVictor | `betvictor` | betvictor.com | Brandfetch (official brand CDN) | high |  |
| Big Pirate | `big-pirate` | bigpirate.com | Brandfetch (official brand CDN) | high |  |
| PlayBracco | `bracco` | playbracco.com | Official site SVG | high | Real brand is PlayBracco; Brandfetch 'bracco.com' was the wrong Bracco Imaging medical company |
| Casino Click | `casino-click` | casino.click | Official site SVG + Brandfetch (icon) | high |  |
| Casino Time | `casino-time` | casinotime.ca | Brandfetch icon (logo derived by keying out black) | low | Canada-only, geo-blocks US; brand NOT confirmed as US sweeps; logo is white-only (dark-bg use) |
| Funrize | `funrize` | funrize.com | Brandfetch (official brand CDN) | medium | Only a low-res 156px source exists; request a vector from the operator for hi-DPI |
| Gleaming Slots | `gleaming-slots` | gleamingslots.com | Review-site vector CDN (Stakester/Supabase) | high | Official site Cloudflare-blocked; vector verified visually |
| Go Go Gold | `go-go-gold` | gogogoldwin.com | Official PWA app icon | high | Logo variant is the square brand mark (no separate wordmark published) |
| HelloMillions | `hello-millions` | hellomillions.com | Oddschecker CDN logo + Google Play icon | high |  |
| High 5 Casino | `high5` | high5casino.com | Brandfetch (official brand CDN) | high |  |
| JackpotGO | `jackpotgo` | jackpotgo.com | Brandfetch (official brand CDN) | high |  |
| Jackpota | `jackpota` | jackpota.com | Brandfetch (official brand CDN) | high |  |
| Lavish Luck | `lavish-luck` | lavishluck.net | Official og:image + Brandfetch (icon) | high | Logo source is small (292px) |
| Legendz | `legendz` | legendz.us.com | Official site logo | high | Operator runs on legendz.us.com (not legendz.com) |
| Lucky Days | `lucky-days` | luckydays.com | Brandfetch icon keyed to transparent + App Store icon | medium | Canada-licensed; logo is white-only wordmark; updates existing icon |
| MegaBonanza | `megabonanza` | megabonanza.com | Brandfetch (official brand CDN) | high |  |
| McLuck | `mcluck` | mcluck.com | Oddschecker CDN SVG + Google Play icon | high |  |
| NorthStar Bets | `northstar` | northstarbets.ca | Official site asset | high | Ontario/Canada brand; logo is white-only (dark-bg use) |
| ParlayPlay | `parlayplay` | parlayplay.io | Dimers CDN wordmark + App Store icon | high | Brandfetch only had the bare mask symbol; full wordmark sourced separately |
| Playfame | `playfame` | playfame.com | Brandfetch (official brand CDN) | high |  |
| PlayStar Casino | `playstar` | playstar.com | Official site SVG | high | NJ/PA real-money casino |
| Polymarket | `polymarket` | polymarket.com | Brandfetch (official brand CDN) | high | Prediction market (not a casino) |
| Pulsz | `pulsz` | pulsz.com | Brandfetch (official brand CDN) | high |  |
| RealPrize | `realprize` | realprize.com | Brandfetch (official brand CDN) | high |  |
| Spinfinity | `spinfinity` | spinfinity.com | Brandfetch (official brand CDN) | high |  |
| SpinQuest | `spinquest` | spinquest-us.com | Official site logo | high |  |
| Spinz Casino | `spinz-casino` | spinz.com | Brandfetch (official brand CDN) | high |  |
| Casino Spree | `spree` | spree.com | Official Bunny CDN | high | Brandfetch generic 'Spree' was wrong; this is the Casino Spree sweeps brand |
| Stake.us | `stake-us` | stake.us | Wikimedia wordmark + Brandfetch (icon) | high |  |
| Sweep Jungle | `sweep-jungle` | sweepjungle.com | Official site assets | high |  |
| Sweeptastic | `sweptastic` | sweeptastics.com | Official site logo (64px) | low | Brand is 'Sweeptastic' (two e's); reportedly ceased operations Mar 2025; only a tiny 64px asset exists — LOW QUALITY |
| TitanPlay | `titanplay` | titanplay.ca | Brandfetch (official brand CDN) | medium | Ontario/Canada AGCO-licensed brand (not US sweeps) |
| TonyBet | `tonybet` | tonybet.com | Brandfetch (official brand CDN) | high |  |
| ToonieBet | `tooniebet` | tooniebet.com | Brandfetch (official brand CDN) | high |  |
| WowVegas | `wowvegas` | wowvegas.com | Brandfetch (official brand CDN) | high |  |

## Flags worth reviewing
- **Casino Time** and **Sweeptastic** are low-confidence: Casino Time is a Canada-only site that geo-blocks the US (brand not confirmed for a US sweeps program), and Sweeptastic (note the two e's) reportedly ceased operations in March 2025 with only a tiny 64px logo available.
- **BetNova**, **NorthStar Bets**, and **TitanPlay** are Ontario/Canada-licensed brands, not US sweepstakes operators.
- **PlayBracco** (bracco) and **Casino Spree** (spree) replace wrong-company logos that brand directories returned for those names.
- **Funrize** and **Lavish Luck** were only available at small source resolutions; a vector from the operator would be preferable for hi-DPI.
- White-only wordmark logos (**casino-time**, **lucky-days**, **northstar**) are intended for dark backgrounds.
