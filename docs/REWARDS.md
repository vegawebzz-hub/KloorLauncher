# Reward & Shop Rules

**Currency:** Kloor Credits (`KLOOR_CREDIT`)  
**Version:** 2026-08-24

## Eligibility and choice

- Rewarded ads are optional and available only to users who confirm they are at least 18, accept the current rules and privacy notice, and explicitly enable rewards.
- Refusing or withdrawing consent does not disable Microsoft login, installations, downloads, or Minecraft launching.
- Ads never autoplay. The launcher shows the provider, expected action, exact fixed reward, daily limit, and whether data leaves the device before each session.
- No reward is offered for clicking an ad, installing software, buying a product, or making misleading interactions.

## Earning credits

### Advertising-free daily tasks

- Daily tasks do not show ads and do not require advertising consent or the advertising age confirmation.
- After an authenticated launcher session starts Minecraft and the process remains running for at least 30 seconds, the launcher reports one event through the fixed API. The report contains only an idempotency key; it is a bounded client engagement signal, not anti-cheat proof. The server chooses task progress and reward amounts.
- **Ready to play:** successfully launch Minecraft once that UTC day, then claim exactly 10 Kloor Credits.
- **One more adventure:** successfully launch Minecraft twice that UTC day, then claim exactly 10 Kloor Credits.
- The combined daily-task limit is exactly 20 Kloor Credits per account per UTC day. Progress and unclaimed task eligibility reset at 00:00 UTC; credits already claimed do not expire.
- Claims require acceptance of the current Terms and Reward & Shop Rules. Duplicate reports or claims do not grant additional credits.

### Optional rewarded advertising

- Credits are issued only after the approved provider sends a valid signed server-to-server completion event.
- The launcher cannot credit itself. Duplicate, expired, forged, replayed, or over-limit events receive no credit.
- Advertising limits, cooldowns, and the fixed advertising reward are enforced separately by the Kloor API. Pending sessions may reserve one advertising slot until they expire.
- Advertising remains disabled until a provider expressly permits the Windows/Electron or hosted-web flow.
- Rewarded ads are disabled by default and are not required to earn the daily-task rewards.

## Spending credits

- Every item has a fixed credit price shown before confirmation.
- The current Terms and Reward & Shop Rules are accepted separately from advertising consent before a new purchase.
- Purchases, balance changes, and owned items are recorded in a visible ledger.
- Current items are six original launcher-only themes: Emerald, Ocean, Obsidian, Sunset, Aurora, and Frost. There are no random items, loot boxes, gameplay advantages, Minecraft capes, official textures, paid servers, mods, or modpacks.
- Owned cosmetics are permanent while the reward service and account remain available. Kloor Credits do not expire.

## No monetary value

Credits cannot be bought for money in the current version and cannot be sold, transferred, gifted, traded, withdrawn, refunded as money, exchanged for crypto or gift cards, or used outside KloorLauncher. They are not Minecoins or a Microsoft/Mojang currency.

## Corrections, abuse, and appeals

The publisher may reverse a demonstrably erroneous or fraudulent credit after retaining an audit record and explaining the decision. Legitimate purchases are not removed merely because consent is withdrawn. Users may appeal through [GitHub Issues](https://github.com/vegawebzz-hub/KloorLauncher/issues). Automated abuse, callback forgery, account farming, or ledger tampering may suspend reward access.

## Shutdown and changes

Material changes are announced before taking effect and may require fresh consent. If the system closes, the publisher provides at least 30 days to spend valid credits where technically and legally possible. Mandatory consumer rights remain unaffected.
