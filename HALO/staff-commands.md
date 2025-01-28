# Staff Rank Hierarchy:

### 🏵️ Trial-Mod - Levels 1-2

As an entry-level staff rank, Trial-Mods have access to essential moderation commands (✨) to help maintain the server's
friendly environment.

### 🛠️ Moderator - Levels 3-4

Moderators have access to all Trial-Mod commands and additional tools (🔧) for managing and resolving issues efficiently.

### ⚙️ Admin (Administrator) - Levels 5-6

Admins have access to all Moderator and Trial-Mod commands, along with advanced tools (⚙️) for server management and
behind-the-scenes operations.

### 👑 Senior Admin - Level 6+

The highest rank in the JeriCraft hierarchy, Owners have access to all staff commands (👑) and are responsible for
overseeing the entire server.

---

# PRIMARY ADMIN COMMANDS:

Used for adding, removing, and managing Halo staff members, as well as handling player bans, mutes, and other
administrative tasks.

| Command                                                                                     | Description                                                         | Permission Level |
|---------------------------------------------------------------------------------------------|---------------------------------------------------------------------|------------------|
| **login** `<password>`                                                                      | Login with a password (username is your IGN)                        | **1**            |
| **logout**                                                                                  | Logout of the server                                                | **1**            |
| **admin_chat** `<1/0 (on/off)>`                                                             | Toggle admin chat on or off for yourself                            | **2**            |
| **change_password** `<old password>` `<"new password">`                                     | Change your own password                                            | **2**            |
| **ip_mute** `<player id>` `<flag (-y -mo -d -h -m -s -r "example reason")>`                 | Mute a player by IP                                                 | **3**            |
| **ip_unmute** `<ban id>`                                                                    | Unmute a player's IP                                                | **3**            |
| **ip_mutes** `<page>`                                                                       | List all muted players by IP                                        | **3**            |
| **hash_mute** `<player id>` `<flag (-y -mo -d -h -m -s -r "example reason")>`               | Mute a player by hash                                               | **3**            |
| **hash_unmute** `<ban id>`                                                                  | Unmute a player's hash                                              | **3**            |
| **hash_mutes** `<page>`                                                                     | List all muted players by hash                                      | **3**            |
| **spy** `<1/0 (on/off)>`                                                                    | Toggle command spy on or off for yourself                           | **3**            |
| **ip_alias** `<player/ip>` `<page>`                                                         | Lookup aliases by player id or ip                                   | **4**            |
| **hash_alias** `<player/hash>` `<page>`                                                     | Lookup aliases by player id or hash                                 | **4**            |
| **ip_ban** `<player id>` `<flag (-y -mo -d -h -m -s -r "example reason")>`                  | Ban a player by IP                                                  | **4**            |
| **ip_unban** `<ban id>`                                                                     | Unban a player's IP                                                 | **4**            |
| **ip_bans** `<page>`                                                                        | List all IP-bans                                                    | **4**            |
| **hash_admin_add** `<player id / -u "name">` `<-l level>` `<-h hash>`                       | Add player as a hash-admin                                          | **5**            |
| **hash_admin_delete** `<admin id>`                                                          | Remove player as a hash-admin                                       | **5**            |
| **hash_admins** `<page>`                                                                    | List all hash-admins                                                | **5**            |
| **ip_admin_add** `<player id / -u "name">` `<-l level>` `<-ip IP>`                          | Add player as an ip-admin                                           | **5**            | 
| **ip_admin_delete** `<admin id>`                                                            | Remove player as an ip-admin                                        | **5**            |
| **ip_admins** `<page>`                                                                      | List all ip-admins                                                  | **5**            |
| **hash_ban** `<player id>` `<flag (-y -mo -d -h -m -s -r "example reason")>`                | Ban a player by hash (requires confirmation if the hash is pirated) | **5**            |
| **hash_unban** `<ban id>`                                                                   | Unban a player's hash                                               | **5**            |
| **hash_bans** `<page>`                                                                      | List all hash-bans                                                  | **5**            |
| **name_ban** `<player id or name>`                                                          | Ban a players name by ID or name                                    | **5**            |
| **name_unban** `<ban id>`                                                                   | Unban a name                                                        | **5**            |
| **name_bans** `<page>`                                                                      | List all name bans                                                  | **5**            |
| **pw_admin_add** `<player id / -u "name">` `<-l level>` `<-p "password">`                   | Add player as a password-admin                                      | **5**            |
| **pw_admin_delete** `<admin id>`                                                            | Remove player as a password-admin                                   | **5**            |
| **pw_admins** `<page>`                                                                      | List all password-admins                                            | **5**            |
| **confirm**                                                                                 | Confirm admin delete                                                | **5**            |
| **change_level** `<player id>` `<type (hash/ip/password)>`                                  | Change player admin level                                           | **6**            |
| **change_admin_password** `<player id>` `<"new password">`                                  | Change another player's password                                    | **6**            |
| **level_add** `<level>`                                                                     | Add an admin level                                                  | **6**            |
| **level_delete** `<level>`                                                                  | Delete an admin level (requires confirmation)                       | **6**            |
| **disable_command** `<command>`                                                             | Disables a command                                                  | **6**            |
| **enable_command** `<command>`                                                              | Enables a command                                                   | **6**            |
| **set_command** `<command>` `<level>` `(opt 3rd arg: "true" to enable, "false" to disable)` | Add or set a new/existing command to a new level                    | **6**            |

