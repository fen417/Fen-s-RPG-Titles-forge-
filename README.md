# 🎭 RPG Title System

> Enhance your Minecraft experience with a powerful RPG-style title system that allows players to earn, manage, and display custom titles both above their heads and in chat.

Perfect for RPG servers, roleplay, factions, progression-based gameplay, or any server that wants more identity and immersion.

---

## ✨ Features

- **Fully custom player titles** – titles are not hardcoded and can be any text
- **Multiple titles per player** – players can own multiple titles and choose one active title
- **Rich formatting support** – titles support spaces and Minecraft color codes (`§` or `&`)
- **In-game display** – titles are displayed above player names
- **Chat integration** – titles can optionally appear as chat prefixes
- **Title descriptions** – each title can have a custom description (shown on hover in chat)
- **Persistent storage** – titles and selections survive relogs and restarts
- **Fully customizable chat format** with placeholders
- **Multiplayer ready** – works in singleplayer and multiplayer (server-friendly)

---

## 📝 Title Descriptions

Each title can have an optional description, for example:

- *"Granted for killing a legendary boss"*
- *"Reward for completing a dungeon"*

When chat prefixes are enabled, hovering over a title in chat will display its description.

**Perfect for achievements, lore, or progression systems.**

---

## 💬 Chat Integration

- ✅ Titles can be displayed as chat prefixes
- ✅ Chat prefix system can be enabled or disabled globally by admins
- ✅ Chat formatting is fully server-controlled when enabled
- ✅ Hovering over titles in chat shows their description
- ✅ Clean rendering without duplicated player names

---

## 🧩 Custom Chat Format

The chat format is fully configurable using placeholders:

| Placeholder | Description |
|------------|-------------|
| `{title}` | Player's active title (with hover description) |
| `{player}` | Player name |
| `{message}` | Chat message content |

**Default format:**
```
[{title}] <{player}>: {message}
```

Admins can view or change the format directly in-game.

> If chat prefixes are disabled, the server automatically falls back to vanilla chat formatting.

---

## 🎮 Commands

### 👑 Admin Commands

#### Grant a Title
```
/rtitle grant <player> "<title>"
```
Grants a custom title to a player.

#### Grant a Title with Description
```
/rtitle grant <player> "<title>" desc <description>
```
Grants a custom title with an optional description (shown on hover in chat).

#### Revoke a Title
```
/rtitle revoke <player> "<title>"
```
Removes a title from a player.

#### Set Active Title
```
/rtitle set <player> <title>
```
Sets one of the player's owned titles as their active title.

*Tab-completion suggests only titles that the target player actually owns.*

#### Toggle Chat Prefixes
```
/rtitle chatprefix on   # Enables title prefixes in chat
/rtitle chatprefix off  # Disables title prefixes in chat
```

#### Manage Chat Format
```
/rtitle chatformat                  # Shows current format and placeholders
/rtitle chatformat <format>         # Sets a new chat format
```

Available placeholders: `{title}`, `{player}`, `{message}`.

*If a player has no active title, the title part is automatically hidden.*

---

### 👤 Player Commands

#### Display a Title
```
/rtitle display <title>
```
Sets one of your owned titles as active.

#### Hide Your Title
```
/rtitle hide
```
Hides your active title.

#### List Your Titles
```
/rtitle list
```
Shows all titles you own.

---

## 🎨 Color & Formatting

Titles support Minecraft formatting codes using `&` or `§`:

| Code | Effect | Code | Effect |
|------|--------|------|--------|
| `&1` | Dark Blue | `&l` | **Bold** |
| `&4` | Dark Red | `&o` | *Italic* |
| `&e` | Yellow | `&n` | <u>Underline</u> |

### Examples

```
&6[&eKing&6]              → [King] (gold/yellow)
&cHero &7of &aNature      → Hero of Nature
&9★ &bMage &9★            → ★ Mage ★
```

---

## 🔧 Compatibility

| Platform | Version | Status |
|----------|---------|--------|
| **Forge** | 1.20.1 | ✅ Stable |
| **NeoForge** | 1.21.1 | 🧪 BETA |

- ✅ Client & Server compatible
- ✅ Works in singleplayer and multiplayer
- ✅ Designed to work alongside other mods

---

## 📦 Installation

1. Download the latest release from the [Releases](../../releases) page
2. Place the `.jar` file in your `mods` folder
3. Launch Minecraft with Forge/NeoForge
4. Enjoy!

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

---

## 📄 License

[Insert your license here]

---

<div align="center">

**Made with ❤️ for the Minecraft community**

[Report Bug](../../issues) · [Request Feature](../../issues)

</div>
