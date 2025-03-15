## This Guide is no longer in use. See the [Factions Guide](/docs/guides/Factions.md)

---

### 🎯 Introduction

Welcome to the JeriCraft Region Management tutorial! Protecting your builds and managing access to specific areas is
essential for a seamless and enjoyable experience on our server. In this guide, we will cover the necessary commands
to help you effectively manage your regions, collaborate with others, and make the most out of your protected areas.

---

# Table of Contents

1. 🎯 [**Introduction**](#-introduction)
2. 🔺 [**Defining Corners**](#-defining-corners)
3. 🗺️ [**Expanding Regions**](#-expanding-regions)
4. 🔐 [**Claiming and Removing Regions**](#-claiming-and-removing-regions)
5. 🌟 [**Max Claim Volume and Region Limits**](#-max-claim-volume-and-region-limits)
6. 📖 [**Displaying Region Information**](#-displaying-region-information)
7. 📝 [**Listing Owned Regions**](#-listing-owned-regions)
8. 👥 [**Adding and Removing Members and Owners**](#-adding-and-removing-members-and-owners)
9. 🔮 [**Setting Region Flags**](#-setting-region-flags)
10. 🌟 [**Conclusion**](#-conclusion)

---

## 🔺 Defining Corners

To create a region, you must first define its corners.

1. **Stand at one corner** of the area you want to protect.
2. **Use the command**: `//p1`
   This marks the first corner of your region.
3. **Move to the opposite corner** of your desired region.
4. **Use the command**: `//p2`
   This marks the second corner of your region and establishes the boundaries.

Once you've defined the two corners, the area between them will be the protected region.

---

## 🗺️ Expanding Regions

You can expand your region vertically or horizontally using the `//expand` command:

Syntax: `//expand <vert|<amount> <amount> [reverseAmount] [direction]`

- **vert**: Expands the region vertically.
- **[amount]**: The number of blocks to expand.
    - **Positive values** expand upwards.
    - **Negative values** expand downwards.
- **[reverseAmount]** *(optional)*: Expands in the opposite direction.
- **[direction]** *(optional)*: Expands in a specific direction (north, south, east, west).

Example: `//expand vert 10`

This will expand your region **upwards** by 10 blocks.

---

## 🔐 Claiming and Removing Regions

- **Claim a region**: `/rg claim <rg name>`  
  Replace `<rg name>` with the desired name for your region.

- **Remove a region**: `/rg remove <rg name>`  
  This will delete the specified region.

---

## 🌟 Max Claim Volume and Region Limits

To ensure a fair and balanced experience for all players, JeriCraft has specific limitations on the number of blocks and
regions you can claim.

### **Max Claim Volume per Region**:

Each individual region you claim can have a maximum volume of **25,000 blocks**. This means each region can be up to
25,000 blocks in size, but you can claim multiple regions as long as they don't exceed the limit.

### **Max Regions per Player**:

Each player can own up to **3 regions**. This means you can claim multiple areas, but you will be limited to a maximum
of 5 separate regions. This ensures that everyone has a fair opportunity to claim space while preventing excessive land
ownership by a single player.

These limits help maintain a balanced gameplay environment and make sure there's plenty of space for everyone to build
and explore!

---

### Region Dimensions and Volume:

Regions on JeriCraft are cuboid-shaped, meaning they have six rectangular faces. Here are a few examples of possible
dimensions for a region with a total volume of **25,000 blocks** (the new maximum claim volume):

| **Region Dimensions** | **Description**           |
|-----------------------|---------------------------|
| **250 x 100 x 1**     | A thin, flat region.      |
| **50 x 50 x 10**      | A perfectly cubic region. |
| **100 x 100 x 2.5**   | A shallow, flat region.   |
| **250 x 100 x 1**     | A large, flat region.     |
| **100 x 50 x 5**      | A tall, thin region.      |
| **50 x 50 x 10**      | A very tall, thin region. |

Because each individual region you claim can have a maximum volume of **25,000 blocks**, you can still claim multiple
regions, as long as their combined volume doesn’t exceed the limit. Feel free to choose any dimensions within this
volume limit to create your region as you see fit! The flexibility allows for different shapes and structures based on
your needs. For help determining the best dimensions for your region, or if you have any questions, feel free to reach
out to our staff or community for assistance.

---

## 📖 Displaying Region Information

To view detailed information about the region you're standing in, use the following command: `/rg i`  
This will display information such as the region's name, owner, and other important details.

---

## 📝 Listing Owned Regions

To see a list of all regions you own, use the command: `/rg list`  
This will display a list of all regions you have claimed.

---

## 👥 Adding and Removing Members and Owners

You can manage who has access to your region by adding and removing members or owners.

- **Add a member**: `/rg addmember <rg name> <player>`
  This adds the specified player to your region.

- **Remove a member**: `/rg removemember <rg name> <player>`  
  This removes the specified player from your region.

- **Add an owner**: `/rg addowner <rg name> <player>`  
  This grants the player owner permissions for your region.

- **Remove an owner**: `/rg removeowner <rg name> <player>`  
  This removes the player's owner permissions.

---

## 🔮 Setting Region Flags

You can customize the settings of your region using flags. Flags allow you to modify specific behaviors within your
region, such as preventing mob spawning or enabling PvP.

Syntax: `/rg flag <rg name> <flag> <value>`

- **[flag]**: The specific setting you want to change (e.g., `use`, `pvp`).
- **[value]**: The value you want to assign to the flag (e.g., `deny`, `allow`).

Example: `/rg flag myregion use deny`  
This command will **prevent players from using blocks** within the region named `myregion`.

For a full list of available region flags, check out
the [Region Flags section](/docs/features/features.md#worldguard) in the main documentation.

---

## 🌟 Conclusion

Congratulations! You're now equipped with the knowledge to manage your regions on JeriCraft like a pro. Whether you're
building your dream house or protecting your creations, these commands will help you control and secure your space in
the world.

If you have any questions, need further assistance, or simply want to explore more about region management, don't
hesitate to reach out to our friendly community or server staff. Happy building and managing your regions!