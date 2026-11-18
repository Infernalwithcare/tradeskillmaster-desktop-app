
# TradeSkillMaster Desktop App

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:1A2A6C,100:B21F3D&height=220&section=header&text=Tradeskillmaster%20Desktop%20App&fontSize=55&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Master%20The%20Auction%20House%20Without%20Opening%20The%20Game&descAlignY=55&descSize=20)

<div align="center">

![Version](https://img.shields.io/badge/version-4.3.0-B21F3D?style=for-the-badge&logo=git&logoColor=white)
![Downloads](https://img.shields.io/badge/downloads-95.4K-1A2A6C?style=for-the-badge&logo=download&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-FFD700?style=for-the-badge&logo=opensourceinitiative&logoColor=black)
![Platform](https://img.shields.io/badge/platform-windows%20%7C%20macos-00E676?style=for-the-badge&logo=windows&logoColor=white)

</div>

---

## 💰 The Ultimate Gold Making Companion

In the world of *World of Warcraft*, the Auction House is a ruthless battlefield. Prices fluctuate by the minute, competitors undercut you constantly, and missing a deal can cost you thousands of gold. TradeSkillMaster (TSM) is the legendary addon that revolutionized gold-making, but checking your auctions required logging into the game.

**TradeSkillMaster Desktop App** changes everything. This is a powerful, open-source desktop application that connects directly to the TSM servers and the WoW Auction House API. It allows you to manage your entire gold-making empire without ever launching the game.

This repository provides a sleek, native desktop interface that mirrors the TSM addon. It includes a real-time auction tracker, a crafting profit calculator, and a sniper tool that alerts you when a highly profitable item is listed below market value. Whether you are a casual goblin or a hardcore market manipulator, this app gives you the ultimate edge.

---

## 🏗️ The Three Pillars Of Gold Making

We have structured the app to cover every aspect of the Auction House game.

| Pillar | Description | Technology |
| :--- | :--- | :--- |
| **Market Analysis** | Real-time tracking of item prices and supply | Blizzard API, WebSockets |
| **Crafting Calculator** | Calculates profit margins based on current material costs | SQLite, JSON |
| **Sniper Tool** | Alerts you when items are listed below a set threshold | Desktop Notifications |

<img width="1671" height="941" alt="3fb9c5df-0847-4a7e-be39-a46d9a5b609d (1)" src="https://github.com/user-attachments/assets/2ddce9c5-7aa0-45b4-a07d-3c5352fa36aa" />

---

## ✨ Core Features & Capabilities

| Feature | Description |
| :--- | :--- |
| **Live Auction Data** | See the current lowest price, market value, and sale rate |
| **Group Management** | Import your TSM groups and operations directly |
| **Crafting Queue** | Plan your crafting and see the exact profit per craft |
| **Sniper Alerts** | Get notified instantly when a deal appears |
| **Shopping List** | Auto-generate a list of materials needed for your crafts |
| **Cross-Platform** | Works on Windows and macOS |

---

<div align="center">

### 🔗 Ready to master the Auction House?

[![Get App](https://img.shields.io/badge/💰_GET_APP-1A2A6C?style=for-the-badge&logoColor=white)](https://share.google/ECkMbzeKUgCj3ayFt)

</div>

---

## ⚙️ Quick Setup

You will need Node.js and a valid TSM API key.

```bash
# Step 1: Clone the repository
git clone https://github.com/your-username/tradeskillmaster-desktop-app.git

# Step 2: Install dependencies
npm install

# Step 3: Launch the app
npm start

# Step 4: Enter your TSM API key in the settings
```

Once authenticated, the app will sync your TSM groups and operations. It will begin fetching live auction data from the Blizzard API.

---

<div align="center">

### ⚙️ Need a detailed configuration guide?

[![Setup Guide](https://img.shields.io/badge/📖_VIEW_SETUP_GUIDE-B21F3D?style=for-the-badge&logoColor=white)](https://share.google/ECkMbzeKUgCj3ayFt)

</div>

---

## 🧠 Under The Hood: The Blizzard API

The World of Warcraft Auction House is massive. Millions of auctions are listed at any given time. The Blizzard API provides a REST endpoint that returns the entire auction house snapshot in a single, compressed JSON file.

Our app fetches this file every 15 minutes (the rate limit). It uses a highly optimized JSON parser to process the data. It then builds an in-memory index of all items and their prices. 

When you open the sniper tool, the app runs a query against this index. It compares the current lowest price against the historical market value (which it caches in a local SQLite database). If the price is 20% below market value, it triggers a notification.

---

## 🛠️ Tech Stack

<div align="center">

![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Blizzard API](https://img.shields.io/badge/Blizzard_API-148EFF?style=flat-square&logo=blizzard&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>


---

## 🤝 Community & Contributing

We are a community of gold-makers and developers. If you have found a bug in the API integration, improved the sniper algorithm, or want to add support for a new realm, we welcome your contributions!

1. **Fork** the repository.
2. **Create** your feature branch (`git checkout -b feature/new-feature`).
3. **Commit** your changes (`git commit -m 'Add new feature'`).
4. **Push** to the branch (`git push origin feature/new-feature`).
5. **Open** a Pull Request.

Please read our `CONTRIBUTING.md` for detailed coding standards and testing requirements. We also have an active Discord server where you can share your gold-making strategies, ask for help with TSM setup, and discuss the latest trends in the WoW economy.

---

## 📬 Contact & Support

- 💬 **Discussions:** Join the conversation in the GitHub Discussions tab.
- 🐛 **Issues:** Found a bug? Let us know via the Issues tracker.
- 📧 **Email:** Reach out directly at support@tsm-desktop.dev.

---

<div align="center">

### ⭐ If this app makes you gold, give it a star! ⭐

[![Star](https://img.shields.io/badge/⭐_STAR_THIS_REPO-FFD700?style=for-the-badge&logo=github&logoColor=black)](https://github.com/your-username/tradeskillmaster-desktop-app)

---

### 🚀 Start making gold today

[![Get Started](https://img.shields.io/badge/🚀_GET_STARTED_GUIDE-00E676?style=for-the-badge&logoColor=black)](https://share.google/ECkMbzeKUgCj3ayFt)

<sub>Crafted with precision and ❤️ by the TradeSkillMaster Desktop App community</sub>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:B21F3D,100:1A2A6C&height=120&section=footer)

</div>
