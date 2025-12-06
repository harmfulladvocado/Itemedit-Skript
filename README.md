# Itemedit-Skript

A **powerful Skript version of the "ItemEdit" plugin** for Minecraft servers. Provides advanced in-game item editing with tons of customization for administrators, content creators, and server players.

---

## ▶️ What Is It?

**Itemedit-Skript** is a Skript-based reimplementation of the classic [ItemEdit plugin](https://www.spigotmc.org/resources/itemedit-1-8-x-1-21-x.40993/) for Minecraft (1.8.x – 1.21.x). It lets you customize nearly any item property directly in-game via simple commands. It brings the flexibility of NBT and attribute/item editing to non-plugin Skript users, with quality-of-life features such as GUIs and tab completion.

- **No custom jar needed, just Skript!**
- Ideal for custom servers, minigames, adventure maps, and more

---

## 🎯 Features

- **Item Attribute Editing** (all vanilla attributes)
- **Renaming (with color support)**
- **Potion Effect Editing** (add/remove/custom effects & duration)
- **Leather Armor Coloring**
- **Compass/Book Author/Unbreakable Toggle**
- **Set Amount & Max Stack Size**
- **Enchantments (add, remove, clear)**
- **Durability (set/max)**
- **Fire Resistant Toggle & Visual Glow**
- **Firework Power Setting**
- **Hide/Show Flags** (enchantments, attributes, etc.)
- **Repair Cost Editor**
- **Skull Owner/Spawn Eggs**
- **Lore Editor (add/remove/clear)**
- **Item Model & Type**
- **Server Items** (save, give, take, list, edit, sell & buy with GUI!)
- **Tab-Completion for all commands**
- **Custom messages and feedback**

> Full, detailed feature list in [the Spigot resource](https://www.spigotmc.org/resources/itemedit-skript.128574/)

---

## 📦 Dependencies

- [**Skript**](https://github.com/SkriptLang/Skript) (core)
- [**SkBee**](https://github.com/ShaneBeee/SkBee) (NBT utils, advanced item editing)
- [**SkCrew**](https://github.com/IdkPro754/Skcrew) (for modern item and attribute features)

Install all dependencies into your `/plugins` folder and reload your server before adding Itemedit-Skript.

---

## 💡 Usage Examples

**Rename an item**  
`/ie rename MyCoolSword`

**Set lore**  
`/ie lore add &6Epic Sword`

**Add knockback resistance (all slots)**  
`/ie attribute add knockback_resistance 1`

**Set item to unbreakable**  
`/ie unbreakable true`

**Add Sharpness V enchantment**  
`/ie enchant sharpness 5`

**Potion effect**  
`/ie potioneffect add speed 3 60 s`

**Server item system** (save/give/list custom admin items)
```
/serveritem save legendary_sword
/serveritem give legendary_sword PlayerName
/serveritem list
```

See all commands and usages via tab completion in-game or the script source.

---

## 🔒 Permissions

- All item edit features require: `skript.itemedit`
- Server item features: `skript.serveritem`

> Make sure only trusted admins or staff have access!

---

## 🧑‍💻 Credits & Info

- Ported/written by: **hrmfullAdvocado**
- **Original ItemEdit plugin by [emanondev]([https://www.spigotmc.org/resources/itemedit-1-8-x-1-21-x.40993/](https://github.com/emanondev))**
- [Permission message for Skript port](https://discord.com/channels/438120634640498690/815511174686572586/1412093889434882188)

---

## 🌐 Links

- **Support & Updates Discord:** [Join here](https://discord.gg/gmyNJMRZfJ)
- **Original plugin:** [ItemEdit (Jar)](https://www.spigotmc.org/resources/itemedit-1-8-x-1-21-x.40993/)
- **Skript version:** [Spigot Page](https://www.spigotmc.org/resources/itemedit-skript.128574/)

---

## 📝 License / Usage

- You must have permission from original plugin authors for redistribution.
- Do not resell. Do not claim as your own.
- Give feedback and suggestions on Discord!

---
