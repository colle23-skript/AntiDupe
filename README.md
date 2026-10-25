# InvGuard (AntiDupe & InvWalk PRO)

InvGuard is an advanced, high-performance anti-exploit Skript designed to prevent inventory-related exploits, item duplication glitches, and unauthorized actions while inventories, containers, or custom GUIs are open. Built with zero disk-write overhead (volatile RAM tracking), it keeps your server lightning fast while securing it against modern client-side exploits and desync tools.

---

## Core Protections & Checks

InvGuard continuously monitors player states and packets to ensure absolute server integrity. Key protections include:
* **Type A & B (InvWalk Protection):** Detects and flags excessive movement while a personal inventory or a container (chest, shulker box, etc.) is open.
* **Type C & D (Chat & Command Blocking):** Cancels commands and chat messages sent while interacting with inventories or containers.
* **Type E (Combat Mitigation):** Prevents players from attacking entities or targets while having an active inventory open.
* **Type F (Container Reach / TP Dupe):** Blocks inventory manipulation if a player teleports away or gets further than 6.5 blocks from the opened container.
* **Type G (Portal & Death Dupe):** Prevents opening inventories or interacting with containers while inside Nether/End portals or upon death.
* **Type H & I (Desync & Packet Exploits):** Advanced protection against client-side desync utilities (like UI-Utils *Desync* and *Close without Packet*), automatically cleaning up ghost items.
* **Type M (Packet Burst / Macro Check):** Intelligent click-rate limiter that blocks autoclickers and packet spam without interfering with legitimate double-clicks or fast shift-clicks.
* **Type Y & Z (PRO Only - World & Entity Interaction Blocks):** Instantly cancels and flags attempts to break blocks or click entities while an inventory is open.
* **Dynamic Ping Compensation:** Automatically applies grace periods and buffer thresholds for high-ping players or spoofers to completely eliminate false positives.

---

## Free vs. PRO Version

| Feature / Check | Free Version | PRO Version (€2.00 EUR) |
| :--- | :---: | :---: |
| **Core Checks (A to G, H, I, M)** | Included | Included |
| **Block & Entity Checks (Y, Z)** | Not Included (PRO Only) | Included |
| **In-Game Control Center GUI (`/ig`)** | Not Included | Included |
| **Custom Prefix & Permission Nodes** | Not Included | Included |
| **Persistent Player Violation Logs (`/ig logs`)** | Not Included | Included |

---

## How to Get InvGuard PRO (€2.00)

You can unlock the full **PRO** version and support future updates through our official community:

👉 **[Join our Discord Server to get PRO!](https://discord.gg/SCfk2SsXrd)** *(Available for just **€2.00 EUR**)*

---

## Installation Instructions

1. Download the `.sk` file (Free or PRO) from the [Releases](https://github.com/colle23-skript/InvGuard/releases) tab.
2. Place the file inside your `plugins/Skript/scripts/` folder.
3. Run `/sk reload <filename>` or restart your server.
4. Enjoy a secure, dupe-free server environment!
