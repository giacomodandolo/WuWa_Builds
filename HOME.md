# CHARACTERS
## Main DPS
```dataview
list
where contains(file.tags, "#character") and contains(file.tags, "#mainDPS")
sort file.name
```
## Sub DPS
```dataview
list
where contains(file.tags, "#character") and contains(file.tags, "#subDPS")
sort file.name
```
## Support
```dataview
list
where contains(file.tags, "#character") and contains(file.tags, "#support")
sort file.name
```
---
# ECHOES
```dataview
list
where contains(file.tags, "echoes")
sort file.name
```
---
# WEAPONS
```dataview
list
where contains(file.tags, "#weapons")
sort file.name
```
