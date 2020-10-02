# saki-portable-online

1. Download PPSSPP emulator https://www.ppsspp.org/
2. Download Saki ISO https://www.emuparadise.me/PSP_ISOs/Saki_Portable_(Japan)/158534
3. Download ZeroTier https://www.zerotier.com/

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
6. If host, Enable built-in PRO Ad Hoc server

## Saki setup
1. Start Saki
2. Open multiplayer (4th option in main menu)
3. Select common room

## Bugs
1. Room 1 doesn't work
2. Moving the cursor too fast freezes the game

