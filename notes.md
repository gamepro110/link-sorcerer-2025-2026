# notes

| stat  |  mod  | score | calc                                         |
| :---: | :---: | :---: | -------------------------------------------- |
|  str  |  -1   |   8   | 8                                            |
|  dex  |  +1   |  13   | 13                                           |
|  con  |  +3   |  16   | 15+race(1)                                   |
|  int  |  +0   |  10   | 10                                           |
|  wis  |  +1   |  12   | 12                                           |
|  cha  |  +3   |  16   | 14+race(2)                                   |
|  hp   |   -   |  37   | 6 + con(3) + (avg(4) + con(3) * (lv(5) - 1)) |

---

| ability        | score | calc                      |
| -------------- | :---: | ------------------------- |
| AC             |  11   | 10+dex(+1)                |
| spell attack   |  +7   | mod(+3)+prof(3)+item(1)   |
| spell save     |  15   | 8+mod(+3)+prof(3)+item(1) |
| sorcery points |   7   | lv(5)+feat(2)             |

---

| saves | score | calc            | advantage + reason         |
| ----- | :---: | --------------- | -------------------------- |
| STR   |  -1   | mod(-1)         |                            |
| DEX   |  +1   | mod(+1)         |                            |
| CON   |  +6   | mod(+3)+prof(3) |                            |
| INT   |  +0   | mod(+0)         |                            |
| WIS   |  +1   | mod(+1)         | always, telepathic insight |
| CHA   |  +6   | mod(+3)+prof(3) | always, telepathic insight |

---

> [!Note]
> known cantrips: 5  
> known spells: 12 = 6 (class lv) + (2 * (subclass lv 1, 3, 5))

| spell/skill slot | available | used  |
| :--------------: | :-------: | :---: |
| restore balance  |  prof(2)  |   0   |
|  sorcery points  |     7     |   0   |
|      1st lv      |     4     |   0   |
|      2nd lv      |     3     |   0   |
|      3rd lv      |     2     |   0   |
|      4th lv      |     0     |   0   |
|      5th lv      |     0     |   0   |

---

|                |       |
| -------------- | :---: |
| current hp     |  37   |
| max hp         |  37   |
| initiative     |  +1   |
| gold           |  93   |
| known cantrips |   5   |

---

| meta magic       | cost     | effect                                                    |
| ---------------- | -------- | --------------------------------------------------------- |
| distant spell    | 1        | range 5ft+ -> doubles, range touch -> 30ft                |
| subtle spell     | 1        | cast spell without verbal or somatic components           |
| twinned spell    | spell lv | single target spell to double target                      |
| empowered spell  | 1        | reroll (cha mod) dmg dice, must use new roll (combinable) |
| ---              | ---      | ---                                                       |
| magical guidance | 1        | reroll d20 on failed ability check, must use new roll     |

---

| sorcerer lv | learned clockwork spell                 |
| ----------- | --------------------------------------- |
| 1st         | alarm, protection from evil and good    |
| 2nd         | protection from evil and good -> shield |
| 3rd         | aid, lesser restoration                 |
| 4th         | ---                                     |
| 5th         | dispel magic, protection from energy    |
| 6th         |                                         |
| 7th         |                                         |
| 8th         |                                         |
| 9th         |                                         |
| 10th        |                                         |

## action economy

### action

| name                                                     | requirement        | note                                                                                       |
| -------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------ |
| [shoot light crossbow](./inventory/light-crossbow.md)    | bolts + two‑handed | 80/320ft 1d8+1 piercing, bonus-action reload                                               |
| [acid splash](./spells/cantrip/acid-splash.md)           |                    | 60ft, target 1 or 2 within 5ft of each other, dex save **1d6** acid on failed save         |
| [chill touch](./spells/cantrip/chill-touch.md)           |                    | spell attack, 120ft, **1d8** necrotic on hit                                               |
| [dancing lights](./spells/cantrip/dancing-lights.md)     |                    | 120ft, concentration up to 1 min                                                           |
| [fire bolt](./spells/cantrip/fire-bolt.md)               |                    | spell attack, 120ft, **1d10**                                                              |
| [mind sliver](./spells/cantrip/mind-sliver.md)           |                    | 60ft, int save, 1d6 psychic, subtract 1d4 from next save                                   |
| [magic missile](./spells/lv1/magic-missile.md)           |                    | auto hit, 3 X **1d4+1** force dmg                                                          |
| [ice knife](./spells/lv1/ice-knife.md)                   |                    | 60ft, 1d10 piercing + 5ft dex-save 2d6 cold dmg                                            |
| [silent image](./spells/lv1/silent-image.md)             |                    | concentration, visual only, 60ft range, 15ft cube                                          |
| [thunderwave](./spells/lv1/thunderwave.md)               |                    | 15ft cone, con save, **2d8** thunder dmg + pushed 10ft on success, fail half dmg + no push |
| [aid](./spells/lv2/aid.md)                               |                    | concentration 8h, 30ft range, choose 3, each get +5 max and current hp                     |
| [enlarge/reduce](./spells/lv2/enlarge-reduce.md)         |                    | concentration 1min, 30ft range                                                             |
| [lesser restoration](./spells/lv2/lesser-restoration.md) |                    | touch, cure 1 condition or disease, see chart in spell                                     |

### bonus actions

| name                     | requirement      | note                                                             |
| ------------------------ | ---------------- | ---------------------------------------------------------------- |
| convert sp to spell slot | spend sp         | [see table](./class_features.md#level-2-font-of-magic-phb14-p99) |
| convert spell slot to sp | spend spell slot | [see table](./class_features.md#level-2-font-of-magic-phb14-p99) |

### on metamagic use

| name            | effect                                | duration                 |
| --------------- | ------------------------------------- | ------------------------ |
| momentary curse | grant disadvantage on 1 ability score | until the end of my turn |

### reaction

| name                                                                   | requirement                                                      | note                   |
| ---------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------------------- |
| [restore balance](./class_features.md#level-1-restore-balance-tce-p68) | creature i see within 60 ft is about to roll with (dis)advantage | prevent (dis)advantage |
| [shield](./spells/lv1/shield.md)                                       |                                                                  | +5 to ac               |

## attune-able items

| attuned | item                                                      |
| ------- | --------------------------------------------------------- |
| [x]     | [Bubble of Privacy](./magic-items/1-bubble-of-privacy.md) |
| [x]     | [amulet of hecate](./magic-items/2-amulet-of-hecate.md)   |

## ASI/Feat

| lv  | choice          |
| --- | --------------- |
| 4   | Metamagic Adept |
| 8   | ...             |
