# Isekaid
# Table of Contents
1. [Early stage](#early)
    1. [Grinding lvl 1-60](#early2)
    2. [Spending gold](#early3)
2. [End game](#end)
    1. [Map grinding lvl 60+](#end)
    2. [Dungeons](#end)
3. [Gatcha](#gatcha)
    1. [Fusing](#gatcha1)
    2. [Pet summoning](#gatcha2)
4. [Commands](#command)

## Early stage <a name="early"></a>
### Grinding lvl 1-60 <a name="early2"></a>
- Start with the Rogue class.
- Add all stat points to str and health
(The rest of the statistics are unnecessary)
```
$stat Health <amount>
$stat Strength <amount>
```
- At level 10, choose the Assassin subclass and learn the 'backstab' skill at lvl 10
```
$learn backstab
```

```
Backstab

Base Damage
90% Attack
Description
Ignores 30% of the opponent's defense
```

### Spending gold <a name="early3"></a>
Spend all the gold on summoning a pet Until you manage to summon a golem try not to bother with equipment, use only what you collect.
```
$buy summon
```
## End game <a name="end"></a>
### Map grinding lvl 60+ <a name="end1"></a>
- Change your class to Swordsman and learn 'puncture'
```
$buy Classchange Potion
```
```
$learn puncture
```
```
Puncture

Base Damage
100% Attack
Description
Ignores 30% of the opponent's defense

```
### Dungeons <a name="end2"></a>

>under development

## Gatcha <a name="gatcha"></a>
At this moment this is hardest game mechanic because it's based purly on your luck.
### Fusing <a name="gatcha1"></a>
Fusing is the upgrading of items. It involves combining two of the same items with the same upgrade rank. E.g.:
Steel sword 2* with Steel sword 2* will give us one Steel sword 3*.

#### Best in slot item list

I personally think that it is not worthwhile to upgrade items that do not have maximum statistics

Each item rarity has its cap on statistics:
Common - 5
Rare - 10
Epic - 15
Legendary - 20
Mythic - 25 (I'm not sure, I have yet to meet anyone who has obtained mythical weapons from dungeons)

Rare:
| Armor               | Weapon          |
|---------------------|-----------------|
| Mithril Chestplate  | Warped Fang     |
| Ivory Vest          | Steel Sword     |
| Infernal Armor      | Elderwood Staff |

Epic:
|Armor| Weapon            |
|-----|-------------------|
|     | Skeletal Shortbow |
|     | Cosmic Staff      |

Legendary:
|Armor| Weapon            |
|-----|-------------------|
|     | Abyssal Dagger    |

#### Odds
So now a little math about statistics
Fusing works by drawing from all statistics
For Eg.:
```
Rare Sword 1

Strength (s) - 10
Strength (s) - 10

Rare Sword 2

Strength (s) - 10
Health (h)   - 10

```
So the chance of getting 2x Str is:
```
Slot 1: [s,s,s,h] = 3/4 chances of drawing strength
Slot 2: [s,s,s,h] = 3/4 chances of drawing strength

So the chance of drawing 2x str is 3/4 * 3/4 = 9/16

For 2x HP you have:
Slot 1: [s,s,s,h] = 1/4 chances of drawing health
Slot 2: [s,s,s,h] = 1/4 chances of drawing health

So the chance of drawing 2x Hp is 1/4 * 1/4 = 1/16

6/16 is the chance to draw hp/str or str/hp
```
Upgrading epic items is even crazier.

### Pet summoning <a name="gatcha2"></a>

## Commands <a name="command"></a>
```
$start      - Start the game
$subclass   - After level 10 you choose a subclass

$p          - Shows statistics
$bal        - Shows gold/keys
$sv         - Shows skill description
$skills     - Shows skills you equip
$skilltree  - Shows skill tree for your class/subclass
$learn      - Equip skill

$map        - Map grinding
$dungeon    - Dungeon list
$challenge  - Dungeon entry

$shop       - Shop list
$buy        - Buy from shop

$fuse       - Item fusing

$drop       - Drop item, or multiple items [1,2,3]
$dropall    - Drop all items with specific rarity
$sell       - Sell materials

$equip      - Equip items
$select     - Equip pet
$view       - View item statistics
$petview    - Check pet statistics

$lb         - General leader board
$lb fish    - Fishing leader board
$lb gold    - Gold leader board
```
