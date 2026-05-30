# Nuclear Option Discord Rich Presence

<img width="1080" height="517" alt="1000103798" src="https://github.com/user-attachments/assets/0f1b884a-53ae-48e3-af85-1e4709a4e5bf" />

A lightweight, seamless BepInEx plugin that brings **Discord Rich Presence** to [Nuclear Option](https://store.steampowered.com/app/2168680/Nuclear_Option/). Let your friends see exactly what you're up to in the skies!

## Features
- **Dynamic Game States**: Accurately displays your current activity, whether you're in the Main Menu, Singleplayer, Multiplayer, the Mission Editor, or the Encyclopedia.
- **Detailed Flight Info**: Shows the aircraft you're currently flying, natively supporting both vanilla names and custom designations from mods like the *Quality of Life (QoL) Mod*.
- **Live Loadout Tracking**: Displays your active weapon loadout right on your Discord profile (e.g., `4x AAM-29 Scythe, 2x AGM-48`).
- **Mission & Map Context**: Broadcasts the current mission name and map environment (e.g., *Ignus Archipelago*, *Heartland*).
- **Faction/Team Awareness**: Lets others know whether you're fighting for the BDF, PALA, or picking a team.
- **Multiplayer Lobby Support**: Automatically detects and displays the number of players in your multiplayer lobby.

## Installation
1. Ensure you have **BepInEx** installed for Nuclear Option.
2. Download the latest `NuclearOptionRPC.dll` and `tab.discord_game_sdk.dll` from the [Releases](#) 
3. Drop the `NuclearOptionRPC.dll` into your `Nuclear Option/BepInEx/plugins` folder.
3. Drop the `tab.discord_game_sdk.dll` into your `Nuclear Option` folder.
4. Launch the game with Discord open, and you're good to go!

## Compatibility
- Works seamlessly with the **Quality of Life (QoL) Mod** and dynamically respects altered unit/encyclopedia names!
- Compatible with custom maps and missions, automatically falling back to graceful display names.

## Technical Details
Built using Harmony and the official Discord Game SDK, this mod is highly optimized. It should scans the game state intelligently without dragging down your framerate or constantly polling expensive Unity methods.

## Credits
- https://github.com/ZidentZ1