# SECONDARY ADMIN COMMANDS:

Used for managing server settings, map rotations, kicking players, and other server-related tasks.

| Command               | Description              | Permission Level |
|-----------------------|--------------------------|------------------|
| clead                 | Command description here | 1                |
| info                  | Command description here | 1                |
| lead                  | Command description here | 1                |
| stats                 | Command description here | 1                |
| stfu                  | Command description here | 1                |
| sv_stats              | Command description here | 1                |
| unstfu                | Command description here | 1                |
| whatsnext             | Command description here | 1                |
| kdr                   | Command description here | 2                |
| mapcycle              | Command description here | 2                |
| pl                    | Command description here | 2                |
| say                   | Command description here | 2                |
| afk                   | Command description here | 3                |
| afks                  | Command description here | 3                |
| aimbot_scores         | Command description here | 3                |
| k `<player id>`       | Kick player              | 3                |
| skips                 | Command description here | 3                |
| balance_teams         | Command description here | 4                |
| inf                   | Command description here | 4                |
| ip                    | Command description here | 4                |
| st                    | Command description here | 4                |
| tell                  | Command description here | 4                |
| uptime                | Command description here | 4                |
| map                   | Command description here | 5                |
| maplist               | Command description here | 5                |
| about                 | Command description here | 6                |
| admin_prefix          | Command description here | 6                |
| afk_kick              | Command description here | 6                |
| aimbot_ban            | Command description here | 6                |
| ammo                  | Command description here | 6                |
| anticamp              | Command description here | 6                |
| anticaps              | Command description here | 6                |
| anticheat             | Command description here | 6                |
| antiglitch            | Command description here | 6                |
| antihalofp            | Command description here | 6                |
| antilagspawn          | Command description here | 6                |
| antispam              | Command description here | 6                |
| antiwar               | Command description here | 6                |
| area_add_cuboid       | Command description here | 6                |
| area_add_sphere       | Command description here | 6                |
| area_del              | Command description here | 6                |
| area_list             | Command description here | 6                |
| area_listall          | Command description here | 6                |
| assists               | Command description here | 6                |
| auto_update           | Command description here | 6                |
| ayy lmao              | Command description here | 6                |
| battery               | Command description here | 6                |
| beep                  | Command description here | 6                |
| block_all_objects     | Command description here | 6                |
| block_all_vehicles    | Command description here | 6                |
| block_object          | Command description here | 6                |
| block_tc              | Command description here | 6                |
| boost                 | Command description here | 6                |
| camo                  | Command description here | 6                |
| cevent                | Command description here | 6                |
| chat_console_echo     | Command description here | 6                |
| cmd_add               | Command description here | 6                |
| cmd_del               | Command description here | 6                |
| cmdstart1             | Command description here | 6                |
| cmdstart2             | Command description here | 6                |
| color                 | Command description here | 6                |
| console_input         | Command description here | 6                |
| coord                 | Command description here | 6                |
| cpu                   | Command description here | 6                |
| custom_sleep          | Command description here | 6                |
| d                     | Command description here | 6                |
| deaths                | Command description here | 6                |
| debug_strings         | Command description here | 6                |
| disable_all_objects   | Command description here | 6                |
| disable_all_vehicles  | Command description here | 6                |
| disable_backtap       | Command description here | 6                |
| disable_object        | Command description here | 6                |
| disable_timer_offsets | Command description here | 6                |
| disabled_objects      | Command description here | 6                |
| dns                   | Command description here | 6                |
| enable_object         | Command description here | 6                |
| eventdel              | Command description here | 6                |
| events                | Command description here | 6                |
| files                 | Command description here | 6                |
| gamespeed             | Command description here | 6                |
| god                   | Command description here | 6                |
| gravity               | Command description here | 6                |
| hill_timer            | Command description here | 6                |
| hp                    | Command description here | 6                |
| kill                  | Command description here | 6                |
| kills                 | Command description here | 6                |
| lag                   | Command description here | 6                |
| loc_add               | Command description here | 6                |
| loc_del               | Command description here | 6                |
| loc_list              | Command description here | 6                |
| loc_listall           | Command description here | 6                |
| log                   | Command description here | 6                |
| log_name              | Command description here | 6                |
| log_note              | Command description here | 6                |
| log_rotation          | Command description here | 6                |
| lua                   | Command description here | 6                |
| lua_api_v             | Command description here | 6                |
| lua_call              | Command description here | 6                |
| lua_list              | Command description here | 6                |
| lua_load              | Command description here | 6                |
| lua_unload            | Command description here | 6                |
| m                     | Command description here | 6                |
| mag                   | Command description here | 6                |
| map_download          | Command description here | 6                |
| map_load              | Command description here | 6                |
| map_next              | Command description here | 6                |
| map_prev              | Command description here | 6                |
| map_query             | Command description here | 6                |
| map_skip              | Command description here | 6                |
| map_spec              | Command description here | 6                |
| mapcycle_add          | Command description here | 6                |
| mapcycle_begin        | Command description here | 6                |
| mapcycle_del          | Command description here | 6                |
| mapvote               | Command description here | 6                |
| mapvote_add           | Command description here | 6                |
| mapvote_begin         | Command description here | 6                |
| mapvote_del           | Command description here | 6                |
| mapvotes              | Command description here | 6                |
| max_idle              | Command description here | 6                |
| max_votes             | Command description here | 6                |
| motd                  | Command description here | 6                |
| msg_prefix            | Command description here | 6                |
| mtv                   | Command description here | 6                |
| nades                 | Command description here | 6                |
| network_thread        | Command description here | 6                |
| no_lead               | Command description here | 6                |
| object_sync_cleanup   | Command description here | 6                |
| packet_limit          | Command description here | 6                |
| ping_kick             | Command description here | 6                |
| query_add             | Command description here | 6                |
| query_del             | Command description here | 6                |
| query_list            | Command description here | 6                |
| reload                | Command description here | 6                |
| reload_gametypes      | Command description here | 6                |
| remote_console        | Command description here | 6                |
| remote_console_list   | Command description here | 6                |
| remote_console_port   | Command description here | 6                |
| report                | Command description here | 6                |
| rprint                | Command description here | 6                |
| s                     | Command description here | 6                |
| sapp_console          | Command description here | 6                |
| sapp_mapcycle         | Command description here | 6                |
| sapp_rcon             | Command description here | 6                |
| save_respawn_time     | Command description here | 6                |
| save_scores           | Command description here | 6                |
| say_prefix            | Command description here | 6                |
| score                 | Command description here | 6                |
| scorelimit            | Command description here | 6                |
| scrim_mode            | Command description here | 6                |
| set_ccolor            | Command description here | 6                |
| setcmd                | Command description here | 6                |
| sh                    | Command description here | 6                |
| sj_level              | Command description here | 6                |
| spawn                 | Command description here | 6                |
| spawn_protection      | Command description here | 6                |
| t                     | Command description here | 6                |
| team_score            | Command description here | 6                |
| teamup                | Command description here | 6                |
| text                  | Command description here | 6                |
| timelimit             | Command description here | 6                |
| tp                    | Command description here | 6                |
| unblock_object        | Command description here | 6                |
| ungod                 | Command description here | 6                |
| unlag                 | Command description here | 6                |
| unlock_console_log    | Command description here | 6                |
| usage                 | Command description here | 6                |
| v                     | Command description here | 6                |
| var_add               | Command description here | 6                |
| var_conv              | Command description here | 6                |
| var_del               | Command description here | 6                |
| var_list              | Command description here | 6                |
| var_set               | Command description here | 6                |
| vdel                  | Command description here | 6                |
| vdel_all              | Command description here | 6                |
| venter                | Command description here | 6                |
| vexit                 | Command description here | 6                |
| wadd                  | Command description here | 6                |
| wdel                  | Command description here | 6                |
| wdrop                 | Command description here | 6                |
| yeye                  | Command description here | 6                |
| zombies               | Command description here | 6                |

