# 🧭 Compass Cleaner

### ✨ What It Does

Tired of magnetized or renamed compasses cluttering your inventory once they're no longer needed?  
**Compass Cleaner** is a tiny but handy mod that lets you **fully reset compasses** via a **simple shapeless crafting recipe** — removing any lodestone binding, custom name, or other NBT data:

```
Input:  [Magnetized Compass]  
Output: [Clean Compass]
```

No paper, no tools, no extra steps — just drop it into the crafting grid and it's reset to a normal compass.

---

### 🧩 Why Use It?

- ✅ **No more confusion** between active and obsolete compasses  
- ✅ **Minimalist** — no new items, no GUI, no configs  
- ✅ **Vanilla-friendly** design and recipe  
- ✅ **Client/server compatible**  
- ✅ Ideal for mods using magnetized compasses (e.g., for teleportation, loot tracking, dimension anchors, etc.)

---

### 📦 Recipe

```json
{
  "type": "minecraft:crafting_shapeless",
  "group": "compass",
  "ingredients": [
    "minecraft:compass"
  ],
  "result": {
    "count": 1,
    "id": "minecraft:compass"
  }
}
```

### 💡 Technical Notes

- The recipe simply returns a clean compass with default NBT.
- It works with any compass item, regardless of how it was previously used or tagged.

---

# 🛠️ Installation and Technical Information

## Installation
- Make sure you have **Minecraft 1.21.1**, **1.21.4** or **1.21.5** with **NeoForge** installed.
- Download the mod `.jar` file.
- Place it into your `mods` folder.
- Launch the game and enjoy your adventure!

## Technical Details
- **Developer:** Sergey Pekarchik
- **Supported NeoForge versions:** 1.21.1, 1.21.4 and 1.21.5
- **Source Code:** [GitHub Repository](https://github.com/spekarchik/CompassCleaner)

---

## 🧩 Related Mods

Pouch & Paper is fully compatible with the following mods by the same author:

- **[🔧 EnchantOnce](https://www.curseforge.com/minecraft/mc-mods/enchantonce)** — a minimalistic but powerful rework of enchanting and repairing.  
  Fixed XP costs, enchanted book duplication, material-based repairs, and perfect gear cloning — all with vanilla-style mechanics.  
  Fully supports custom gear and enchantments from The Block of Angel mod.

- **[🌟 Pouch & Paper](https://www.curseforge.com/minecraft/mc-mods/pouch-and-paper)** — introduces compact forms of tradeable resources for easier storage and trading:  
  • paper (stackable and block form),  
  • ink and glow ink (bottled),  
  • leather (bundled),  
  • seeds (in pouches),  
  • feathers (as compact packs).  
  Includes the *Burnt Paper Block* — crafted by setting a Paper Block on fire. It attracts creepers and repels bees, perfect for traps and moody builds.

- **[🌟 The Block of Angel](https://www.curseforge.com/minecraft/mc-mods/angel-block-mod)**
  An exploration-focused mod that rewards curiosity and reduces repetitive grind — while keeping the core survival balance intact. Perfect for players who want each discovery to matter.
  Start with almost nothing — earn every shortcut.  
  This mod transforms Minecraft into a world of meaningful adventure and artifact-driven progression. No grind, no farms — just clever tools, dangerous dungeons, and rewards you must conquer.

  • Progression-focused gameplay: leather armor, stone weapons, and real survival.  
  • Unique tools: magnetic rods, precision builders, instant crop planters.  
  • Legendary gear: 6 armor sets, powerful weapons, and upgrade paths.  
  • Angel Block & Rod: sacred artifacts that protect and purify your world.  
  • No custom UIs — pure, immersive gameplay.

  Ideal for adventurers who want to *explore*, *survive*, and *earn* their power — not dig tunnels forever.

---

## ☕ Support Development

If you enjoy the mod and would like to support future updates and new features, you can support me here:  
[Buy me a coffee on Ko-fi!](https://ko-fi.com/sergeypekarchik)

Your support means a lot and helps me dedicate more time to creating new content and improving the mod! ❤️

---
