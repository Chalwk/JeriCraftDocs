# 🏗️ JeriCraft Region Management Commands

### 🎯 Introduction

Welcome to the JeriCraft Region Management tutorial! 📚 Protecting your builds and managing access to specific areas is
essential for a seamless and enjoyable experience on our server. 💻 In this guide, we will cover the necessary commands
to help you effectively manage your regions, collaborate with others, and make the most out of your protected areas.

---

# Table of Contents

1. 🎯 [Introduction](#-introduction)
2. 🔺 [Defining Corners](#-defining-corners)
3. 🗺️ [Expanding Regions](#-expanding-regions)
    - [Syntax](#syntax)
    - [Example](#example)
4. 🔐 [Claiming and Removing Regions](#-claiming-and-removing-regions)
5. 🌟 [Max Claim Volume](#-max-claim-volume)
    - [Region Dimensions and Volume](#region-dimensions-and-volume)
6. 📖 [Displaying Region Information](#-displaying-region-information)
7. 📝 [Listing Owned Regions](#-listing-owned-regions)
8. 👥 [Adding and Removing Members and Owners](#-adding-and-removing-members-and-owners)
9. 🔮 [Setting Region Flags](#-setting-region-flags)
    - [Syntax](#syntax-1)
    - [Example](#example-1)
10. 🌟 [Conclusion](#-conclusion)

---

## 🔺 Defining Corners

To create a region, you must first define its corners.

1. **Stand at one corner** of the area you want to protect.
2. **Use the command**: `/pos1`  
   This marks the first corner of your region.
3. **Move to the opposite corner** of your desired region.
4. **Use the command**: `/pos2`  
   This marks the second corner of your region and establishes the boundaries.

Once you've defined the two corners, the area between them will be the protected region.

---

## 🗺️ Expanding Regions

You can expand your region vertically or horizontally using the `expand` command:

### Syntax:

`expand <vert|<amount> <amount> [reverseAmount] [direction]`

- **vert**: Expands the region vertically.
- **[amount]**: The number of blocks to expand.
    - **Positive values** expand upwards.
    - **Negative values** expand downwards.
- **[reverseAmount]** *(optional)*: Expands in the opposite direction.
- **[direction]** *(optional)*: Expands in a specific direction (north, south, east, west).

### Example:

`expand vert 10`  
This will expand your region **upwards** by 10 blocks.

---

## 🔐 Claiming and Removing Regions

- **Claim a region**:  
  `rg claim <rg name>`  
  Replace `<rg name>` with the desired name for your region.

- **Remove a region**:  
  `rg remove <rg name>`  
  This will delete the specified region.

---

## 🌟 Max Claim Volume

JeriCraft has a **maximum claim volume** to ensure fair and balanced gameplay for all players. This is the maximum
number of blocks you can claim within a single region, set to **1,000,000 (1 million blocks)**.

### Region Dimensions and Volume:

Regions on JeriCraft are cuboid-shaped, meaning they have six rectangular faces. Here are a few examples of possible
dimensions for a region with a total volume of **1,000,000 blocks**:

| **Region Dimensions** | **Description**           |
|-----------------------|---------------------------|
| **1000 x 1000 x 1**   | A thin, flat region.      |
| **100 x 100 x 100**   | A perfectly cubic region. |
| **500 x 500 x 4**     | A large, shallow region.  |
| **1000 x 500 x 2**    | A large, flat region.     |
| **200 x 200 x 25**    | A tall, thin region.      |
| **100 x 100 x 1000**  | A very tall, thin region. |

Feel free to choose any dimensions within this volume limit to create your region as you see fit! The flexibility allows
for different shapes and structures based on your needs.

For help determining the best dimensions for your region, or if you have any questions, feel free to reach out to our
staff or community for assistance.

---

## 📖 Displaying Region Information

To view detailed information about the region you're standing in, use the following command:

`rg i`  
This will display information such as the region's name, owner, and other important details.

---

## 📝 Listing Owned Regions

To see a list of all regions you own, use the command:

`rg list`  
This will display a list of all regions you have claimed.

---

## 👥 Adding and Removing Members and Owners

You can manage who has access to your region by adding and removing members or owners.

- **Add a member**:  
  `rg addmember <rg name> <player>`  
  This adds the specified player to your region.

- **Remove a member**:  
  `rg removemember <rg name> <player>`  
  This removes the specified player from your region.

- **Add an owner**:  
  `rg addowner <rg name> <player>`  
  This grants the player owner permissions for your region.

- **Remove an owner**:  
  `rg removeowner <rg name> <player>`  
  This removes the player's owner permissions.

---

## 🔮 Setting Region Flags

You can customize the settings of your region using flags. Flags allow you to modify specific behaviors within your
region, such as preventing mob spawning or enabling PvP.

### Syntax:

`rg flag <rg name> <flag> <value>`

- **[flag]**: The specific setting you want to change (e.g., `mob-spawning`, `pvp`).
- **[value]**: The value you want to assign to the flag (e.g., `deny`, `allow`).

### Example:

`rg flag myregion mob-spawning deny`  
This command will **prevent mobs from spawning** in the "myregion" area. 🚫

For a full list of available region flags, check out
the [Region Flags section](/MINECRAFT/features/features#8-WorldGuard) in the
main documentation.

---

## 🌟 Conclusion

Congratulations! You're now equipped with the knowledge to manage your regions on JeriCraft like a pro. Whether you're
building your dream house or protecting your creations, these commands will help you control and secure your space in
the world.

If you have any questions, need further assistance, or simply want to explore more about region management, don't
hesitate to reach out to our friendly community or server staff. Happy building and managing your regions!