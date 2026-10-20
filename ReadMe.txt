🇮🇷 Deadlock Persian Localization

A clean, accurate, and lightweight Persian (فارسی) localization for Deadlock!

🌐 Website: https://games.peditx.ir
📦 GitHub: https://github.com/peditx/DeadLock-Persian

✨ Features
- Full Hero Ability Translations: 100% faithful Persian descriptions for all 47+ heroes, including Hero Labs heroes
- Hero Lore: every hero's lore translated
- Item & Shop Descriptions: in natural gamer Persian
- Settings Menu: the whole Settings section (Video, Audio, Keybinds, Camera, Accessibility, Shop, Chat...) in Persian
- Hero Quips & Reactions: in-match voice lines shown as text
- Custom Splash Logo: branded loading screen
- Vanilla Upgrade Cards: Tier 1 / Tier 2 / Tier 3 upgrades stay in clean English so stats, numbers, and scaling remain crystal clear and readable
- BiDi & RTL Fixed: no reversed numbers, broken brackets, or UI layout glitches
- Zero Gameplay Impact: pure text mod, no scripts, no performance cost

✅ Why this mod
- Written the way Deadlock players actually talk — gamer terms, never stiff word-by-word translation
- Proper right-to-left support: mixed English terms, numbers, and tokens render correctly
- Superset of the original mod: everything the base mod had, plus new translations on top
- Light and safe: text files only, nothing executable

📦 Installation
Download pak82_dir.vpk.
Move/copy the .vpk file to your Deadlock mod directory:
...\Steam\steamapps\common\Deadlock\game\citadel\addons\
(If the custom folder does not exist inside citadel, simply create it).

and then replace this line in your gameinfo.gi (located ...\Steam\steamapps\common\Deadlock\game\citadel):
text replace in gameinfo :

            Game_Language "citadel_*LANGUAGE*"
            Game          "citadel/addons"

            Mod   "citadel"
            Write "citadel"
            Game  "citadel"
            Mod   "core"
            Write "core"
            Game  "core"


Launch the game and enjoy!

🗑️ Uninstallation
Simply delete pak82_dir.vpk from the addons\ folder.

🇬🇧 On purpose, left in English
Soul, Deny, tier upgrade cards, hero / ability / item names, and tech terms like FPS, VSync, DLSS — the words every Deadlock player uses.

🚧 In progress
Rest of the in-game menus, hero tags, and in-game subtitles / VO captions.

🙏 Credits
Base localization (abilities, quips, items) — original mod author
Lore, Settings menus, logo, packaging — peditx
File tracking & English baseline: SteamTracking/GameTracking-Deadlock

Unofficial fan translation. Not affiliated with Valve.
