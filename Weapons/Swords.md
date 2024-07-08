#weapons
```dataview
table weapon_rarity as "Weapon Rarity", second_stat as "Second Stat"
WHERE contains(file.tags, "sword")
SORT weapon_rarity ASC
```