# 🏪 ChestShop Tutorial 🛒

Welcome to the **ChestShop Tutorial**! 🎉 With ChestShop, you can create your own shops using signs and chests, making it
easy to buy and sell items. Follow this step-by-step guide to set up your shop efficiently.

---

## 📚 Table of Contents

1. [Building Your Shop](#-step-1-build-your-shop)
2. [Chest Placement](#-step-2-place-a-chest)
3. [Stock Management](#-step-3-stock-the-chest)
4. [Sign Configuration](#-step-4-create-a-sign)
5. [Transaction Process](#-step-5-how-customers-buy-or-sell-items)

## 🏗️ Step 1: Build Your Shop

Begin by constructing a designated area for your shop. Be creative as you can, an appealing shop design can attract more
customers!

Pro Tip: Use these materials for best results:

- `Oak Planks`
- `Glass Panes`
- `Item Frames`
- `Glowstone`

<details>
<summary>📸 Example Shop Designs</summary>
<br>
<img src="/misc/assets/images/TUTORIALS/chestshop_example.png" alt="JeriCraft Logo" width="1920" />
</details>

---

## 📦 Step 2: Place a Chest

<div align="left">
  <img src="https://img.shields.io/badge/Important-Note-red?style=flat-square" alt="Important">
  <sup>Double chests supported for high-volume shops!</sup>
</div>

Position your chest in an accessible location. Ensure clear line of sight to the sign area.

---

## 📈 Step 3: Stock the Chest

Fill the chest with the items you wish to sell. Organizing your stock efficiently will make it easier for customers to
find what they need. For example:

1. High-demand resources (`Diamonds`, `Netherite`)
2. Building materials (`Oak_Logs`, `Stone`)
3. Rare items (`Enchanted_Golden_Apples`, `Dragon_Egg`)
4. Common items (`Iron_Ingot`, `Gold_Ingot`)
5. Consumables (`Apple`, `Bread`)

---

## 📋 Step 4: Create a Sign

Create your shop sign with this exact formatting:

```none
[Shop Owner]       Auto-filled by system
[Quantity]         Stack size: 1-64
[Price]            Format: B/S [Amount] or B X : S Y
[Item Name]        Use /iinfo for ID
```

**Example Configurations:**

1. Basic Shop (Single Price):

```none
Chalwk          Auto-filled
16              Item Quantity
B 100           Buy Price
Diamond         Item Name (Must match exactly)
```

2. Advanced Shop (Multiple Prices):

```none
Chalwk          Auto-filled
16              Item Quantity
B 100 : S 25    Buy Price and Sell Price
Diamond         Item Name (Must match exactly)
```

<details> <summary>🛠️ Advanced Configuration (Click to Expand)</summary>

| **Format**   | **Description**                    | **Example**  |
|--------------|------------------------------------|--------------|
| B 100        | Shop sells to players for 100 each | B 100        |
| S 50         | Shop buys from players for 50 each | S 50         |
| B 100 : S 25 | Dual pricing (Buy/Sell)            | B 100 : S 25 |
| ? 75         | Auto-convert to best deal          | ? 75         |

💡 Pro Tip: The colon : must have spaces on both sides when using dual pricing!

</details>

---

## 💰 Step 5: How Customers *Buy* or *Sell* Items

| **Action**      | **Click Type**          | **Transaction**                       |
|-----------------|-------------------------|---------------------------------------|
| Purchase Single | `Right Click`           | 🔼 Takes 1 transaction from chest     |
| Purchase Stack  | `Shift` + `Right Click` | 🔼 Takes max stacks (inventory space) |
| Sell Single     | `Left Click`            | 🔽 Adds 1 transaction to chest        |
| Sell Stack      | `Shift` + `Left Click`  | 🔽 Adds max stacks (chest space)      |

💡 Pro Tip: You can hold `Shift` while clicking to buy or sell multiple items at once.

---

<div align="center"> <h3 style="color: #2ecc71; border: 2px solid #27ae60; padding: 10px; border-radius: 5px;"> 🎊 Shop Successfully Created! 🎊 </h3> <p>Your shop is now contributing to JeriCraft's economy!</p> <img src="https://img.shields.io/badge/Next_Steps-Create_Shop_Hub-orange?style=for-the-badge" alt="Next Steps"> </div><hr><div align="center"> <sup>Need help? Contact our support team on Discord or create an issue on <a href="https://github.com/Chalwk/JeriCraftDocs/issues">GitHub</a></sup> <br> <img src="https://img.shields.io/badge/Server_Online-Yes-brightgreen?style=flat-square"> <img src="https://img.shields.io/badge/Uptime-99.9%25-important?style=flat-square"> </div>