# csgo_llama
Simplified csgo_english.txt and valve_english.txt with more COLORS

## Install

1. Download and place `csgo_llama.txt` and `valve_llama.txt` in your `SteamApps\common\Counter-Strike Global Offensive\csgo\resource` directory.
2. Right-click 'Counter-Strike: Global Offensive' >> 'Properties' >> 'Set launch options...'
3. Add `-language llama` to the launch options and click 'OK'.

## Features

### Friendlist

![Friendlist](/readme/friends.png)

- Changed `Playing` to `Loading...` and `Main Menu`, because this status will show up only when starting the game (Loading) and when players aren't connected to any server (Main Menu).
- Official **Competitive** and **Casual** now with bold.
- All Community *gamemodes* now with italics.
- Unfortunately colors can't be changed, tried `<font>` and `<span>`. Newline `\n` works but then texts overlap.

### Status messages

![Status](/readme/status.png)

- Added more colors, because why not?
- Used [Solarized](http://ethanschoonover.com/solarized) color palette

### Damage

![Damage](/readme/dmg.png)

- Changed taken damage to red and given to green to improve readability

### Chat

![Chat](/readme/chat.png)

- Radio messages starts with green `[R]`
- Team messages starts with dark yellow/dark blue `[T]` as in `Team`, no separation between CT/T, because you can see that from the name color 
- Dead messages starts with grey `[D]` or `[T]` depending of say/say_team
- Spectator messages starts with `[S]`

#### Competitive chat

![Competitive](/readme/comp.png)
![Hearts](/readme/hearts.png)

- Same as above, but had to fiddle with the dots so they line up
- You could also change the dots to something else
  - Uncomment line 290 and comment line 289 

#### Grenades

![Grenades](/readme/grenades.png)

- Each grenade has own color to improve readability

#### Other chat messages

![Other](/readme/other.png)

- Shortened messages and added some colors

## TODO

- Change more stuff
- Get suggestions
- Receive bacon
