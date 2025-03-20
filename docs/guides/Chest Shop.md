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

## 💰 Step 6: How Customers *Buy* or *Sell* Items
<div align="center">
  <table>
    <tr>
      <th>Action</th>
      <th>Click Type</th>
      <th>Transaction</th>
    </tr>
    <tr>
      <td>Purchase Single</td>
      <td><kbd>Right Click</kbd></td>
      <td>🔼 Takes 1 transaction from chest</td>
    </tr>
    <tr>
      <td>Purchase Stack</td>
      <td><kbd>Shift + Right Click</kbd></td>
      <td>🔼 Takes max stacks (inventory space)</td>
    </tr>
    <tr>
      <td>Sell Single</td>
      <td><kbd>Left Click</kbd></td>
      <td>🔽 Adds 1 transaction to chest</td>
    </tr>
    <tr>
      <td>Sell Stack</td>
      <td><kbd>Shift + Left Click</kbd></td>
      <td>🔽 Adds max stacks (chest space)</td>
    </tr>
  </table>
</div>

<div style="background-color: #e3f2fd; padding: 15px; border-radius: 5px; margin-top: 10px;">
💡 <strong>Pro Tip:</strong> Holding <kbd>Shift</kbd> while clicking lets you:
- <span style="color: #2e7d32;">Buy</span> multiple quantities based on your inventory space
- <span style="color: #c62828;">Sell</span> multiple quantities based on chest space
<br>
<small>Transaction size determined by quantity set in your shop sign</small>
</div>

---

## Step 7: Restocking Your Shop 🔄

To restock, simply place more items into the chest. Keeping your inventory full ensures uninterrupted sales.

---

## Step 8: Shop Protection 🛡️

Your shop is automatically protected! Only you can modify or break the chest and sign, ensuring the security of your
inventory.

---

## Step 9: WorldGuard Protected Regions 🛠️

If your shop is located in a **WorldGuard protected region**, you need to enable the `allow-shop` flag for your shop to
function correctly.
Use the following command: `/rg flag <region id> allow-shop allow`

---

## **You're All Set! 🎉**

Congratulations! Your ChestShop is now fully operational and ready to contribute to JeriCraft’s thriving economy. Happy
trading!