# HardCoreTest Launcheer

HardCoreTest Launcher is an independent Windows desktop launcher under development for the HardCoreTest community.

This repository hosts the modpack distribution files used by the launcher.

## Features

- Installs a dedicated Minecraft: Java Edition 1.21.1 instance with Fabric 0.19.5.
- Checks for published modpack updates before launching.
- Verifies downloaded files using cryptographic hashes.
- Allows users to configure the memory allocated to the game.

## Authentication

The current version requires Microsoft authentication and verified access to Minecraft: Java Edition before gameplay.

Users authorize the launcher through Microsoft's device-code flow in their browser. The launcher does not collect Microsoft passwords. Session credentials are stored locally using operating-system-protected encryption.

The current version does not provide an offline or unauthenticated launch mode.

## Development status

Microsoft OAuth, Xbox Live authentication and XSTS authorization have been tested successfully. Minecraft Services currently returns HTTP 403 during the Minecraft token exchange.

An AppID review request is being prepared for this application's own Client ID:

`0b1ab76e-e884-44ad-af3a-46f846e7cea7`

A public launcher installer has not yet been released. The files currently published in Releases are modpack distribution assets.
