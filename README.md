Enhance your Minecraft experience with a powerful RPG-style title system that allows players to earn, manage, and display custom titles both above their heads and in chat.
Perfect for RPG servers, roleplay, factions, progression-based gameplay, or any server that wants more identity and immersion.

✨ Features
• Fully custom player titles – titles are not hardcoded and can be any text
• Players can own multiple titles and choose one active title
• Titles support spaces and Minecraft color codes (§ or &)
• Titles are displayed above player names in-game
• Titles can optionally appear as chat prefixes
• Each title can have a custom description (shown on hover in chat)
• Titles and selections are saved persistently (survive relogs and restarts)
• Fully customizable chat format with placeholders
• Works in singleplayer and multiplayer (server-friendly)

📝 Title Descriptions
Each title can have an optional description, for example:

“Granted for killing a legendary boss”
“Reward for completing a dungeon”

When chat prefixes are enabled, hovering over a title in chat will display its description.
Perfect for achievements, lore, or progression systems.

💬 Chat Integration
• Titles can be displayed as chat prefixes
• Chat prefix system can be enabled or disabled globally by admins
• Chat formatting is fully server-controlled when enabled
• Hovering over titles in chat shows their description
• Clean rendering without duplicated player names

🧩 Custom Chat Format
The chat format is fully configurable using placeholders:

• {title} – player’s active title (with hover description)
• {player} – player name
• {message} – chat message content

Default format:
[{title}] <{player}>: {message}

Admins can view or change the format directly in-game.
If chat prefixes are disabled, the server automatically falls back to vanilla chat formatting.

🎮 Commands
Admin Commands
/rtitle grant <player> "<title>"
Grants a custom title to a player.

/rtitle grant <player> "<title>" desc <description>
Grants a custom title with an optional description (shown on hover in chat).

/rtitle revoke <player> "<title>"
Removes a title from a player

/rtitle set <player> <title>
Sets one of the player’s owned titles as their active title.
Tab-completion suggests only titles that the target player actually owns.

/rtitle chatprefix on
Enables title prefixes in chat

/rtitle chatprefix off
Disables title prefixes in chat

/rtitle chatformat
Shows the current chat format and available placeholders

/rtitle chatformat <format>
Sets a new chat format.
Available placeholders: {title}, {player}, {message}.
If a player has no active title, the title part is automatically hidden.

Player Commands
/rtitle display <title>
Sets one of your owned titles as active

/rtitle hide
Hides your active title

/rtitle list
Shows all titles you own

🎨 Color & Formatting
Titles support Minecraft formatting codes using & or §:

• &1 Dark Blue
• &4 Dark Red
• &e Yellow
• &l Bold
• &o Italic
• &n Underline

Examples:

&6[&eKing&6] → [King] (gold/yellow)
&cHero &7of &aNature → Hero of Nature
&9★ &bMage &9★ → ★ Mage ★

🔧 Compatibility
• Minecraft 1.20.1 (Forge) and Minecraft 1.21.1 (NeoForge) BETA
• Client & Server compatible
• Works in singleplayer and multiplayer
• Designed to work alongside other mods
