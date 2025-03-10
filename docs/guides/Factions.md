# JeriCraft Factions Guide

Welcome to the **JeriCraft Factions System**! This guide will help you understand how to create and manage your faction,
claim land, build power, and raid enemy territories.

## 📜 Table of Contents

1. [Kingdom Management](#-kingdom-management)
2. [Claiming Land](#-claiming-land)
3. [Membership & Ranks](#-membership--ranks)
4. [Communication](#-communication)
5. [Additional Help](#-additional-help)
6. [Power System](#-power-system)
7. [Raiding & Warfare](#-raiding--warfare)
8. [Faction Relations and Limits](#-faction-relations-and-limits)
9. [Faction Commands Reference](#-faction-commands-reference)
10. [Faction Colors and Relations](#-faction-colors-and-relations)
11. [Economy and Faction Banks](#-economy-and-faction-banks)
12. [Faction Bank Commands](#-faction-bank-commands)
13. [Protection and PvP](#-protection-and-pvp)

---

## 📜 Kingdom Management

> The foundation of any great empire begins with its creation. Establish your own faction, forge alliances, and carve
> your legacy into the lands of JeriCraft. A faction serves as your **kingdom**, a gathering of warriors, builders, and
> rulers under one banner.

| **Action**                  | **Command**                 | **Description**                                                              |
|-----------------------------|-----------------------------|------------------------------------------------------------------------------|
| **Create a faction**        | `/f create <name>`          | Establish your own kingdom and take the throne as its ruler.                 |
| **Faction Description**     | `/f desc <description>`     | Set a short description for your kingdom.                                    |
| **Rename your faction**     | `/f tag <name>`             | Change your kingdom’s official banner (name).                                |
| **View faction details**    | `/f show`                   | Display a full overview of your kingdom, including members, power, and land. |
| **Inspect another faction** | `/f who <name>`             | Gather intelligence on another faction, including its members and power.     |
| **List all factions**       | `/f list`                   | Discover all known kingdoms that roam these lands.                           |
| **Disband your faction**    | `/f disband`                | Dissolve your kingdom, scattering its people and relinquishing its lands.    |
| **Home Management**         | `/f sethome/delhome <name>` | Set or remove your home location (a safe haven for your kingdom).            |

> Once created, you become the **leader** of your faction, wielding the power to **expand your domain**,
> **recruit allies**, and **command your kingdom’s fate**. You can **manage your faction’s land, power, and members** to
> build an empire that stands the test of time.

---

## 📌 Claiming Land

> A kingdom is nothing without its territory! Factions must **claim land** to establish castles, villages, and
> fortifications.

| **Action**           | **Command**      | **Description**                                                    |
|----------------------|------------------|--------------------------------------------------------------------|
| **Claim land**       | `/f claim`       | Seize control of a chunk of land for your kingdom.                 |
| **Unclaim land**     | `/f unclaim`     | Relinquish a previously claimed territory.                         |
| **Unclaim all land** | `/f unclaimall`  | Release all faction-owned land at once.                            |
| **Fill claim**       | `/f fillclaim`   | Automatically claim up to `25` chunks within a `5`-chunk radius.   |
| **Fill unclaim**     | `/f fillunclaim` | Automatically unclaim up to `25` chunks within a `5`-chunk radius. |

> Each chunk of land requires **power** to maintain, and you can only claim as much land as your
**faction’s total power allows**.

- Your **faction’s power** is determined by the number of members and their individual power levels.
- If a member dies, their power decreases, reducing your faction’s ability to claim land.
- Keep your kingdom strong by **recruiting more members** and **avoiding unnecessary deaths** in battle!

---

## 🏹 Membership & Ranks

> A kingdom thrives on its people! Recruit allies, build a loyal court, and manage your ranks wisely.

| **Action**               | **Command**            | **Description**                                   |
|--------------------------|------------------------|---------------------------------------------------|
| **Join a faction**       | `/f join <name>`       | Swear fealty to a faction and become its subject. |
| **Leave a faction**      | `/f leave`             | Renounce your oath and walk your own path.        |
| **Invite a player**      | `/f invite <player>`   | Extend an invitation to a worthy knight or ally.  |
| **Revoke an invitation** | `/f deinvite <player>` | Retract an invitation before it is accepted.      |
| **Kick a player**        | `/f kick <player>`     | Exile a member from your faction.                 |
| **Promote a player**     | `/f mod <player>`      | Elevate a member to a higher rank of leadership.  |

> As a ruler, it is your duty to **build trust** and **reward loyalty**. Strong factions are forged through camaraderie
> and strategy.

- More members mean **more power**, which allows your faction to **claim more land** and expand its influence.
- Grant **leadership roles** to trusted members to help you manage your growing kingdom.

---

## 🛡️ Communication

> A kingdom must have strong communication among its warriors. Use **faction chat** to strategize, plan attacks, and
> share your vision.

| **Action**       | **Command**                                   | **Description**                            |
|------------------|-----------------------------------------------|--------------------------------------------|
| **Faction chat** | `/f chat <alliance/faction/mod/public/truce>` | Send a message to a specific chat channel. |

> Stay connected with your knights and advisors to **coordinate strategies** and **plan attacks**.

---

## ❓ Additional Help

If you ever need guidance, use these commands to **learn more about faction mechanics**.

| **Action**                | **Command**     | **Description**                              |
|---------------------------|-----------------|----------------------------------------------|
| **View faction commands** | `/f help`       | Show a list of faction-related commands.     |
| **View next help page**   | `/f help 2/3/4` | See additional faction commands and options. |

> May your kingdom rise to power, and may your banner be remembered for generations to come! 🏰

---

## ⚡ Power System

> Power determines how much land your faction can **claim** and **defend**.

- **Starting Power:** `0`
- **Maximum Power per Player:** `500`
- **Minimum Power per Player:** `-10`
- **Power Loss Per Death:** `2`
- **Power Regeneration Rate:** `0.2 per minute` (takes 5 minutes to regain 1 power)
- **Offline Power Loss:** `-1 per day`
- **Offline Power Regeneration:** ❌ *Disabled*
- **Max Faction Power:** Unlimited (0 means no cap, extra power acts as a buffer)

> You gain power over time while online, but **death and inactivity** will reduce it!
> Your factions **Power** is the total sum of your members' **power levels** (not mcMMO power level).

---

## ⚔️ Raiding & Warfare

> If your faction’s **claimed land exceeds its power**, **your land becomes vulnerable to raids**!

- **Raidability:** ✅ *Enabled*
- **Raid Triggers:** If a faction’s land is **greater than or equal to** their power.
- **WarZone & Wilderness Power Loss:** ✅ *Enabled* (You lose power when dying in warzones and wilderness.)
- **Power Stealing on Kill:** `50%` (Attackers gain half of the power lost by the victim.)

> Once raidable, **enemy factions can break blocks, loot chests, and take control of your land**! Be strategic and
> manage your faction’s power wisely.

---

## 🤝 Faction Relations and Limits

> Factions can form different types of relationships with other factions, such as alliances,
> truces, or enmity. However, there are limits to how many of each type of relationship a faction can have.

### Types of Relations

- **Ally:** A friendly relationship. Allies can help each other in battles and share resources.
- **Enemy:** A hostile relationship. Enemies can attack and raid each other.
- **Neutral:** A default relationship. Neutral factions are neither friendly nor hostile.
- **Truce:** A temporary peace agreement. Truces prevent PvP between factions.

### Limits on Relations

- **Maximum Allies:** `5`
    - Your faction can form alliances with up to 5 other factions.
- **Maximum Enemies:** `10`
    - Your faction can declare up to 10 other factions as enemies.
- **Maximum Truces:** `5`
    - Your faction can have up to 5 truces with other factions.
- **Neutral Relations:** Unlimited
    - There is no limit to the number of factions your faction can remain neutral with.

### Default Relation

- The default relationship between factions is **Neutral**.
    - This ensures that factions can always revert to a neutral stance if needed.

### Important:

- **Strategic Alliances:** Form alliances with strong factions to protect your territory and gain support in battles.
- **Manage Enemies:** Be cautious when declaring enemies, as you can only have up to 10 at a time.
- **Truces for Peace:** Use truces to temporarily avoid conflict with other factions while focusing on other goals.
- **Neutral Stance:** Staying neutral with most factions can help you avoid unnecessary conflicts and focus on building
  your power.

---

## 🏰 Faction Commands Reference

| Command              | Description                                 |
|----------------------|---------------------------------------------|
| `/f create <name>`   | Create a faction                            |
| `/f invite <player>` | Invite a player to your faction             |
| `/f join <faction>`  | Join a faction                              |
| `/f leave`           | Leave your current faction                  |
| `/f disband`         | Disband your faction (leader only)          |
| `/f claim`           | Claim land for your faction                 |
| `/f unclaim`         | Unclaim the current land chunk              |
| `/f unclaimall`      | Unclaim all faction land                    |
| `/f power`           | View your power stats                       |
| `/f map`             | See the land claimed by factions around you |
| `/f top`             | View the top factions by power              |
| `/f seechunks`       | See claimed chunks (colorized particles)    |

---

## 🎨 Faction Colors and Relations

- **Faction Colors:**
    - **Safezone:** `GOLD`
    - **Warzone:** `DARK_RED`
    - **Wilderness:** `GRAY`
- **Relation Colors:**
    - **Ally:** `LIGHT_PURPLE`
    - **Enemy:** `RED`
    - **Member:** `GREEN`
    - **Neutral:** `WHITE`
    - **Peaceful:** `GOLD`
    - **Truce:** `DARK_PURPLE`

- The colors help identify faction territories and relationships at a glance.
- For example, if you see `DARK_RED`, you’re in a **Warzone**, where PvP is enabled and factions can raid each other.

---

## 💰 Economy and Faction Banks

- **Faction Bank:** Enabled
    - Factions can store money to pay for land claims and other costs.
    - Members with the `moderator` rank or higher can withdraw money.
- **Costs:**
    - **Create a Faction:** `$100`
    - **Claim Land:** `$30` per chunk
- Use the faction bank to pool resources and fund expansions.
- Be mindful of the costs associated with managing your faction.

A kingdom is built on wealth! The **JeriCraft** economy offers various ways for players to earn and spend money:

### 1. Jobs:

> Players can earn money by taking on different jobs within the server. Jobs such as miner, builder, fisherman, and more
> let you accumulate wealth through your activities.

### 2. Chest Shops:

> Players can buy and sell items using their own player-run shops. Set up a chest shop,
> and others can purchase your goods!

### 3. NPC Shops:

> Players can also buy items directly from NPC-run shops, which are available throughout the kingdom.

### 4. Faction Banks:

> Your faction also has its own bank where you can pool resources and fund land claims, repairs,
> and other faction-related costs.

## 💰 Faction Bank Commands

| **Command**                                        | **Description**                                                              |
|----------------------------------------------------|------------------------------------------------------------------------------|
| **/f money**                                       | View the faction's current bank balance.                                     |
| **/f money balance**                               | See the available funds in the faction bank.                                 |
| **/f money deposit <amount> [faction]**            | Deposit a specific amount of money into the faction's bank.                  |
| **/f money ff <amount> <factionfrom> <factionto>** | Transfer money between two factions (from one faction to another).           |
| **/f money fp <amount> <factionfrom> <playerto>**  | Transfer money from a faction to a player.                                   |
| **/f money pf <amount> <playerfrom> <factionto>**  | Transfer money from a player to a faction.                                   |
| **/f money withdraw <amount> [faction]**           | Withdraw a specified amount of money from the faction's bank.                |
| **/f money modify <amount> <faction>**             | Modify the faction's bank balance manually (for admins or authorized users). |

> Use these commands to manage your faction’s finances, transfer funds between factions, and ensure your kingdom's
> financial health is maintained! Manage your faction’s finances wisely, as **money** can play a huge role in
> both *expanding your territory** and **funding your military endeavors**!

---

## 🛡️ Protection and PvP

- **Safe Zones:**
    - No PvP or building allowed.
    - Protected from explosions and mob damage.
- **War Zones:**
    - PvP is always enabled.
    - No building or usage permissions for non-members.
- **Wilderness:**
    - No protections; players can build and PvP freely.
- Safe zones are ideal for new players or trading.
- War zones are high-risk areas for PvP and raiding.

---

## 🛠️ Advanced Features

- **TNT Banking:** Disabled
- **Portals:**
    - Portals can only be created in territory with a minimum relation of `MEMBER`.
- **Spawning:**
    - Certain mobs (e.g., hostile mobs) are prevented from spawning in safe zones and war zones.
- Use portals and spawning rules to your advantage when defending or raiding.

## ⚔️ **Enemy Faction Territory - Denied Commands** ⚔️

> When you enter the claimed territory of an enemy faction, certain commands will be disabled to
> maintain the integrity and balance of the game. These commands are restricted to prevent
> players from easily escaping, teleporting, or getting an unfair advantage while in enemy territory.

### 🚫 **Denied Commands:**

- **/spawn** – Teleport to spawn (disabled in enemy territory)
- **/tpa** – Send teleport requests to others
- **/f sethome** – Set a home location (disabled in enemy territory)
- **/tpahere** – Teleport someone to your location
- **/tpaccept** – Accept a teleport request
- **/f home** – Teleport to your home location

> These restrictions are in place to enhance the challenge and ensure that players cannot easily
> escape or bypass the territorial control of enemy factions.
> Stay alert, strategize carefully, and prepare for battle when venturing into enemy lands!

---

## 📊 Scoreboard and UI

- **Constant Scoreboard:** Enabled
    - Displays faction information, power, and territory status.
    - Updates in real-time as players move between territories.
- The scoreboard provides essential information about your faction and its status.

---

🛡️ **Defend your kingdom, forge alliances, and become the most powerful faction in JeriCraft!** 🏆