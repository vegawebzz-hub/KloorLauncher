# KloorLauncher

KloorLauncher is a Windows launcher for **Minecraft: Java Edition**. It provides one place to manage Minecraft installations, mods, modpacks, servers, resource packs, Java settings, and launch options.

**NOT AN OFFICIAL MINECRAFT PRODUCT. NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR MICROSOFT.**

## Download

The newest build in this repository is:

- `KloorLauncher-1.1.0.exe`
- Platform: Windows 10/11, 64-bit
- Type: portable application — installation is not required
- SHA-256: `383D3D993889BE8BC269E8D662D161F3C24278B86D98E442283A43FDE147F471`

## Features

- Separate Minecraft installations and game directories
- Vanilla, Fabric, Forge, and NeoForge profile support
- Mods, modpacks, servers, and resource-pack management
- Java runtime detection and custom Java path
- Adjustable RAM and download settings
- Launch and download progress
- Microsoft account authentication
- Verified offline single-player after a successful ownership check
- Kloor-themed Windows interface
- Optional Kloor Credits ledger and fixed-price launcher-theme shop foundation
- Separate adult advertising consent and shop-rule acceptance
- Legal, privacy, and unofficial-product notices inside the launcher

## Getting started

1. Download `KloorLauncher-1.1.0.exe`.
2. Open the file.
3. Sign in with the Microsoft account that owns Minecraft: Java Edition.
4. Create or select an installation.
5. Press **Play**.

Java may be required depending on the selected Minecraft version. Use a trusted distribution such as Eclipse Temurin or Microsoft OpenJDK.

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
- Only download builds from this repository and compare the SHA-256 checksum when possible.

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
