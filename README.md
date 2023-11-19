# RaiOne-Vault

![GitHub release (latest by date)](https://img.shields.io/github/v/release/raiblocksone/raione-vault)
[![GitHub All Releases](https://img.shields.io/github/downloads/raiblocksone/raione-vault/total)](https://github.com/raiblocksone/raione-vault/releases/latest)
[![Discord](https://img.shields.io/badge/discord-join%20chat-orange.svg?logo=discord&color=7289DA)](https://discord.gg/RRMh2s8ZWT)

RaiOne-Vault is a community driven fork of the popular nano wallet [Nault](https://github.com/Nault/Nault) 💙

It's a fully client-side signing wallet for sending and receiving [RaiblocksOne](https://github.com/raiblocksone/raiblocksone-node/) either directly in your browser at [vault.raione.cc](https://vault.raione.cc) or with the [desktop app](https://github.com/raiblocksone/raione-vault/releases/latest).

Seamless integration with any RaiblocksOne compatible RPC backend/websocket and the aim to be more frequently maintained are some of the main features. Those together will greatly increase the stability, performance and uptime.
___

## How To Use
RaiOne-Vault comes in different flavors to suit your need.
#### Desktop App
Available for Windows/Mac/Linux - just head over to the [latest release](https://github.com/raiblocksone/raiblocksone-node/releases/latest) and download the version for your OS.

If you want to verify the binary checksum there are plenty of apps to do this. One way is using a powershell or bash terminal:

* **Powershell:** `Get-FileHash -Path '.\Nault-Setup-x.x.x-Windows.exe' -Algorithm SHA256`
* **Bash:** `openssl sha256 Nault-x.x.x-Linux.AppImage`

Then compare the output hash with the one listed in the corresponding checksums file that you download.

#### Web App
You can also use RaiOne-Vault from any device on the web at [vault.raione.cc](https://vault.raione.cc).

#### Mobile App
There is no native mobile app but the web wallet contains a Progressive Web App (PWA). That allows you to run it in offline mode for remote-signing.

If you visit [vault.raione.cc](https://vault.raione.cc) in your phone you will be given the option to install it.

* Android: Click on "Install RaiOne-Vault for Android" in the menu
* iOS (Safari only): 1 - Tap the share button. 2 - Select "+ Add to home screen". 3 - Open RaiOne-Vault from the home screen

## How To Help

Thanks for your interest in contributing! There are many ways to contribute to this project. [Get started here at CONTRIBUTING.md](CONTRIBUTING.md).

If you want to know how to setup the development environment head over to [DEVELOPMENT.md](DEVELOPMENT.md).

## Support

If you are looking for more interactive and quick support compared to creating a new Github issue, you will then find most of the developers in the Nault channel over at the [TNC discord server](https://discord.gg/RRMh2s8ZWT).

## Acknowledgements

Special thanks to the following!

- [NanoVault](https://github.com/cronoh/nanovault) - The original one
- [Nault](https://github.com/nault/nault) - The forked one
- [numtel/nano-webgl-pow](https://github.com/numtel/nano-webgl-pow) - WebGL PoW Implementation
- [jaimehgb/RaiBlocksWebAssemblyPoW](https://github.com/jaimehgb/RaiBlocksWebAssemblyPoW) - CPU PoW Implementation
- [dcposch/blakejs](https://github.com/dcposch/blakejs) - Blake2b Implementation
- [dchest/tweetnacl-js](https://github.com/dchest/tweetnacl-js) - Cryptography Implementation

## Donations

If you have found RaiOne-Vault useful and are feeling generous, you can donate to the Nault donation wallet
`xro_3niceeeyiaa86k58zhaeygxfkuzgffjtwju9ep33z9c8qekmr3iuc95jbqc8`

Thanks a lot!
