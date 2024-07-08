#weapons
```dataview
TABLE weapon_rarity as "Weapon Rarity", second_stat as "Second Stat"
WHERE contains(file.tags, "broadblade")
SORT weapon_rarity ASC
```