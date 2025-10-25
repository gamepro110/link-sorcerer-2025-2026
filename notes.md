# notes

| stat  |  mod  | score | calc                                    |
| :---: | :---: | :---: | --------------------------------------- |
|  str  |  -1   |   8   | 8                                       |
|  dex  |  +1   |  13   | 13                                      |
|  con  |  +3   |  16   | 15+race(1)                              |
|  int  |  +0   |  10   | 10                                      |
|  wis  |  +1   |  12   | 12                                      |
|  cha  |  +3   |  16   | 14+race(2)                              |
|  hp   |   -   |  23   | 6 + con(3) + (4 + con(3) * (lv(3) - 1)) |

---

| ability      | score | calc              |
| ------------ | :---: | ----------------- |
| AC           |  11   | 10+dex(+1)        |
| spell attack |  +5   | mod(+3)+prof(2)   |
| spell save   |  13   | 8+mod(+3)+prof(2) |

---

| saves | score | calc            | advantage + reason         |
| ----- | :---: | --------------- | -------------------------- |
| STR   |  -1   | mod(-1)         |                            |
| DEX   |  +1   | mod(+1)         |                            |
| CON   |  +5   | mod(+3)+prof(2) |                            |
| INT   |  +0   | mod(+0)         |                            |
| WIS   |  +1   | mod(+1)         | always, telepathic insight |
| CHA   |  +5   | mod(+3)+prof(2) | always, telepathic insight |

---

> [!Note]
> known cantrips: 4  
> known spells: 8 = 4 (class lv) + 2 (subclass 1st lv) + 2 (subclass 3rd lv)

| spell/skill slot | available | used  |
| :--------------: | :-------: | :---: |
| restore balance  |  prof(2)  |   0   |
|  sorcery points  |     3     |   0   |
|      1st lv      |     4     |   0   |
|      2nd lv      |     2     |   0   |
|      3rd lv      |     0     |   0   |
|      4th lv      |     0     |   0   |
|      5th lv      |     0     |   0   |

---

|                 |       |
| --------------- | :---: |
| current hp      |  23   |
| max hp          |  23   |
| initiative      |  +0   |
| gold            |  60   |
| known cantrips  |   0   |
| prepared spells |   0   |

---

| meta magic    | cost | effect                                                                      |
| ------------- | ---- | --------------------------------------------------------------------------- |
| distant spell | 1    | range 5ft+ -> doubles, range touch -> 30ft                                  |
| seeking spell | 2    | miss attack roll for spell and miss, 2 sp to reroll d20, must use new roll. |

---

| sorcerer lv | learned clockwork spell                 |
| ----------- | --------------------------------------- |
| 1st         | alarm, protection from evil and good    |
| 2nd         | protection from evil and good -> shield |
| 3rd         | aid, lesser restoration                 |
| 4th         |                                         |
| 5th         |                                         |
| 6th         |                                         |
| 7th         |                                         |
| 8th         |                                         |
| 9th         |                                         |
| 10th        |                                         |

## action economy

### action

| name                                                     | requirement         | note                                                                                       |
| -------------------------------------------------------- | ------------------- | ------------------------------------------------------------------------------------------ |
| [shoot light crossbow](./inventory/light-crossbow.md)    | 1 bolt + two‑handed | 80/320ft 1d8+1 piercing, bonus-action reload                                               |
| [acid splash](./spells/cantrip/acid-splash.md)           |                     | 60ft, target 1 or 2 within 5ft of each other, dex save **1d6** acid on failed save         |
| [chill touch](./spells/cantrip/chill-touch.md)           |                     | spell attack, 120ft, **1d8** necrotic on hit                                               |
| [dancing lights](./spells/cantrip/dancing-lights.md)     |                     | 120ft, concentration up to 1 min                                                           |
| [fire bolt](./spells/cantrip/fire-bolt.md)               |                     | spell attack, 120ft, **1d10**                                                              |
| [magic missile](./spells/lv1/magic-missile.md)           |                     | auto hit, 3 X **1d4+1** force dmg                                                          |
| [silent image](./spells/lv1/silent-image.md)             |                     | concentration, visual only, 60ft range, 15ft cube                                          |
| [thunderwave](./spells/lv1/thunderwave.md)               |                     | 15ft cone, con save, **2d8** thunder dmg + pushed 10ft on success, fail half dmg + no push |
| [aid](./spells/lv2/aid.md)                               |                     | concentration 8h, 30ft range, choose 3, each get +5 max and current hp                     |
| [enlarge/reduce](./spells/lv2/enlarge-reduce.md)         |                     | concentration 1min, 30ft range                                                             |
| [lesser restoration](./spells/lv2/lesser-restoration.md) |                     | touch, cure 1 condition or disease, see chart in spell                                     |

### bonus actions

| name                     | requirement      | note                                                             |
| ------------------------ | ---------------- | ---------------------------------------------------------------- |
| convert sp to spell slot | spend sp         | [see table](./class_features.md#level-2-font-of-magic-phb14-p99) |
| convert spell slot to sp | spend spell slot | [see table](./class_features.md#level-2-font-of-magic-phb14-p99) |

### reaction

| name                                                                   | requirement                                                      | note                   |
| ---------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------------------- |
| [restore balance](./class_features.md#level-1-restore-balance-tce-p68) | creature i see within 60 ft is about to roll with (dis)advantage | prevent (dis)advantage |
| [shield](./spells/lv1/shield.md)                                       |                                                                  | +5 to ac               |

## ASI/Feat

| lv  | choice          |
| --- | --------------- |
| 4   | Metamagic Adept |
| 8   | ...             |

## item ideas

- +1 bloodwell vial (rare, tce)
- far realm shard (uncommon, tce)
- shadowfell shard (rare, tce)
