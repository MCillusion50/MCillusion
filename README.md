# illusion Launcher

A third-party Minecraft Java Edition launcher built with WinUI 3 + WebView2 + .NET 10.

## Features

- Microsoft account login (OAuth 2.0 Device Code Flow)
- Multi-threaded game download (ProjBobcat 2.1.2)
- Forge / NeoForge installer
- Modrinth mod management
- iOS 26 Liquid Glass UI style

## Tech Stack

- WinUI 3
- WebView2 + WebGL
- .NET 10
- ProjBobcat 2.1.2

## Purpose

This launcher uses Microsoft's official OAuth flow to let users sign in with their Microsoft account and play the official Minecraft Java Edition. It requests whitelist approval to verify legitimate game ownership via `api.minecraftservices.com`.
