# AntiDupe & Anti-Exploit System

AntiDupe is a high-performance, enterprise-grade Skript designed to prevent inventory-related exploits, item duplication glitches (Types A through E), and unauthorized actions while inventories or containers are open.

---

## What AntiDupe Does
AntiDupe continuously monitors player states and packets to ensure absolute server integrity. Key protections include:
* **Type A & B (Movement Protection)**: Detects and flags excessive movement while a player inventory or a container (chest, shulker box, etc.) is open.
* **Type C & D (Chat & Command Blocking)**: Cancels commands and chat messages sent while interacting with inventories or containers.
* **Type E (Combat Mitigation)**: Prevents players from attacking entities or targets while having an active inventory open.
* **Smart GUI & Desync Handling**: Fully compatible with custom GUIs and plugin menus, featuring an advanced grace period and background synchronization to completely eliminate false positives.
* **Automated Updates**: Integrated GitHub API checking to notify admins of newer releases.
* **In-Game Control Center**: Easily manage prefixes, permissions, and system statuses via `/antidupe` or `/adp` (OP only).

---

## Requirements & Dependencies
To run AntiDupe successfully on your Minecraft server, make sure you have the following installed:
1. **Minecraft Server**: Paper / Purpur (recommended for optimal performance).
2. **Skript**: The core Skript plugin by Matocolotoi / Bensku.
3. **skript-reflect** (Recommended for advanced packet handling and stability).
4. **SkBee** (Required for robust command tab completion support).

---

## AntiDupe PREMIUM Version
Looking for the ultimate protection? Upgrade to **AntiDupe Premium** to unlock advanced blocks and total server security!

### Premium Features:
* **Type Y Check**: Instantly blocks, cancels, and flags any attempt to break or interact with blocks while an inventory is open.
* **Type Z Check**: Completely controls and restricts any entity interactions (villagers, armor stands, item frames, etc.) while an inventory is open.
* **Custom Violation Logs**: Automatically records and tracks all player violation flags (with timestamps, ping, and types) accessible via `/antidupe logs <player>`.
* Priority support and exclusive updates.

### How to Get Premium:
You can unlock the Premium version through one of the following methods:
1. **Discord Server Boost**: Boost our official Discord server to get lifetime access to the Premium version for free!
2. **Direct Purchase**: Buy it directly from the owner for just **€2.00 EUR**.

👉 **[Join our Official Discord Server to get Premium!] [discord](https://discord.gg/SCfk2SsXrd)**

---

## Installation
1. Download the latest `.sk` file from the [Releases](https://github.com/colle23-skript/AntiDupe/releases) tab.
2. Place the file inside your `plugins/Skript/scripts/` folder.
3. Run `/skript reload <filename>` or restart your server.
4. Enjoy a secure, dupe-free server environment!
