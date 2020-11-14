# saki-portable-online

1. Download PPSSPP emulator https://www.ppsspp.org/
2. Download Saki ISO 
   * https://cdromance.com/psp/saki-portable-jpn/
   * https://www.emuparadise.me/PSP_ISOs/Saki_Portable_(Japan)/158534
   * https://mega.nz/file/HPZElJoS#KiKpS7fZXf6ujD_i2l1HK15Pw4beXpZMxt7_U3RMHlk
3. Download the better Achiga game and the complete save
   * https://cdromance.com/psp/saki-achiga-hen-episode-of-side-a-portable-jpn/
   * https://gamefaqs.gamespot.com/boards/712915-saki-achiga-hen-episode-of-side-a-portable/67548346
4. Download ZeroTier https://www.zerotier.com/

## ZeroTier setup for host
1. Make an account
2. Account > Create token
   * In the program, paste it in Preferences > API Key
3. Networks > Create Network
   * Write down the Network ID
4. Set it as public

## ZeroTier setup for everybody
1. Open the program
2. Join Network
   * Check all the things
   * Insert the Network ID given by host
3. If host, write down your Managed IP and share it with the others

## PPSSPP setup - Networking tab
1. Enable Networking/WLAN
2. Send Discord "Rich Presence" information
3. Change PRO ad hoc server IP address (enter ZeroTier Managed IP of host device)
4. Port Offset change from "0" to something else, everyone must use the same number
5. Settings > System > uncheck "Fast memory"
6. Enable network chat
   * In System > PSP settings > Change nickname, you can change the chat nick
6. If host, Enable built-in PRO Ad Hoc server


## Saki setup
1. Start Saki/Achiga
2. Open multiplayer (4th option in main menu for Saki, 3rd for Achiga)
3. Select common table 

## Bugs
1. Moving the cursor too fast freezes the game
2. Table 1 doesn't work?

## Achiga 
### Menu translation
![Try](https://raw.githubusercontent.com/watterle/saki-portable-online/main/menus.jpg "menu")
### Superpowers translation
![Try](https://raw.githubusercontent.com/watterle/saki-portable-online/main/saki%20psp%20abilities.png "superpowers")
