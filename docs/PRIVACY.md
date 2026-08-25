# Privacy Notice

> **Release blocker:** before public distribution, replace `[LEGAL NAME]`, `[POSTAL ADDRESS]`, and `[PRIVACY EMAIL]`, name every hosting and advertising processor, confirm retention periods, and obtain a qualified legal review.

**Controller:** [LEGAL NAME], [POSTAL ADDRESS]  
**Privacy contact:** [PRIVACY EMAIL]  
**Version:** 2026-08-24

KloorLauncher is an unofficial Minecraft: Java Edition launcher. This notice covers the launcher, the Kloor API, optional social features, and the optional Kloor Credits reward system.

## Data we process

- Microsoft sign-in happens in the system browser. Microsoft refresh tokens and Minecraft access tokens stay encrypted on the user's Windows device and are not stored in the Kloor database.
- The Kloor API stores the verified Minecraft UUID, username, optional public skin/cape URLs, account settings, session identifiers, friend relationships, and privacy preferences.
- If an adult explicitly enables rewards, the API stores the policy and provider-consent versions and time, random ad-session identifiers, completion status, Kloor Credits ledger, purchases, shop-agreement versions, and owned launcher cosmetics.
- Security logs may contain timestamps, request identifiers, route names, status codes, and redacted diagnostic data. Passwords and authentication tokens must not be logged.

KloorLauncher does not send Microsoft/Xbox tokens, Minecraft UUIDs, gamertags, friend data, or profile data to an advertising provider. A provider may receive only a random, short-lived reward-session token required for server-to-server completion verification.

## Purposes and legal bases

- **Contract/service:** authenticate licensed users, launch Minecraft, preserve settings, and deliver requested social or shop functions.
- **Consent:** start an optional rewarded advertisement. Consent is separate from Microsoft sign-in, can be refused without losing core launcher functions, and can be withdrawn as easily as it is accepted.
- **Legitimate interests:** prevent fraud, secure accounts, diagnose failures, and keep an auditable virtual-credit ledger, balanced against user rights.
- **Legal obligation:** retain or disclose limited records when applicable law requires it.

No advertising identifier or SDK may run before valid consent. Personalized advertising is disabled. Reward advertising is unavailable to users under 18.

## Sharing and transfers

Data is shared only as necessary with Microsoft/Mojang authentication services, the selected hosting/database processors, and an advertising provider that has expressly approved the Windows/Electron rewarded flow. The final provider and its privacy notice must be named here before ads are enabled. International transfers require a documented lawful safeguard.

KloorLauncher does not sell personal data.

## Retention

- Encrypted local authentication data remains until logout or local application data is removed.
- Active profile, settings, inventory, and ledger data remain while the account is active.
- Expired or revoked API sessions are deleted within 30 days.
- Incomplete ad sessions and routine security logs are deleted or anonymized within 90 days unless needed to investigate abuse.
- After a verified deletion request, personal data is deleted or anonymized without undue delay. Limited ledger evidence may be retained for up to 24 months only when necessary for fraud disputes or legal claims.

The controller must verify these periods against its actual infrastructure and legal obligations before launch.

## User rights

Depending on applicable law, users may request access, correction, export, restriction, objection, or deletion and may withdraw consent at any time. Requests go to [PRIVACY EMAIL]. Identity may be verified without asking for a password or token. EU users may complain to their national authority; in Estonia this is the Andmekaitse Inspektsioon.

## Children

The launcher may have younger users, but rewarded advertising is restricted to adults who confirm they are at least 18. KloorLauncher does not knowingly profile children for advertising. Core login, download, and play features must remain available without ads.

## Security

Tokens are isolated from the renderer, encrypted with Windows secure storage, and redacted from logs. The API validates live sessions, scopes every query to the authenticated user, rate-limits requests, verifies provider callbacks cryptographically, and records virtual-credit changes in an append-only ledger. No system is perfectly secure; report suspected incidents privately to [PRIVACY EMAIL].

## Changes

Material changes are shown before they take effect. A new consent is required whenever the configured provider version, advertising purpose, or applicable policy version changes.
