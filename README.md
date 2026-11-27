# BO Overlay – releases

Installers and update files for **BO Overlay**, an unofficial fan overlay for Broken Oath
(not made, endorsed or supported by the game's developers).

Download the latest `BO Overlay_x.y.z_x64-setup.exe` from **Releases**. Source code is not public.
The app updates itself and asks before installing.

Free for personal use, all rights reserved. See the licence in the installer / About page.
Contact: Discord `rampa88`.


BO Overlay (alpha) – unofficial overlay for Broken Oath

Hi all! I made a small free overlay that sits on top of the game and uses the public Broken Oath API. It's in alpha, same as the game, so expect rough edges. Builds still miss item images, but that doesn't change how it works.

What it does
• Ladder, Builds, Favourites, Import – browse the public ladder and builds, see skills with gem icons and names, an inventory / idols view with item tooltips, save favourites. "Lilshrimper ↗" opens the hero in the web build planner, and a search box in the build details finds a gem, skill or item at a glance
• Check item – press Ctrl+C on an item in game and the overlay finds similar listings on the Wagon Market (cheapest, price chips, per-affix matching). One click opens the same search on BO Market or Lilshrimper with the league, slot, rarity and your ticked mods already filled in
• Filters – lists your loot filters, shares them with the community under your Discord name, and lets you browse filters shared by others and copy them straight into the game. Other tools can read the shared filters through the public API
• League auto-detect – reads which league your character is in from the game log and switches Check item, Ladder and Builds to it automatically, including new leagues like Playtest
• Overlay controls – opacity, always on top, show/hide with a hotkey, click-through, remembers its window position and size, and gives focus back to the game after you click it
• Auto-update – it checks for a new version on start and every 6 hours, there is also a "Check for updates" button in Settings, and it always asks before installing

Safe? It only reads the clipboard (your Ctrl+C), the game's log file and the game's public web API. It doesn't touch, inject into or automate the game. It's an unofficial fan tool, not made or endorsed by the developers.

Download: https://github.com/mlukympoe/bo-overlay-releases/releases
Windows may show a SmartScreen warning because the installer isn't code-signed (More info → Run anyway).

Bugs / ideas: please write them here or DM me (Discord: rampa88). I'd be glad for any feedback! Known limit: items linked in chat can't be copied in game yet, so they can't be price-checked.


Big thanks to the Broken Oath developers for the public API – this tool wouldn't exist without it.
Free for personal use, all rights reserved. Made by R4mpa Mckvak.
