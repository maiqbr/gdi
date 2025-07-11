# gdi
Hey there! I'm GDI, or the Improbability Generator! A custom RPG bot for rolling dice, managing character sheets, and automating your rpg adventure.
Using me in your RPG session to roll some dice is super easy!

**MAIN COMMANDS**
> ✅ `/enable` → Activates the rolling and dynamic ambient system (reactions) for the entire server. **(It’s already activated when you add the bot)**
> ⛔ `/disable` → Deactivates the rolling and dynamic ambient system (reactions) for the entire server.
> ⛅ `/atmosphere` → Activates the dynamic atmosphere system (reactions) for the entire server.
> 🐉 `/adventure` → Sets up the permanent voice channel generation system controlled by the member (dont worry, permissions are minimal and local).

**Character Sheet and Attribute COMMANDS**
> 📋 `/attributes` → Edit your sheets and attributes
> 📋 `/sheet` → View any user's sheet
> 📝 `/editattribute` → Edit one or more attributes from your sheet via command
> 💿 `/exportsheet` → Export your sheet in JSON format
> 📀 `/importsheet` → Import an exported JSON sheet
> 💾 `/copyattributes` → Copy another user's attributes to your sheet
> 💖 `/heal` → Heal HP on your sheet
> 💔 `/damage` → Subtract damage from your current HP

**Rolling COMMANDS via `/` and others**
> 🎲 `/r` → Rolls XdY + bonuses + attributes if available (`X#Roll` gives result in a list)
> 🧮 `/calc` → Solve math expressions
> ⏳ `/timer` → Set a timer and get the corresponding timestamp
> - 🎛 `/panels` → Select a custom panel for easy simple rolls

**Dice Rolling (`XdY + BONUS + ATTRIBUTES`)**
> - **X** = number of dice
> - **Y** = faces per die
> - **BONUS** = flat modifier to add or subtract
> - **ATTRIBUTES** = your character’s attributes (aliases supported)
> - 
> - You can combine multiple dice, modifiers, and attributes. Example:
> `2d20+2d6+3d10+5+5+dex+str+con` → 🎲 d20[15, 4] + d6[3, **6**] + d10[6, 7, 4] +10 (+3⚡ +2💪 -1🍄) **➧ `59`**

> - For list rolls, use repetitions: `X#expression`, e.g. `2#d20`

> - **Exploding**: add `!` after the die:
>   - `d6!` explodes on 6
>   - `d6!:3` explodes on results ≥3 (Z+)

> - **FATE**: use `dfate`

> - **World of Darkness**:
>   - `Xdwod` → X dice, no difficulty
>   - `XdwodY` → X dice with difficulty Y (full breakdown)

> - **TTS**: start with tts to roll with text-to-speech.
Exemple: `tts2d6`

## Questions? `/help`

Copyright (c) 2025 [maiq]
All rights reserved.
Unauthorized copying, modification, or distribution of any part of this project is prohibited without explicit permission from the copyright holder.
