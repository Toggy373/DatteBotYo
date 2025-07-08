# DatteBotYo
DatteBotYo is a full-service Discord bot built for Naruto 5E campaigns. It's designed to streamline character management, automate combat rolls, and give players quick access to jutsu and feats, all while syncing directly with Google Sheets and a MySQL database.

Here’s a breakdown of what it brings to the table:

🧠 Character Sheet Integration
DatteBotYo links directly to a Google Sheet using a secure import system. Once connected, it pulls in all relevant stats, abilities, saves, skills, attack bonuses, chakra, HP, and even your sheet's thumbnail image. This data is stored and managed through a MySQL database, allowing players to switch between characters, update stats, and carry their data across sessions.

🪙 Resource Tracking
The bot tracks key resources like Ryo and Downtime directly through the database. You can add or subtract values with simple commands, and it will validate that you never go below zero. You can also fetch a clean readout of a character's current totals at any time.

⚔️ Combat Automation
DatteBotYo streamlines combat by pulling your character’s attack bonuses directly from your sheet. You can roll for Ninjutsu, Genjutsu, or Taijutsu attacks with a single command, while still applying modifiers like bonus dice, flat bonuses, and advantage or disadvantage.
Saving throws and skill checks work the same way. If you enter a stat or skill slightly wrong, the bot uses intelligent matching to find what you meant and proceeds accordingly.

🎲 Advanced Dice Engine
The dice roller behind DatteBotYo is robust. It supports:

Exploding dice (rolls again when max value is hit)
Rerolls (once or until you beat a threshold)
Minimum value enforcement
Complex arithmetic (like (2d6+1d4)*2)
Advantage/disadvantage on d20s
Rolling the same expression multiple times with automatic summaries

📘 Jutsu and Feat Lookup
The bot connects to a database containing all jutsu and feats. You can search using partial names, and if multiple results come up, it prompts you to choose from a list.

Questions or bugs? Ping the dev (that’s Toggy).

Add this bot to your server via this link and use !N5ehelp to get started
