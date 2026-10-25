
---

# InvGuard — Ultimate Anti-Exploit & InvWalk System

**InvGuard** is a high-performance, enterprise-grade Skript designed to prevent inventory-related exploits, item duplication glitches, and unauthorized actions while inventories, containers, or custom GUIs are open. Built with zero disk-write overhead (volatile RAM tracking), it keeps your server lightning fast while securing it against modern client-side exploits and desync tools.

---

## Core Protections & Checks

InvGuard monitors player states and packets to ensure absolute server integrity. Key protections include:

* **Type A & B (InvWalk Protection)**: Detects and flags excessive movement while a personal inventory or a container (chest, shulker box, etc.) is open.
* **Type C & D (Chat & Command Blocking)**: Cancels commands and chat messages sent while interacting with inventories or containers.
* **Type E (Combat Mitigation)**: Prevents players from attacking entities or targets while having an active inventory open.
* **Type F (Container Reach / TP Dupe)**: Blocks inventory manipulation if a player teleports away or gets further than 6.5 blocks from the opened container (e.g., via Enderpearls).
* **Type G (Portal & Death Dupe)**: Prevents opening inventories or interacting with containers while inside Nether/End portals or upon death.
* **Type H & I (Desync & Packet Exploits)**: Advanced protection against modern client-side desync utilities (like UI-Utils *Desync* and *Close without Packet*), automatically cleaning up ghost items and desynced slots.
* **Type M (Packet Burst / Macro Check)**: Intelligent click-rate limiter that blocks autoclickers and packet spam without interfering with legitimate double-clicks or fast shift-clicks.
* **Type Y & Z (World & Entity Interaction Blocks)**: Instantly cancels and flags attempts to break blocks, interact with blocks, or click entities (villagers, armor stands, etc.) while an inventory is open.
* **Dynamic Ping Compensation**: Automatically applies grace periods and buffer thresholds for high-ping players or spoofers to completely eliminate false positives.

---

## Requirements & Dependencies

To run InvGuard successfully on your Minecraft server, make sure you have:

1. **Minecraft Server**: Paper / Purpur 1.21+ (recommended for optimal performance).
2. **Skript**: The core Skript plugin.
3. **No heavy addons required!** (InvGuard is 100% native Vanilla Skript compatible).

---

## Free vs. PRO Version

Choose the right protection level for your server community:

| Feature / Check | Free Version | PRO Version (€2.00 EUR) |
| --- | --- | --- |
| **Core Checks (A to G)** | ✅ Included | ✅ Included |
| **Desync & Packet Checks (H, I, M)** | ✅ Included | ✅ Included |
| **Block & Entity Checks (Y, Z)** | ✅ Included | ✅ Included |
| **In-Game Control Center GUI (`/ig`)** | ❌ | ✅ Included |
| **Custom Prefix & Permission Nodes** | ❌ | ✅ Included |
| **Persistent Player Violation Logs (`/ig logs`)** | ❌ | ✅ Included |

---

## How to Get InvGuard PRO (€2.00)

You can unlock the full **PRO** version and support future updates through our official community:

👉 **[Click here to join our Discord Server and get PRO!](https://discord.gg/SCfk2SsXrd)** *(Available for just **€2.00 EUR** or via community perks)*

---

## Installation Instructions

1. Download the `.sk` file (Free or PRO) from the [Releases](https://www.google.com/search?q=https://github.com/colle23-skript/InvGuard/releases) tab.
2. Place the file inside your `plugins/Skript/scripts/` folder.
3. Run `/sk reload <filename>` or restart your server.
4. Enjoy a secure, dupe-free server environment!
