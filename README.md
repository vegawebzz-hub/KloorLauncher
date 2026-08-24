# KloorLauncher

KloorLauncher is a Windows launcher for **Minecraft: Java Edition**. It provides one place to manage Minecraft installations, mods, modpacks, servers, resource packs, Java settings, and launch options.

## Download

The newest build in this repository is:

- `KloorLauncher-1.0.6.exe`
- Platform: Windows 10/11, 64-bit
- Type: portable application — installation is not required
- SHA-256: `CB7A288AA2397D9BDECAB01B9A409774D66600C29E1F0C4ABBC006C580C4C10D`

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

## Getting started

1. Download `KloorLauncher-1.0.6.exe`.
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
- Only download builds from this repository and compare the SHA-256 checksum when possible.

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
