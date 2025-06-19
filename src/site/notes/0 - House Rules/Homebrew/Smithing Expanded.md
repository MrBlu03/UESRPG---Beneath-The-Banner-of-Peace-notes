---
{"dg-publish":true,"permalink":"/0-house-rules/homebrew/smithing-expanded/"}
---

# Crafting Rules & Modifications
*An adaptation of weapon modifications from the **Book of Circles**, and an expansion of crafting material requirements. Credit to all contributors of the Book of Circles, as well as **Tutorial.tuna** for crafting times.*

---

## New Crafting Steps

### Step 1: Determine Item
The character must choose the item they wish to create. Some items cannot be created (e.g., items that occur only naturally), so the GM should use discretion. The character must also choose the **quality** of the item, which, when combined with its base price, determines its market value.

#### Step 1a: Determine Modification
If eligible, select one or more modifications from the Weapon, Shield, or Armor tables below. The number of upgrades allowed (including scaled levels) is equal to **half the character's Profession: Smithing rank**, rounded up (e.g., 1 for rank 1, 3 for rank 5).

---

### Step 2: Gather Raw Materials
Collect the required **core materials** and **fastenings** as listed in the *Material Requirements & Crafting Time* section below. Requirements vary based on the item and modifications selected.

---

### Step 3: Determine Test Difficulty
Base difficulty is set by the **item’s quality**. Materials and modifications apply modifiers. Use the tables below to determine initial and adjusted difficulty.

#### Step 3a: Modify Test Difficulty
Add difficulty modifiers from all applied modifications to the base difficulty to get the final crafting test difficulty.

---

### Step 4: Make the Crafting Test
Make a skill test using the difficulty from Step 3. Most crafted items use **Profession: Smithing**; others may use a relevant **Profession: Field** skill.  
- **Failure**: No item is produced.  
- **Critical success**: Crafting time is halved.  
- **Tools**: The appropriate tools and facilities (e.g., forge for smithing) are required.  
- **Duration**: Crafting takes several hours to days depending on complexity; the character must be focused throughout.

---

### Runed Weapons & Armor
Characters with **Enchanting** knowledge may add magical runes:
- Requires a successful **Enchant test** during crafting.
- **Success**: Adds the *Magic* quality and +1 Magic AR to armor.
- **Failure**: Item lacks the *Magic* quality and may not be enchanted again.

---

### Repairing Weapons & Armor
Weapons and armor can be repaired with a **Profession: Smithing** test:
- Takes ~1 hour.
- Requires **1 unit of the core material** used in the item.
- On success: Reduce `Damaged(X)` by degrees of success.

---

## Modifications

### Weapons

- **Serrated Edge**  
  *Cost:* 1 core unit  
  *Applies to:* All weapons and slashing arrows  
  *Difficulty:* -10  
  *Effect:* Apply `Bleeding(1)` on damage after mitigation.

- **Parrying Hooks**  
  *Cost:* 1 core unit  
  *Applies to:* Longswords, Greatswords  
  *Difficulty:* -15  
  *Effect:* Gains the *Dueling Weapon* quality when used two-handed.

- **Basket Hilt**  
  *Cost:* 1 core unit  
  *Applies to:* All 1H swords  
  *Difficulty:* -15  
  *Effect:* +20 vs Disarm, +5 to Parry, -5 to offensive Combat Style tests.

- **Spiked Head**  
  *Cost:* 1 core unit  
  *Applies to:* Mace, Warhammer, Maul  
  *Difficulty:* -10 × X (max 3)  
  *Effect:* Increases *Crushing* value by X.

- **Fitted Grip**  
  *Cost:* 1 fastening  
  *Applies to:* All melee weapons  
  *Difficulty:* -10  
  *Effect:* +5 to Combat Style for the user, -5 for others.

- **Wavy Blade**  
  *Cost:* 1 core unit  
  *Applies to:* Non-exotic bladed weapons  
  *Difficulty:* -20  
  *Effect:* +5 to Counter Attacks, -5 to Parry, +10 bonus vs polearms.

- **Downturned Crossguard**  
  *Cost:* 1 core unit  
  *Applies to:* Bladed weapons  
  *Difficulty:* -15  
  *Effect:* +10 to Disarm against 1H weapons.

---

### Armor

- **Spiked Armor**  
  *Cost:* 2 core units  
  *Applies to:* Full Chest (AR 4+)  
  *Difficulty:* -10  
  *Effect:* +1 ENC. Deals 1d4 *Crushing* damage on grapples.

- **Fur Lined**  
  *Cost:* ½ unit cost of Fur × X (rounded up)  
  *Applies to:* All armor  
  *Difficulty:* -5 × X (max 3)  
  *Effect:* +10 × X to resist cold exposure (Endurance tests).

