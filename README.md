# 🔥 BruLive - TNT Coin Relay

**TikTok Live → Minecraft Bedrock**, running 100% on Android with no PC or external server required.

BruLive is an Android app that connects your TikTok Live directly to Minecraft Bedrock in real time. Every gift, like, follow, and chat message from your TikTok viewers can trigger in-game actions — perfect for Minecraft streamers who want to make their live streams more interactive.

## ✨ Features

- **TikTok Live to Minecraft Relay** — chat, gifts, likes, and follows are relayed in real time into the game via the TNT Coin addon
- **Multiple game modes** — besides TNT Coin, additional modes are available such as **Sand Sweep** (clear a platform of sand while gifts can pile more sand on or drop TNT)
- **In-app dashboard** — monitor live status, gift/like/coin counters, and activity history directly from your phone
- **Membership & subscription system** — Member/VIP/Dev roles with an extendable active period
- **Game mode store** — unlock additional modes per user
- **Runs 100% on Android** — the Node.js server is embedded directly inside the APK (nodejs-mobile), no PC or separate hosting needed

## 🛠️ Tech Stack

- **Node.js** (nodejs-mobile) — embedded relay server inside the APK
- **tiktok-live-connector** — TikTok Live connection
- **WebSocket** — real-time bridge to Minecraft Bedrock
- **Kotlin (Android)** — native wrapper, Foreground Service, WebView
- **Supabase** — user authentication and data management
- **Minecraft Bedrock Script API** — interactive addons (TNT Coin, Sand Sweep, etc.)

## 📲 How to Use

1. Download the latest APK from the **[Releases](../../releases)** page
2. Install it on your Android device (enable "Install from unknown sources" if prompted)
3. Log in using the account provided by the admin
4. Enter your TikTok username (without `@`) in the **Live Control** field
5. Tap **Start Relay**
6. In Minecraft Bedrock, run `/connect localhost:3000` to connect the game

## 🎮 Minecraft Addon Setup

1. Enable **Beta APIs** in World Settings → Experiments
2. Import the addon behavior pack (TNT Coin / Sand Sweep) into Minecraft
3. Activate the pack for the world you're using
4. Run `/connect localhost:3000` once the BruLive relay is active

## ⚠️ Disclaimer

This project was built for personal/community streamer use. It is not an official TikTok or Mojang/Microsoft product.

## 📩 Contact

For questions about access or subscriptions, contact the admin through the contact info listed in the app.

---

Built with ❤️ by the BruLive team
