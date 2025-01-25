# JeriCraft Halo Servers Overview

Welcome to **JeriCraft**'s Halo community! Our collection of Halo servers provides a diverse range of exciting and
unique game modes designed to challenge players, foster competition, and provide endless fun. Whether you're a fan of
strategic team-based gameplay, intense free-for-all action, or something in between, we have something for everyone.

Here’s a quick overview of our current Halo servers:

| Game Mode                                                                   | Description                                                                                                                                                  | Server                 |
|-----------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------|
| **[Divide & Conquer](/HALO/servers/Divide%20and%20Conquer.md)**             | A dynamic game mode where each team works to recruit opponents after eliminating them, with the game ending when one team is fully converted.                | **jericraft.net:2301** |
| **[Gun Game](/HALO/servers/Gun%20Game.md)**                                 | Start with basic weapons and upgrade after each kill, aiming to reach the top weapon and claim victory.                                                      | **jericraft.net:2302** |
| **[Hunter Prey](/HALO/servers/Hunter%20Prey.md)**                           | A survival-based game mode where players fight to control the flag at the center of the map. The player who holds the flag the longest wins.                 | **jericraft.net:2303** |
| **[Kill Confirmed](/HALO/servers/Kill%20Confirmed.md)**                     | Score points by eliminating enemies and collecting their dog tags (skulls), ensuring kills count towards your team's score.                                  | **jericraft.net:2304** |
| **[Market](/HALO/servers/Market.md)**                                       | A unique server with an in-game economy, allowing players to buy weapons and gear to take down their opponents.                                              | **jericraft.net:2305** |
| **[Melee Attack](/HALO/servers/Melee%20Attack.md)**                         | A mode focused entirely on close combat, where players only use melee attacks to fight their enemies.                                                        | **jericraft.net:2306** |
| **[One In The Chamber](/HALO/servers/One%20In%20The%20Chamber.md)**         | Players only have one bullet per life, and must use their wits to outsmart and eliminate opponents without wasting ammo.                                     | **jericraft.net:2307** |
| **[Rooster CTF](/HALO/servers/Rooster%20CTF.md)**                           | A CTF mode for Slayer (FFA/Team), where players fight to capture a single flag and return it to either the Red or Blue Base to score.                        | **jericraft.net:2308** |
| **[Sabotage](/HALO/servers/Sabotage.md)**                                   | Players must work to plant explosives and sabotage the opposing team’s objectives while defending their own.                                                 | **jericraft.net:2309** |
| **[Snipers Dream Team Mod](/HALO/servers/Snipers%20Dream%20Team%20Mod.md)** | A highly modded snipers game mode with unique features and gameplay mechanics.                                                                               | **jericraft.net:2310** |
| **[Tag](/HALO/servers/Tag.md)**                                             | A fast-paced and exciting variation of tag, where players must catch (melee) and eliminate each other in a thrilling chase.                                  | **jericraft.net:2311** |
| **[Team Defender](/HALO/servers/Team%20Defender.md)**                       | One player holds the flag while their team defends them. Keep the flag for double points. The flag respawns every 15 seconds if dropped, requiring teamwork. | **jericraft.net:2312** |
| **[Zombies](/HALO/servers/Zombies.md)**                                     | A unique twist on the classic zombies mode, where Humans (Red Team) must survive while Zombies (Blue Team) aim to infect and convert them.                   | **jericraft.net:2313** |

Each server offers a unique and custom experience, crafted to deliver the best possible gameplay. Whether you’re looking
to compete in a classic mode or try something completely new, JeriCraft Halo servers are ready for you. Dive into the
action and join us on any of the following servers today!

For more information about each game mode or to connect, check out the individual server pages linked above. Happy
gaming! 🎮

---

# JeriCraft Server Scripts

All **JeriCraft** servers are equipped with several custom scripts designed to improve gameplay, ensure fair play, and
enhance the overall server experience. Here’s a list of the scripts running on all of our servers:

## 🛠️ **Alias System**

The Alias System is an advanced tool designed to enhance security and fairness across all JeriCraft Halo servers. It
keeps a record of every player name used during gameplay, linking each alias to both the player's unique CD Key (hash)
and IP Address. This system helps catch cheaters, prevent repeat offenders from evading bans, and ensures the integrity
of the game environment by identifying players who may try to hide their identity through name changes or IP address
manipulation. With this robust tracking mechanism, we are able to maintain a clean and enjoyable community for all
players.

## 🔒 **VPN Blocker**

We use a **VPN Blocker** to prevent players from connecting to our servers using a VPN. This helps to reduce malicious
activity and ensures that only legitimate players can join the community.

## 📝 **Server Logger**

Our **Server Logger** tracks important events and activities on the server to help maintain a secure and transparent
environment. The following events are logged:

- **SCRIPT LOAD**: When the Advanced Logger is loaded.
- **SCRIPT RELOAD**: When the Advanced Logger is re-loaded.
- **SCRIPT UNLOAD**: When the Advanced Logger is unloaded.
- **START**: A new game has started, showing the map and mode.
- **END**: When a game ends and the post-game carnage report is shown.
- **JOIN**: A player joins, including their name, ID, IP, and piracy status (whether they are using a pirated copy of
  the game).
- **QUIT**: A player quits, including their name, ID, IP, and piracy status (whether they are using a pirated copy of
  the game).
- **SPAWN**: A player spawns in the game.
- **WARP**: A player is detected warping.
- **LOGIN**: A player logs in, with their admin level.
- **RESET**: The map is reset.
- **SWITCH**: A player switches teams.
- **COMMAND**: A player executes an admin command, including their level and command type.
- **MESSAGE**: A player sends a message in chat, including message type.
- **DEATH**: Tracks various types of player deaths, including suicides, betrayals, and kills by other players.
- **FIRST BLOOD**: Tracks the first kill in a game.

And more!

## 💤 **AFK Manager**

The **AFK Manager** is designed to monitor players who are inactive for extended periods. Players detected as AFK will
be automatically warned then kicked to prevent them from affecting the gameplay experience of others.

## 🚫 **Anti Cheat**

Our **Anti Cheat** script actively scans for and prevents players from using aim bots, wall hacks, camping, and other
cheating
methods (including common exploits), which would otherwise give them an unfair advantage in combat. This helps to ensure
a level playing field for all players.

## 💬 **Admin Chat**

Admins have access to a special **Admin Chat** feature that allows them to communicate privately with other staff
members.

## 🚫 **Word Buster**

The **Word Buster** script filters out inappropriate language and offensive words from chat messages to maintain a
clean and respectful environment for all players.

## 🕵️ **Command Spy**

Admins can see all commands executed by players using the **Command Spy** feature, allowing them to monitor players and
ensure fair play.

## 📜 Script Manager**

Runs all of our custom scripts and ensures they function correctly to provide a smooth and enjoyable gameplay
experience.

---

These scripts work together to provide an environment where players can enjoy fair, secure, and exciting gameplay. We
are always working to improve the community experience, so be sure to check out these features in action on all of our
servers!

Happy playing! 🎮