- **Reinforced Knuckles**  
  *Cost:* 1 core unit  
  *Applies to:* Arm armor  
  *Difficulty:* Based on Cestus material  
  *Effect:* +1 ENC. Functions as a cestus. Weapon is part of the armor, cannot be disarmed.

- **Locked Gauntlet**  
  *Cost:* 1 core unit  
  *Applies to:* Full Arm (AR 4+)  
  *Difficulty:* -10  
  *Effect:* Locks 1H weapon in place. While locked: -10 to Parry, hand can't be used until unlocked (Secondary Action).

- **Ridged Shoulder Guard**  
  *Cost:* 2 core units  
  *Applies to:* Full Chest (AR 4+)  
  *Difficulty:* -15  
  *Effect:* On a hit to the Head, roll d10. On 9–10, hit is redirected to the Body.

---

### Shields

- **Shield Spike**  
  *Cost:* 1 core unit (2 for Tower)  
  *Difficulty:* -5  
  *Effect:* Adds 1d4 *Crushing(2)* damage to Bash.

- **Shield Bumps**  
  *Cost:* 1 core unit  
  *Difficulty:* -10 × X  
  *Effect:* +5 × X bonus to block bladed weapons (including arrows).

- **Fastening Straps**  
  *Cost:* 1 fastening  
  *Difficulty:* -5  
  *Effect:* Allows shield to be strapped as a Secondary Action. Immune to Disarm while strapped.

- **Strapped Dagger**  
  *Cost:* 2 fastenings, 1 dagger  
  *Difficulty:* -5  
  *Effect:* Dagger can be drawn as a Free Action from a hidden sheath.

---

## Material Requirements & Crafting Time

### Material Requirements

| Item             | Core Units | Fastenings |
|------------------|------------|------------|
| Partial Chest    | 3          | 3          |
| Full Chest       | 5          | 4          |
| Partial Limb     | 1          | 1          |
| Full Limb        | 2          | 2          |
| Shield           | 3          | 2          |
| Buckler          | 1          | 1          |
| Tower Shield     | 4          | 3          |
| Targe            | 2          | 1          |
| 1H Weapons       | 1          | 1          |
| 1.5H Weapons     | 2          | 2          |
| 2H Weapons       | 3          | 3          |
| Small Misc.      | 1          | 1          |
| Medium Misc.     | 2          | 2          |
| Large Misc.      | 4          | 3          |
| 10 Arrows/Bolts  | 1          | 1          |
| Complex Weapon   | 2          | 4          |
| Bows             | 1          | 3          |

- **Repair**: Always requires **1 unit** per repair test.
- **Crafting a unit**: Requires 2 raw units (except Steel = 2 Iron + 1 Corundum).
- **Leather/Fur**: 2 hides → 1 leather; 1 pelt → 1 fur.
- **Fastenings**: 1 leather → 4 fastenings.

---

### Material Unit Costs

| Material     | Cost |  
|--------------|------|  
| Fastening    | 1    |  
| Cloth        | 1    |  
| Hide         | 3    |  
| Fur          | 4    |  
| Leather      | 5    |  
| Iron         | 10   |  
| Bonemold     | 10   |  
| Steel        | 20   |  
| Moonstone    | 20   |  
| Dreugh Hide  | 25   |  
| Orichalcum   | 25   |  
| Dwemer       | 30   |  
| Mithril      | 70   |  
| Adamantium   | 80   |  
| Malachite    | 150  |  
| Ebony        | 200  |  
| Stalhrim     | 300  |  
| Dragonbone   | 1000 |

*All units weigh 0.2, except Fastenings (0.1).*

---

### Crafting Time

*1 crafting day = 12 hours*

| Item             | Time     |
|------------------|----------|
| Partial Chest    | 24 hrs   |
| Full Chest       | 36 hrs   |
| Partial Limb     | 12 hrs   |
| Full Limb        | 18 hrs   |
| Shield           | 24 hrs   |
| Buckler          | 12 hrs   |
| Tower Shield     | 36 hrs   |
| Targe            | 18 hrs   |
| 1H Weapons       | 24 hrs   |
| 1.5H Weapons     | 36 hrs   |
| 2H Weapons       | 48 hrs   |
| Small Misc.      | 6 hrs    |
| Medium Misc.     | 12 hrs   |
| Large Misc.      | 18 hrs   |
| 10 Arrows/Bolts  | 12 hrs   |
| Complex Weapon   | 48 hrs   |
| Bows             | 36 hrs   |

- **Material Difficulty**: Each -10 increases crafting time by +6 hours.  
- **Modification Difficulty**: Each -10 adds +2 hours.
