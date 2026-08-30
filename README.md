# KloorLauncher

KloorLauncher is a Windows launcher for **Minecraft: Java Edition**. It provides one place to manage Minecraft installations, mods, modpacks, servers, resource packs, Java settings, and launch options.

**NOT AN OFFICIAL MINECRAFT PRODUCT. NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR MICROSOFT.**

## Download

The official public download is available at **https://kloor.eu/#download**:

- `KloorLauncher-1.9.3.exe`
- Platform: Windows 10/11, 64-bit
- Type: Windows installer
- SHA-256: `94c3665908b7ba399a47e31292b4800f7cc49024eb336bab730369e75d8dcd9d`

## Features

- Separate Minecraft installations and game directories
- Vanilla, Fabric, Forge, and NeoForge profile support
- Mods, modpacks, servers, and resource-pack management
- Automatic checksum-verified Java 8, 16, 17, 21, and 25 runtimes
- Modrinth and CurseForge mods, resource packs, and shaders with compatibility and hash checks
- Modrinth `.mrpack` support with dependency and conflict checks
- Integrity-checked KloorCore auto-install for compatible Fabric 1.21.1 profiles
- Installation repair, world backups, and local crash analysis
- Safe Mode, automatic world backups, installation snapshots, and rollback
- Hardware-aware Low, Balanced, and High performance profiles
- Managed mod conflict checks and safe update-all with rollback
- Pausable, resumable, cancellable, and speed-limited downloads
- Storage analysis and exact duplicate cleanup
- Portable Kloor modpack export
- Favorite servers with automatic latency refresh
- Server version compatibility warnings and recent join history
- Live friend status with automatic reconnect
- Private 30-day friend chat
- Polished in-game KloorCore shop, purchase confirmation, particle emotes, player auras, friends, and chat
- Social features: emote wheel, cosmetic previews, saved loadouts, friend requests, server invites, profiles, blocking and reporting
- One-click friend joining with compatibility checks
- Multiple securely stored Microsoft accounts
- Local screenshot manager and launch/session performance statistics
- Built-in Skin Studio with direct drawing on a rotatable 3D character, body/outer layers, PNG import/export, and verified Minecraft account upload
- Optional end-to-end encrypted settings and profile-preset sync
- Built-in What's New page
- English and Estonian interface
- Adjustable RAM and download settings
- Launch and download progress
- Microsoft account authentication
- Verified offline single-player after a successful ownership check
- Kloor-themed Windows interface
- Optional Kloor Credits ledger and fixed-price launcher-theme shop foundation
- Password-protected Kloor users with salted Argon2id credential storage
- Separate adult advertising consent and shop-rule acceptance
- Legal, privacy, and unofficial-product notices inside the launcher

## Getting started

1. Download `KloorLauncher-1.9.3.exe` from https://kloor.eu/#download.
2. Open the file.
3. Sign in with the Microsoft account that owns Minecraft: Java Edition.
4. Create a KloorLauncher username and a unique 15–128-character Kloor password to use Friends and earn Kloor Credits.
5. Create or select an installation.
6. Press **Play**.

KloorLauncher automatically installs the compatible Eclipse Temurin Java runtime when it is missing.

## Mods and modpacks

- A **mod** is one individual game modification.
- A **modpack** is a prepared collection of compatible mods, configurations, and sometimes resource packs.
- Installations stay isolated so files from one profile do not mix with another profile.

## Important notes

- KloorLauncher does not bypass Minecraft ownership or provide cracked accounts.
- Online play requires a valid Microsoft account and Minecraft: Java Edition license.
- Microsoft sign-in may return error `403` until the launcher registration is approved for Minecraft Services.
- This build is currently unsigned, so Windows SmartScreen may display a warning. Code signing or Microsoft Store distribution is planned.
- Live rewarded ads are intentionally disabled until an approved Windows/Electron provider, publisher HTTPS API, provider contract, and legal review are complete.
- Social, rewards, and shop services need the publisher API; Minecraft installation and launch features remain independent.
- Use kloor.eu for public downloads. GitHub release files are retained as backup copies.

Read the [Privacy Notice](docs/PRIVACY.md), [Terms of Service](docs/TERMS.md), [Reward & Shop Rules](docs/REWARDS.md), and [release checklist](docs/LEGAL-CHECKLIST.md).

## Reporting problems

When opening an issue, include:

- KloorLauncher version
- Windows version
- Minecraft version and loader
- The complete error message
- Steps that reproduce the problem

Do not post Microsoft passwords, access tokens, refresh tokens, or other private account information.

## Project status

KloorLauncher is under active development. Features, data formats, and authentication behavior may change between releases.
