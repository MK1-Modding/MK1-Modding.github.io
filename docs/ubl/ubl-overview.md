# 🔷 UBL Framework Overview (WIP)

The **Universal Blueprint Loader (UBL)** is a powerful framework that allows **actor blueprint mods** to dynamically interact with the game. It achieves this by:

- **Loading** actor blueprint mods into the game.
- **Processing custom Blueprint events** triggered within mods.
- **Handling event logic** through **UE4SS Lua scripts** (**UBLScripts**).

By combining **Unreal Engine Blueprints** with the flexibility of **Lua scripting**, UBL provides a robust system for creating **advanced mod interactions that were previously unattainable**.

---
## 🔹 What are UBL Events?

UBL introduces a **list of custom Blueprint events** that can be used in **Actor Blueprint mods**. These events act as triggers inside Unreal Engine Blueprints and are processed by **UBLScripts** (UE4SS Lua scripts) to execute game modifications.

### **📌 UBL Event Workflow**
1. **Blueprint Event is Triggered** → Inside an **Unreal Engine Blueprint**.
2. **UBLScript Handles the Event** → Processes the logic via **UE4SS Lua scripts**.
3. **Mod Behavior Executes** → Changes occur dynamically in-game.

---
## 📖 **UBL Event Format & Usage** (WIP)

All UBL Events in this documentation follow a **standardized format** to ensure consistency.

🚧 **This section is still in progress!** 🚧  
More details on event structure and usage will be added soon.

---
## 📖 Key Guides in This Section (WIP)
- 🔹 [UBL Basics: How It Works](ubl-basics.md) – Understanding the core concept.
- 🔹 [UBL Event List](event-list.md) – Full reference of all available events.
- 🔹 [Creating & Using UBL Events](using-ubl-events.md) – How to integrate them into your mods.
- 🔹 [Advanced UBL Scripting](advanced-ubl.md) – Handling complex interactions.

## ⏭️ Next Steps
If you're new to UBL, start with the **[UBL Basics Guide](ubl-basics.md)**.

---
💡 **Tip:** Bookmark the [UBL Event List](event-list.md) as a quick reference!
