# iGaming operator logo sources

Initial batch: 41 operators, two variants each:

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


## DAZN BET (2026-09-11)

- Added `sportsbooks/icons/dazn-bet.png` for the shared operator brand catalogue.
- Official source: [DAZN Bet: Sports & Casino on the Apple App Store](https://apps.apple.com/gb/app/dazn-bet-sports-casino/id1672192705), published by DZBT Limited.
- [Original 1024px artwork](https://is1-ssl.mzstatic.com/image/thumb/Purple211/v4/e9/9d/3b/e99d3bfd-bbce-fed7-2fef-c536081932d8/AppIcon-0-0-1x_U007emarketing-0-11-0-85-220.png/1024x1024bb.png); visually cross-checked against the [official operator site icon](https://www.daznbet.com/assets/favicons/apple-touch-icon.png).
- Format: 1024 x 1024 PNG, opaque sRGB, solid black canvas, square corners, original centered white/yellow DAZN BET mark. Mark bounds are 738 x 360 at +143+332, giving a 72% horizontal safe area.
- Prepared in complete-icon mode, retaining the official artwork without redrawing or stretching. Visually checked at 32, 48, 64, 128, and 256 pixels. This addition supplies the opaque icon only.
- Tracking: https://github.com/hottakes/workflow-and-wiki/issues/2000


## Hard Rock Bet Casino (2026-09-24)

- Added `sportsbooks/icons/hard-rock-bet.png` for the shared operator-brand catalogue and volume-raffle configuration. Existing `hardrock.png` remains unchanged; it is a legacy 76 x 82 image.
- Official source: [Hard Rock Bet Casino on the Canadian Apple App Store](https://apps.apple.com/ca/app/hard-rock-bet-casino/id6753178980), published by Seminole Hard Rock Digital, LLC.; listing links to https://hardrockbet.ca/.
- [Original 1024px artwork](https://is1-ssl.mzstatic.com/image/thumb/Purple221/v4/b4/c8/0a/b4c80a07-7e7d-60fe-ed6c-fe66eb31bbf5/CasinoCAAppIcon-0-0-1x_U007epad-0-1-0-85-220.png/1024x1024bb.png). Preserved the original complete app icon without redrawing, resizing, or stretching.
- Format: 1024 x 1024 PNG, opaque sRGB, square corners, white Hard Rock BET / CASINO mark on its official magenta background. Visually inspected; no clipped mark or transparent canvas.
- SHA-256: `909e3df30013a455ed7bb1b161cee2c32ac8cf77f96b89bae0820d919befb96e`.
- Tracking: https://github.com/hottakes/workflow-and-wiki/issues/2527


## theScore Bet (2026-10-21)

- Added `sportsbooks/icons/thescore-bet.png` for the shared operator-brand catalogue (ht-business operator brand `TheScore`, used for its sportsbook and casino links).
- Official source: [theScore Bet: Sports Betting on the Canadian Apple App Store](https://apps.apple.com/ca/app/thescore-bet-sports-betting/id1465992052), published by Score Media and Gaming Inc.; listing links to https://www.thescore.bet.
- [Original 1024px artwork](https://is1-ssl.mzstatic.com/image/thumb/Purple221/v4/35/20/4c/35204cee-db2d-8c06-1a23-fb7eb5c6265f/AppIcon-0-0-1x_U007ephone-0-1-0-85-220.png/1024x1024bb.png). Preserved the complete app icon without redrawing, resizing, or stretching; only metadata was stripped (pixel-identical to the source).
- Format: 1024 x 1024 PNG, opaque sRGB, square corners, white theScore "S" mark on its official blue-to-black gradient with the yellow BET band. Visually checked at 32, 48, 64, 128, and 256 pixels; no clipped mark or transparent canvas.
- SHA-256: `01eb0db784e916ba3fc2d908974bbc40c7895bee4baf35948e2de3ecf4eae8f7`.
- Tracking: https://github.com/hottakes/workflow-and-wiki/issues/3405


## Active production operator opaque-icon completion (2026-10-26)

Tracking: https://github.com/hottakes/workflow-and-wiki/issues/3575

Opaque icon work only; transparent logos are unchanged. Each output is a 1024 x 1024 opaque sRGB PNG. Official complete app icons retain their source pixels; mark sources are centered with a 72% maximum axis on an intentional dark brand canvas. No generated or redrawn marks. PNG encoding and metadata were optimized without quantizing colors. Square masters and circular crops at 24, 32, and 40 pixels were visually reviewed.

| Brand | Icon path | Official source page / publisher | Original artwork | Preparation / notes |
|---|---|---|---|---|
| BET365 | `sportsbooks/icons/bet365.png` | [Source page](https://apps.apple.com/ca/app/bet365-sports-betting/id1600273117?uo=4) / Hillside Technology Limited | [Artwork](https://is1-ssl.mzstatic.com/image/thumb/Purple211/v4/d8/94/47/d8944757-fdef-2ef8-6751-694f01fbbd4d/AppIcon-CA-0-0-1x_U007epad-0-1-0-sRGB-85-220.png/1024x1024bb.png); 1024 x 1024 px | Official App Store 1024px complete icon; publisher and product selected from Apple metadata; preserve the complete square artwork. Output RGB pixels match the official 1024px PNG source. |
| BetMGM | `sportsbooks/icons/betmgm.png` | [Source page](https://apps.apple.com/ca/app/betmgm-sportsbook-casino/id1609578715?uo=4) / BetMGM, LLC | [Artwork](https://is1-ssl.mzstatic.com/image/thumb/Purple211/v4/e8/1a/ff/e81aff83-9382-4cdf-625d-b480abb6c1c2/AppIcon-0-0-1x_U007epad-0-1-0-85-220.png/1024x1024bb.png); 1024 x 1024 px | Official App Store 1024px complete icon; publisher and product selected from Apple metadata; preserve the complete square artwork. Output RGB pixels match the official 1024px PNG source. |
| BetRivers | `sportsbooks/icons/betrivers.png` | [Source page](https://apps.apple.com/us/app/betrivers-casino-sportsbook/id1635357259?uo=4) / Rush Street Interactive LLC | [Artwork](https://is1-ssl.mzstatic.com/image/thumb/Purple211/v4/c1/81/91/c181913b-e8bb-f8e3-07c4-158eda21ba5c/AppIcon-0-0-1x_U007epad-0-1-0-sRGB-85-220.png/1024x1024bb.png); 1024 x 1024 px | Official App Store 1024px complete icon; publisher and product selected from Apple metadata; preserve the complete square artwork. Output RGB pixels match the official 1024px PNG source. |
| DraftKings | `sportsbooks/icons/draftkings.png` | [Source page](https://apps.apple.com/us/app/draftkings-sports-casino/id1375031369?uo=4) / DRAFTKINGS LLC. | [Artwork](https://is1-ssl.mzstatic.com/image/thumb/Purple211/v4/6c/56/a2/6c56a297-0db4-78db-6897-d8dfb9833a39/AppIcon-0-0-1x_U007epad-0-1-85-220.png/1024x1024bb.png); 1024 x 1024 px | Official App Store 1024px complete icon; publisher and product selected from Apple metadata; preserve the complete square artwork. Output RGB pixels match the official 1024px PNG source. |
| FanDuel | `sportsbooks/icons/fanduel.png` | [Source page](https://apps.apple.com/us/app/fanduel-sportsbook-casino/id1413721906?uo=4) / FanDuel Limited | [Artwork](https://is1-ssl.mzstatic.com/image/thumb/Purple221/v4/b7/15/56/b7155694-f2ea-0146-879f-8304b2b80642/AppIcon-0-0-1x_U007emarketing-0-11-0-85-220.png/1024x1024bb.png); 1024 x 1024 px | Official App Store 1024px complete icon; publisher and product selected from Apple metadata; preserve the complete square artwork. Output RGB pixels match the official 1024px PNG source. |
| PointsBet | `sportsbooks/icons/pointsbet.png` | [Source page](https://apps.apple.com/ca/app/pointsbet-sportsbook-casino/id1613813063?uo=4) / PointsBet Canada Operations 1 Inc | [Artwork](https://is1-ssl.mzstatic.com/image/thumb/Purple211/v4/71/94/50/71945020-06f9-8a63-0065-a8d1896135f9/AppIcon-sportsbook-0-1x_U007emarketing-0-8-0-85-220-0.png/1024x1024bb.png); 1024 x 1024 px | Official App Store 1024px complete icon; publisher and product selected from Apple metadata; preserve the complete square artwork. Output RGB pixels match the official 1024px PNG source. |
| Sports Interaction | `sportsbooks/icons/sports-interaction.png` | [Source page](https://apps.apple.com/ca/app/sports-interaction-sportsbook/id6444409687?uo=4) / Avid Ecom Solutions Limited | [Artwork](https://is1-ssl.mzstatic.com/image/thumb/Purple211/v4/d3/ba/a6/d3baa673-8a4d-3012-2433-a30333b6a091/AppIcon-0-0-1x_U007epad-0-1-0-85-220.png/1024x1024bb.png); 1024 x 1024 px | Official App Store 1024px complete icon; publisher and product selected from Apple metadata; preserve the complete square artwork. Output RGB pixels match the official 1024px PNG source. |
| Hollywood | `sportsbooks/icons/hollywood.png` | [Source page](https://apps.apple.com/ca/app/hollywood-casino/id6736526782?uo=4) / Score Media and Gaming Inc. | [Artwork](https://is1-ssl.mzstatic.com/image/thumb/Purple221/v4/ef/19/a4/ef19a461-d287-880b-0c4b-4e0d592f1dc3/HollywoodCasino-AppIcon-0-0-1x_U007ephone-0-1-0-85-220.png/1024x1024bb.png); 1024 x 1024 px | Official App Store 1024px complete icon; publisher and product selected from Apple metadata; preserve the complete square artwork. Output RGB pixels match the official 1024px PNG source. |
| OG | `sportsbooks/icons/og.png` | [Source page](https://apps.apple.com/us/app/og-com-trade-sports-events/id6757954676?uo=4) / OG Markets Limited | [Artwork](https://is1-ssl.mzstatic.com/image/thumb/Purple221/v4/23/8e/43/238e434d-2ccd-29a5-aa50-e5ef84799f19/AppIcon-0-0-1x_U007ephone-0-1-85-220.png/1024x1024bb.png); 1024 x 1024 px | Official App Store 1024px complete icon; publisher and product selected from Apple metadata; preserve the complete square artwork. Output RGB pixels match the official 1024px PNG source. |
| Prophet X | `sportsbooks/icons/prophet-x.png` | [Source page](https://apps.apple.com/us/app/prophetx-prediction-market/id6504584166?uo=4) / ProphetX OpCo LLC | [Artwork](https://is1-ssl.mzstatic.com/image/thumb/Purple221/v4/c7/e9/63/c7e963e3-62b8-a19c-a7d6-63d66ba606a3/AppIcon-0-0-1x_U007emarketing-0-8-0-85-220.png/1024x1024bb.png); 1024 x 1024 px | Official App Store 1024px complete icon; publisher and product selected from Apple metadata; preserve the complete square artwork. Output RGB pixels match the official 1024px PNG source. |
| Underdog | `sportsbooks/icons/underdog.png` | [Source page](https://apps.apple.com/us/app/underdog-sports-games-rips/id1514665962?uo=4) / Underdog Sports, Inc. | [Artwork](https://is1-ssl.mzstatic.com/image/thumb/Purple221/v4/b3/10/4a/b3104af9-872f-7fce-aa2c-aad237ce24ad/underdog-0-0-1x_U007ephone-0-1-0-85-220.png/1024x1024bb.png); 1024 x 1024 px | Official App Store 1024px complete icon; publisher and product selected from Apple metadata; preserve the complete square artwork. Output RGB pixels match the official 1024px PNG source. |
| 247Bet | `sportsbooks/icons/247bet.png` | [Source page](https://casimba-affiliates.com/brand/247bet/) / Casimba Gaming / Casimba Affiliates | [Artwork](https://casimba-affiliates.com/wp-content/uploads/brand/247bet/SVG/247bet-white.svg); 1400 x 266 px | Official affiliate brand-kit SVG, white/green mark; original operator parent also identifies 247Bet. Separate from Action 247. Rasterized from vector at 1400px width. |
| Card Crush | `sportsbooks/icons/card-crush.png` | [Source page](https://www.cardcrush.com/) / Card Crush | [Artwork](https://storage.googleapis.com/www.cardcrush.com/cardcrush-images/brand-logos/logo.png); 454 x 251 px | Official logo URL observed directly in the operator restricted-access page DOM. Native 454x251 transparent raster, sufficient for current 24-40px avatars; modest resampling for composition does not imply native 1024px source detail. |
| Coinsback | `sportsbooks/icons/coinsback.png` | [Source page](https://www.coinsbackcasino.com/) / CoinsBack Casino | [Artwork](https://www.coinsbackcasino.com/favicon.svg); 1024 x 1024 px | Official site SVG favicon (1000px viewBox), linked in the page head; purple CB mark, distinct from unrelated CoinsBack domains. Rasterized from vector. |
| FunzCasino | `sportsbooks/icons/funzcasino.png` | [Source page](https://funzcasino.com/) / Funz Casino | [Artwork](https://funzcasino.com/wp-content/uploads/2025/12/funz-mobile-logo.svg); 987 x 1024 px | Official mobile SVG mark directly linked by the operator page. Vector cyan/purple mark on a deliberate dark high-contrast square; distinct from Funrize. |
| Chip'n Win | `sportsbooks/icons/chipnwin.png` | [Source page](https://chipnwin.com/manifest.webmanifest) / Chip'n WIN | [Artwork](https://chipnwin.com/icon/pwa/android-launchericon-512-512_v3.png); 512 x 512 px | Official non-seasonal PWA mascot icon linked by the operator manifest. Native source 512x512; resampled to catalogue canvas, without claiming extra source detail. Transparent outer corners flattened to the existing top-edge brand purple. |

Existing `sportsbooks/icons/prophet.png` remains the historical Prophet Exchange artwork. The current Prophet X configuration uses the separate `prophet-x.png`. Existing `action247.png` is not 247Bet and is unchanged. The existing Hard Rock Bet Casino and theScore Bet complete icons remain unchanged. Native raster-source limits for Card Crush (454 x 251) and Chip'n Win (512 x 512) are disclosed above; normalized canvas size does not imply additional source detail. This work does not change operator market availability, licensing statements, or affiliate links.
