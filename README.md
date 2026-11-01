# Aether Launcher

**A modern, lightweight, and customizable Minecraft: Java Edition launcher.**

Aether is an independent Minecraft launcher currently in active development. Built with Rust, Tauri 2, Svelte, and TypeScript, the project aims to provide a fast, reliable, and user-friendly experience for Minecraft Java Edition players.

Our goal is to combine a clean, modern desktop interface with powerful instance management, modding support, performance optimizations, and optional in-game customization features.

## Features

### Launcher Foundation

- Modern desktop interface
- Minecraft version selection
- Official Minecraft metadata integration
- Game asset and library downloads
- Download integrity verification
- Java runtime detection and configuration
- Customizable memory allocation
- Minecraft installation and launch management
- Error handling and diagnostic logging

### Microsoft Authentication

Aether is designed to support secure authentication using Microsoft's official OAuth 2.0 device authorization flow.

The authentication implementation includes:

- Microsoft account sign-in
- Xbox Live and XSTS authentication
- Minecraft Services integration
- Minecraft Java Edition ownership verification
- Minecraft player profile retrieval
- Token refresh and logout

Aether does not collect or store Microsoft account passwords.

**Authentication status:** The authentication implementation has passed local automated tests. Live Microsoft/Minecraft authentication is still awaiting application approval and end-to-end verification.

### Planned Features

- Fabric, NeoForge, and Forge support
- Multiple isolated Minecraft instances
- Mod and modpack management
- Customizable launcher themes
- Performance profiles and optimizations
- Optional in-game HUD modules
- FPS, CPS, keystrokes, and armor displays
- Customizable waypoints
- Integrated HUD editor
- Additional quality-of-life features

These features are part of the development roadmap and may change as the project progresses.

## Technology Stack

| Component | Technology |
|---|---|
| Desktop framework | Tauri 2 |
| Backend | Rust |
| Frontend | Svelte |
| Language | TypeScript |
| Build tooling | Vite |
| Minecraft integration | Java Edition |
| Planned client extensions | Java / Fabric |

## Development Status

**Status: Active Development — Pre-Release**

The project has successfully passed initial compilation, frontend integration, automated regression tests, and Minecraft installation checks.

The following milestones are still pending:

- Live Microsoft account authentication
- Minecraft API application approval
- End-to-end ownership verification
- Verified gameplay launch
- Production-ready credential persistence
- Public release preparation

Aether is not yet considered a fully playable or production-ready Minecraft launcher.

## Security and Account Ownership

Aether is committed to using legitimate Microsoft and Minecraft authentication mechanisms.

The launcher is designed to:

- Authenticate users through Microsoft's official authorization endpoints
- Verify Minecraft Java Edition ownership
- Avoid collecting Microsoft account passwords
- Prevent unauthorized game launches
- Protect account credentials
- Respect Microsoft and Mojang authentication requirements

Persistent secure credential storage is planned and remains under development.

## Project Goals

Our priorities are:

1. Deliver a reliable and fully functional Vanilla Minecraft launcher.
2. Complete secure Microsoft authentication and ownership verification.
3. Implement flexible instance and modloader management.
4. Optimize launcher performance and stability.
5. Introduce customizable Minecraft client features.
6. Provide a polished and accessible user experience.

## Minecraft API Access

Aether requires Microsoft OAuth application registration and appropriate Minecraft Services API access to authenticate players and verify Minecraft Java Edition ownership.

The project is pursuing authorization for its own registered application.

No third-party launcher credentials or unofficial authentication bypasses are used.

## Disclaimer

Aether Launcher is an independent, unofficial project.

**Aether is not affiliated with, endorsed by, sponsored by, or associated with Mojang Studios, Microsoft Corporation, or Xbox.**

Minecraft, Minecraft: Java Edition, Mojang, and Microsoft are trademarks of their respective owners.

Aether does not distribute Minecraft game files independently. Game files are intended to be downloaded from official sources, and users must own a valid Minecraft Java Edition license to play.

---

**Aether Launcher — Built for a better Minecraft experience.**