# Ban command examples:

- `/hash_ban` `1` `-y 1` `-mo 6` `-r "caught cheating"`
    - This will ban player 1 by hash for 1 year, 6 months with the reason "caught cheating".<br><br>

- `/hash_ban` `1`
    - This will ban player 1 by hash permanently.<br><br>

- `/ip_ban` `1` `-h 1` `-m 30` `-r "caught cheating"`
    - This will ban player 1 by IP for 1 hour, 30 minutes with the reason "caught cheating".<br><br>

- `/ip_ban` `1`
    - This will ban player 1 by IP permanently.<br><br>

- `/name_ban` `1` `-r "explicit name"`
    - This will blacklist player 1's name with the reason "explicit name".<br><br>

- `/name_ban` `penis`
    - This will blacklist the name "penis".<br><br>

- `/ip_mute` `1` `-m 10` `-r "spamming"`
    - This will text-ban player 1 by IP for 10 minutes with reason "spamming".<br><br>

- `/hash_mute` `1` `-d 5` `-r "constant swearing"`
    - This will text-ban player 1 by hash for 5 days with reason "spamming".

**TIP:**<br>
The order of the flags <ins>doesn't matter</ins>, but the player id <ins>must</ins> be the first argument.<br>

**Pirated Hashes:**<br>
> Shared CD Key hashes are detected automatically.<br>
> If a player has a shared CD Key hash, the admin will be informed<br>
> and will have to confirm the ban by typing */confirm*.<br>
> Otherwise, the action will time out after 10 seconds.