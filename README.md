# skyhud

Release downloads for skyhud, a Hypixel SkyBlock HUD for Fabric on Minecraft 26.2.

skyhud has one stats panel that follows what you're doing (the tool in your hand, then the island), an activity panel
with matching progress, and a location panel. Each island remembers its own layout, and the middle third of the screen
stays clear.

## Install

1. Install Fabric Loader 0.19.5 or newer for Minecraft 26.2, and Fabric API.
2. Put `skyhud-<version>.jar` from [Releases](https://github.com/ethanluh/skyhud/releases) in your `mods` folder.
   The Hypixel Mod API is bundled.
3. On Hypixel, turn on the tab list's Stats widget and the stats you want shown.

Run `/skyhud edit` to arrange the panels.

skyhud only displays data the client already receives and automates nothing. Hypixel does not approve individual
mods, so use it at your own risk.
