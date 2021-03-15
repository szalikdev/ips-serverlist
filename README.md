# (aXen) Advanced Server List

Server table showing server information about the status, name, number of players, current map and their owners as applications on IPS Community Suite.

### Other features:

- Set your own fields for the server:
  - Name,
  - Own name,
  - IP,
  - Own IP,
  - Statistics URL,
  - TV URL,
  - Vote URL,
  - Forum URL
- Highlight for the server,
- Special badge for the new server,
- Hiding server owners in button,
- The scroll that the user can control,
- Color filling of players,
- RWD,
- Lazy loading in img icons,
- Table in 2 columns that the user can control

## Table of contents 📖

- [Requirements 🏷️](#requirements-)
- [Compatible servers 💻](#compatible-servers-)
- [Install 🧰](#install-)
- [Configuration 🔨](#configuration-)
  - [Discord Configuration](#dicord-configuration)
  - [TeamSpeak 3 Permissions](#teamspeak-3-permissions)
- [Update 🛠️](#update-)
- [Graphics 📷](#graphics-)
- [Download from other sources 🔌](#download-from-other-sources-)

## Requirements 🏷️

- [IPS Community Suite: 4.5 version](https://invisioncommunity.com/)
- PHP 7.2+
- [Bzip2](https://www.php.net/manual/en/book.bzip2.php) - Used for A2S Compressed responses,
- ❗❗ Unlocked external ports on the website server

## Compatible servers 💻

- ARK: Survival Evolved
- Arma3
- Battlefield 2
- Battlefield 3
- Battlefield 4
- Battlefield 1942
- Battlefield Bad Company 2
- Battlefield Hardline
- Call of Duty
- Call of Duty 2
- Call of Duty 4
- Call of Duty: United Offensive
- Call of Duty: World at War
- Conan Exiles
- Contagion
- Counter-Strike 1.6
- Counter-Strike: Condition Zero
- Counter-Strike: Global Offensive
- Counter-Strike: Source
- DayZ Standalone
- DayZ Mod
- Discord
- Garry's Mod
- GRAV Online
- GTA Five M
- Grand Theft Auto Network
- Half Life 2: Deathmatch
- Hurtworld
- Insurgency
- Star Wars Jedi Knight: Jedi Academy
- Star Wars Jedi Knight II: Jedi Outcast
- Just Cause 2 Multiplayer
- Just Cause 3
- Left 4 Dead
- Left 4 Dead 2
- Minecraft
- Medal of honor: Allied Assault
- Multi Theft Auto
- Mumble Server
- Natural Selection 2
- Quake 2 Server
- Quake 3 Server
- Quake Live
- Red Orchestra 2
- Rust
- San Andreas Multiplayer
- 7 Days to Die
- The Ship
- Squad
- StarMade
- Teamspeak 3
- Teeworlds Server
- Terraria
- Team Fortress 2
- Tibia
- Tshock
- Unreal 2
- Unturned
- Unreal Tournament 3
- Unreal Tournament 2004
- Ventrilo
- Warsow
- World Opponent Network

_In future versions, new servers will be added to the list._

## Install 🧰

1. Go to: AdminCP -> System -> SITE FEATURES -> **Appliactions**,  
   ![Select Plugin](https://axendev.net/github/app/admincp_select.png)
2. Click on the link **manual upload**,  
   ![Manual Upload](https://axendev.net/github/app/manual_upload.png)
3. Select file **.tar** [from packet](https://github.com/aXenDeveloper/ips-app-serverlist/releases) and click install button

## Configuration 🔨

1. Go to: AdminCP -> Advanced Server List -> Servers -> **Create new**,
2. First you have to choice a game in **Game**,
3. Provide a custom name in **Custom name** for example: _JailBreak_,
4. Provide a address IP in **IP** for example: **145.239.16.78:27015**.  
   ❗❗ Some servers like **TeamSpeak 3** require a **Query port**!
5. Click **save**.

### Discord configuration

You have to configurate Discord Widget which will return a value:

- name,
- instant_invite,
- presence_count

To add a discord server you have to enter the **widget ID** in the **IP** field.

If you want check return values from your server discord check from json file: `https://discordapp.com/api/guilds/{your ID widget form discord}/widget.json` for example: https://discordapp.com/api/guilds/720054040116854835/widget.json

### TeamSpeak 3 Permissions

If after adding TeamSpeak 3 server but it's still offline then check permissions for **guest** group:

```
b_virtualserver_info_view
b_virtualserver_channelgroup_list
b_virtualserver_client_list
b_virtualserver_channel_list
```

## Update 🛠️

1. Go to: AdminCP -> System -> SITE FEATURES -> **Appliactions**,  
   ![Select Plugin](https://axendev.net/github/app/admincp_select.png)
2. Search appliaction and click **Upload a new version**,  
   ![Upload a new version](https://axendev.net/github/app/new_version_upload.png)
3. Select file **.tar** from packet and click install button.

## Graphics 📷

![1](https://axendev.net/myapps/app/serverlist/1.png)
![2](https://axendev.net/myapps/app/serverlist/2.png)
![3](https://axendev.net/myapps/app/serverlist/3.png)
![4](https://axendev.net/myapps/app/serverlist/4.png)
![5](https://axendev.net/myapps/app/serverlist/5.png)
![6](https://axendev.net/myapps/app/serverlist/6.png)
![7](https://axendev.net/myapps/app/serverlist/7.png)
![8](https://axendev.net/myapps/app/serverlist/8.png)
![9](https://axendev.net/myapps/app/serverlist/9.png)

## Download from other sources 🔌

- [invisioncommunity.com](https://invisioncommunity.com/files/file/9852-axen-advanced-server-list/),
- [invisionize.pl](https://forum.invisionize.pl/files/file/825-axen-advanced-server-list/)

_The resources from the links above are updated on an ongoing basis if the administration approves the file._
