# saki-portable-online
Guide on how to get achiga psp game to work online on the ppsspp emulator. The same should apply to any psp game.

## Downloads
1. Download PPSSPP emulator https://www.ppsspp.org/
3. Download the better Achiga game and the complete save
   * https://mega.nz/file/2KYTwCDC#51AUToCsjHIlUXWE8Ng80Ld_UwtClkc0Sym5wZ3vl8k
   * https://mega.nz/file/WXIziIzL#V-F1dI6cYVkn2PuBjvYkXDk2jJGbEUGxV8ymsIzNGjE
     * Savedata goes in memstick\PSP\SAVEDATA in the PPSSPP folder (found in ./config for linux users). Open story mode to check if it is installed correctly. (You can also install it from PPSSPP settings probably)
4. Download ZeroTier https://www.zerotier.com/
   * You need to restart the PC after the installation or it won't work

## ZeroTier setup for host
1. Make an account
2. Account > Create token
   * In the program, paste it in Preferences > API Key
3. Networks > Create Network
   * Write down the Network ID
4. Set it as public
5. Write down your Managed IP and share it with the others

## ZeroTier setup for everybody
1. Open the program
2. Join Network
   * Insert the Network ID given by host  
   * Enable all the things (global ip, managed ip, etc...)

[Screenshot (not host)](https://raw.githubusercontent.com/watterle/saki-portable-online/main/208.png)

## PPSSPP setup - Networking tab
1. Enable Networking/WLAN
2. Send Discord "Rich Presence" information
3. Set PRO ad hoc server IP address (enter ZeroTier Managed IP of host device)
4. Port Offset change from "0" to something else, everyone must use the same number (/mjg/ "standard" is 100)
5. Settings > System > uncheck "Fast memory"
6. Enable network chat
   * In System > PSP settings > Change nickname, you can change the chat nick
7. If host, Enable built-in PRO Ad Hoc server  

[Screenshot (not host)](https://raw.githubusercontent.com/watterle/saki-portable-online/main/207.png)


## Saki setup
1. Start Saki/Achiga
2. Open multiplayer (3rd option)
3. Select common table

## Bugs
1. Moving the cursor too fast freezes the game
2. If error, try to run ppsspp as administrator/sudo
3. Toki and Teru should read waits but this seems to be bugged (needs a v1.01 patch)
4. Can't reconnect after disconnection (?)
5. AFK host stops people from joining (?)
6. Can't handle too many connections (?)

## Tierlist
1. Kuro banned due to completely bullshit power
   - Punish Kuro players by using Saki

## Achiga setup and translation
### Menu translation
![mainmenu](https://raw.githubusercontent.com/watterle/saki-portable-online/main/menus.jpg "mainmenu")
![lobbymenu](https://raw.githubusercontent.com/watterle/saki-portable-online/main/143.png "lobbymenu")
![rulesmenu](https://raw.githubusercontent.com/watterle/saki-portable-online/main/148.png "rulesmenu")
![gamemenu](https://raw.githubusercontent.com/watterle/saki-portable-online/main/144.png "gamemenu")



### Superpowers translation
[Infopic (imprecise)](https://raw.githubusercontent.com/watterle/saki-portable-online/main/1609976207723.png)

#### Achiga
Matsumi Kuro (doraslut)  
opponents can't draw any dora  
you are more likely to draw dora and triplets and get dora in haipai  
deactivates upon discarding dora, which reverses the power so that you can no longer draw any dora  

Matsumi Yuu (scarf)  
biased to draw red tiles, which means manzu, 1579s, 135679p and chun  

Atarashi Ako (enkoslut)  
likely to draw good tiles after calling  

Sagimori Arata (bowling)  
likely to draw her winning tile with the following exact waits:  
4679p, 467p, 1247p, 24578p, 28p, 57p, 79p  

Takakamo Shizuno (monkey)  
activates during the 3rd row of discards  
opponents get worse draws while she gets better draws  
opponents' powers become weaker  

#### Senriyama

Onjouji Toki  
can see her next draw (this can not be shifted using calls)  
can see opponents' winning tiles  
when 12k below 1st place, she can see 2 draws ahead, and 3 draws when 32k down  
deactivates for the last 14 tiles of a hand  
slightly improved draws  

Nijou Izumi (who?)  
no power  

Eguchi Seera (tomboy)  
slightly improved draws  
haipai biased towards iipeikou  

Funakubo Hiroko (glasses)  
no power  

Shimizudani Ryuuka (toki's gf)  
activates in even rounds (E2, E4, ...)  
can see the final shape of here hand, and draws towards it  
the final shape is typically mangan to baiman  

#### Shiraitodai

Miyanaga Teru  
gets good haipai after winning a hand  
can see opponents' winning tiles  
does NOT get improved draws  

Hirose Sumire (archer)  
highest placed opponent will draw her winning tile after she gets tenpai  

Shibuya Takami (glasses)  
her first discard each round will be part of her haipai in all last  
when there are multiple S4, this activates every time  
discarding a tile as first discard more than 4 times nullifies the power  

Matano Seiko (green hair tomboy)  
guaranteed to draw good tiles after calling 3 pons  
likely to draw pairs  

Oohoshi Awai (blondie)  
opponents get worse haipai  
when not in 1st place, likely to get double riichi with late game rinshan  

#### Shindouji  

Hanada Kirame (subara)  
can't get shadowrealmed  
the game won't let her deal in unless there is no safe tile  
opponents won't tsumo if it would shadowrealm her  

Yasukouchi Yoshiko (glasses)  
no power  

Ezaki Hitomi (sheep)  
no power  

Shirouzu Mairu (twintail)  
if she wins and Himeko plays the next hanchan, Himeko will get a good haipai in the same round and honba  
improved draws  

Tsuruta Himeko (vibrator)  
as above but no improved draws  

#### Kiyosumi

Kataoka Yuuki (tacos)  
improved draws during the first 3 hands  
biased to be starting dealer  

Someya Mako (glasses)  
activates in the 4th hand of the hanchan  
can see opponents' winning tiles  
likely to have honor pairs in haipai and draw manzu  

Takei Hisa (captain)  
likely to draw her winning tile if 2 or less are left  
works even with dama and open hands  

Haramura Nodoka (10hoe autist)  
improved draws if she won the previous hand  
immune to some other characters' powers  

Miyanaga Saki (MC)  
gets good draws whenever she kans  
cancels the power of opponents whose discards she kans  
likely to have kan of shaa in haipai  
draws are biased towards triplets  

#### Ryyumonbuchi  

Inoue Jun (tomboy)  
after calling, she gets a good draw while each opponent gets a bad draw  

Sawamura Tomoki (autist)  
no power  

Kunihiro Hajime (cunnyhero)  
no power  

Ryuumonbuchi Touka (ojou)  
likely to get ippatsu with a hand that is at least mangan  
can tell when others are in tenpai  

Amae Koromo (cunny)  
whenever she has the haitei, opponents will draw bad tiles and she will often tsumo haitei  
likely to have an honor triplet in haipai  
can tell when others are in tenpai  
slightly improved draws  

#### Kazekoshi  

Fukuji Mihoko (kyaputen)  
activates in the 8th hand after the start of the hanchan  
can see the suit of the tiles in opponents' hands and gets improved draws  

Ikeda Kana (nyagger)  
activates whenever below 10k points  
guaranteed to get a good haipai, biased toward chanta  

#### Tsuruga  

Kanbara Satomi (wahaha)  
whenever her haipai has at least 2 dora, she will go "wahaha" (negative power)  

Kajiki Yumi (purple hair Tsuruga lesbo)  
if she gets 123456 of one suit in haipai, 789 becomes easier to draw  
increased odds of kokushi   
possibly biased towards worse hands  

Touyoko Momoko (invisible girl)  
activates in the 7th hand after the start of the hanchan  
opponents can't call her tiles and her riichi declaration becomes undetectable  
however, furiten still applies as normal  

#### Others

Kobashiri Yae (drill hair)  
when she calls riichi, other players get better draws (negative power)  
slightly improved draws  

Akado Harue (achiga coach)  
highly improved haipai and draws  
likely to get sanshoku  

Arakawa Kei (who?)  
if another player wins, she gets better haipai and draws next hand  
improved draws  

Fujita Yasuko (pro)  
improved haipai and draws  

Suga Kyoutarou (>male)  
worse draws (negative power)  
