<p align="center"><img src="https://i.ibb.co/RpNDzZG/Elden-Ring.png" width="350"></a>
<h1 align="center"><b>How-To install Seamless Co-op Mod for Elden Ring</b></h1>
<br />

## Prerequisites:
* The latest Version of Elden Ring
* [Seamless Co-op Mod](https://www.nexusmods.com/eldenring/mods/510) (Instructions for installing can be found on the Mod's Page)
* [Goldberg Steam Emulator](https://mr_goldberg.gitlab.io/goldberg_emulator/)
* [Radmin](https://www.radmin-vpn.com/), [Hamachi](https://www.vpn.net/) or [ZeroTier](https://www.zerotier.com/) 

## How-To:
1. Download and extract Goldberg SteamEmu
2. In Elden Ring's Game Directory, make a Backup of "steam_api64.dll" (eg: rename it to steam_api64.dll.backup)
3. Copy the "steam_api64.dll" from the Golberg Folder to your Elden Ring Game Directory
4. In the "tools" Folder of Goldberg, drag the Backup of "steam_api64.dll" you made onto the "generate_interfaces_file.exe". This should generate a "steam_interfaces.txt" File
5. Navigate to your Roaming AppData Folder. Found in "C:\Users\USERNAME\AppData\Roaming" (You can also get to this by opening run (win + r) and typing %appdata%).
Find "Goldberg SteamEmu Saves", then the "settings" Folder. Change the Contents of "account_name.txt" to whatever Username you want. 
Then open "user_steam_id.txt" and change the Number slightly. This must be different for every Person you will be playing with, so you should coordinate having a different Steam ID
6. Download and install Radmin or a similar Program
7. Create a Network, and have you and your Friends connect to it. After doing these Steps, you should be able to connect and join your Friends
8. The Host must use the "Tiny Great Pot" to create a Session. At that Point, the other players can join using the "Effigy of Meleina". 
You should spawn in at a Point nearby the Host. Any Player can leave at any time using the "Separating Mist" - If the Host uses this Item, the Session will be disbanded and all Players will disconnect.

## Potential Errors:
* Elden Ring is updated to the newest Version, and you're using the latest Version of the Seamless Co-Op Mod
* Running launch_elden_ring_seamlesscoop.exe as Admin
* Failed: No sessions found:
* Make sure you and your Friends:
  * Using the same Mod Version
  * Same Co-Op Password
  * Connected to a Hamachi-like Program
  * Generated the steam_interfaces.txt

## Failed Steam timed out Error:
* Delete the "steam_settings" Folder if you have it
* Changing the Port in "C:\Users\USERNAME\AppData\Roaming\Goldberg SteamEmu Saves\settings\listen_port.txt" to 47584 if it's not already
* Port Forwarding: 47584
* Add steam_emu.ini and steam_appid.txt to your Elden Ring Game Directory