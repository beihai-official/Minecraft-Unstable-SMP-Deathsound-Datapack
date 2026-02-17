# Minecraft-Unstable-SMP-Deathsound-Datapack
# Unstable SMP Deathsound

**Death just got epic.**  
When any player dies, **every online player on the server instantly hears the iconic wither spawn sound** (`entity.wither.spawn`) — that dramatic, booming "doom" everyone knows from wither summoning.

This lightweight datapack turns ordinary deaths into server-wide memorable moments, perfect for hardcore, chaotic, fun, or "unstable" SMP servers.


## Features

- **Server-wide wither spawn sound** on any player's death  
  - Uses `entity.wither.spawn` (the classic wither summon roar)  
  - Plays to **all online players** at once (master channel, adjustable volume/pitch)  
  - Slight random pitch variation for a more natural/epic feel

- **Global death announcement**  
- **No duplicate triggers**  
  - Uses scoreboard delta detection (current deaths - previous deaths)  
  - Ensures the sound and message play **exactly once** per death

## Installation

1. **Download the datapack**  
   - Go to the Releases page on this GitHub repository (or click the green "Code" button → "Download ZIP").  
   - Download the latest version (e.g. `unstable-smp-deathsound-main.zip` or a tagged release).

2. **Place the folder in your world**  
   Extract the ZIP if needed, then copy the folder named **`unstable-smp-deathsound`** into your world's `datapacks/` folder:  
   - **Singleplayer** (local world):  
     Windows: `%appdata%\.minecraft\saves\YourWorldName\datapacks\`  
     macOS/Linux: `\~/.minecraft/saves/YourWorldName/datapacks/`  
   - **Dedicated server**:  
     `world/datapacks/` (or replace `world` with your actual world folder name)

   **Important**: The folder name must be exactly `unstable-smp-deathsound` (no extra spaces, keep lowercase).

3. **Load the datapack**  
   - Join your world or server.  
   - Open chat (or use the server console) and run:  
     ```
     /reload
     ```

