<div align="center">

  # 🎮 Local Prod

  ![Minecraft Version](https://img.shields.io/badge/Minecraft-26.2%20--%201.21.x-green?style=for-the-badge&logo=minecraft)
  ![Server Core](https://img.shields.io/badge/Server-Paper%20%2F%20Velocity-orange?style=for-the-badge)
  ![Build Tool](https://img.shields.io/badge/Build-Maven-blue?style=for-the-badge)

</div>

---

## 📦 Plugins

| Plugin | Description | Platform | Maintained By |
| :--- | :--- | :---: | :---: |
| [**`AlexCore`**](https://github.com/Local-Prod/AlexCore) | Core plugin for Staff/Admin/Media channels, dual Discord bridge, dynamic emojis, and mentions. | `Paper` | [@Alexxxander0](https://github.com/Alexxxander0) |
| [**`AlexPack`**](https://github.com/Local-Prod/AlexPack) | Velocity proxy resource pack merger, internal HTTP web server, and Geyser integration. | `Velocity` | [@Alexxxander0](https://github.com/Alexxxander0) |
| [**`AlexJobs`**](https://github.com/Local-Prod/AlexJobs) | Jobs, economy, and player progression framework with anti-abuse protection. | `Paper` | [@Alexxxander0](https://github.com/Alexxxander0) |
| [**`AlexAuctionHouse`**](https://github.com/Local-Prod/AlexAuctionHouse) | High-performance player-to-player auction house with Shulker preview and claim box. | `Paper` | [@Alexxxander0](https://github.com/Alexxxander0) |
| [**`AlexAFK`**](https://github.com/Local-Prod/AlexAFK) | Automated AFK arena management, time-based rewards, and particle boundary outlines. | `Paper` | [@Alexxxander0](https://github.com/Alexxxander0) |
| [**`DeltaScheduler`**](https://github.com/Delta-Prod/DeltaScheduler) | Multilingual automated task scheduling with PlaceholderAPI cache and 21 languages. | `Paper` | [@Alexxxander0](https://github.com/Alexxxander0) |
| [**`CoreProtect`**](https://github.com/Delta-Prod/CoreProtect) | Custom 26.2 build of block logging and anti-griefing tool with TabCompletion QoL fixes. | `Paper / Spigot` | [@Alexxxander0](https://github.com/Alexxxander0) |
| [**`DeltaAntiVPN`**](https://github.com/Delta-Prod/DeltaAntiVPN) | Real-time Anti-VPN, proxy detection, and ASN verification with dual-layer caching. | `Paper` | [@Alexxxander0](https://github.com/Alexxxander0) |
| [**`DeltaIslands`**](https://github.com/Delta-Prod/DeltaIslands) | Island management, custom schematics, grid generation, upgrades, and member roles. | `Paper` | [@Alexxxander0](https://github.com/Alexxxander0) |
| [**`DeltaEvents`**](https://github.com/Delta-Prod/DeltaEvents) | Competitive multiplayer mini-games manager (Sumo, KOTH, MrBeast, FiveM). | `Paper` | [@Alexxxander0](https://github.com/Alexxxander0) |
| [**`XaeroDisabler`**](https://github.com/Delta-Prod/XaeroDisabler) | Security plugin to disable unauthorized radar and cave mapping in client mods. | `Paper` | [@Alexxxander0](https://github.com/Alexxxander0) |
| [**`DeltaParcel`**](https://github.com/Delta-Prod/DeltaParcel) | Enterprise land claiming, parcel management, and plot protection system. | `Paper` | [@Alexxxander0](https://github.com/Alexxxander0) |

---

## ⚡ Workflow & Development Instructions:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Delta-Prod/<RepositoryName>
   ```

2. **Apply necessary code changes locally.**

3. **Build the `.jar` artifact:**
   ```bash
   mvn clean package
   ```

4. **Push changes & create a Release:**
   Commit and push your changes with clear English commit messages. Create a new GitHub Release containing the compiled `.jar` artifact and release notes following the organization release standard.
