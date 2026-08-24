# Privacy Notice

> **Release blocker:** replace `[LEGAL NAME]`, `[POSTAL ADDRESS]`, and `[PRIVACY EMAIL]`, name every hosting and advertising processor, verify retention, and obtain legal review before public commercial distribution.

**Controller:** [LEGAL NAME], [POSTAL ADDRESS]  
**Privacy contact:** [PRIVACY EMAIL]  
**Version:** 2026-08-24

KloorLauncher is an unofficial Minecraft: Java Edition launcher. Microsoft sign-in occurs in the system browser. Microsoft refresh tokens and Minecraft access tokens are encrypted on the user's Windows device and are not stored in the Kloor database.

The optional Kloor API stores the verified Minecraft UUID, username, optional public skin/cape URLs, settings, session identifiers, friendships, privacy preferences, Kloor Credits ledger, purchases, shop agreements, and launcher-cosmetic entitlements. If an adult explicitly enables rewards, it also stores consent and provider-policy versions, random short-lived ad-session identifiers, and completion status. Security logs may contain timestamps, request IDs, routes, statuses, and redacted diagnostics; passwords and tokens must not be logged.

KloorLauncher must never send Microsoft/Xbox tokens, Minecraft UUIDs, gamertags, profiles, friends, or server activity to an advertising provider. An approved provider may receive only a random reward-session token needed for signed server-to-server verification.

Processing is used to deliver requested service functions, prevent fraud, keep an auditable virtual-credit ledger, meet legal obligations, and—only with separate consent—start one optional non-personalized rewarded ad. Refusal or withdrawal does not remove core login, installation, download, or launch features. Ads are unavailable to users under 18 and no ad SDK or identifier may load before consent.

Data is shared only as needed with Microsoft/Mojang authentication services, named infrastructure processors, and an expressly approved provider. International transfers require documented safeguards. KloorLauncher does not sell personal data.

Encrypted local authentication data remains until logout or local data removal. Active account, inventory, and ledger data remain while the account is active. The planned limits are 30 days for expired/revoked sessions, 90 days for incomplete ad sessions and routine logs, and up to 24 months for limited ledger evidence needed for fraud disputes or legal claims. The controller must verify these periods before launch.

Users may request access, correction, export, restriction, objection, deletion, or consent withdrawal at [PRIVACY EMAIL]. EU users may complain to their national authority; in Estonia this is the Andmekaitse Inspektsioon. Material provider, purpose, or policy-version changes require fresh consent.

Tokens are isolated from the renderer, encrypted with Windows secure storage, and redacted from logs. The API validates live sessions, scopes queries to the authenticated user, rate-limits requests, verifies callbacks cryptographically, and records credit changes in an append-only ledger.
