# WarriorsLib.GarrisonWarriors

## `WarriorsLib.GarrisonWarriors(buldingid, player)`

Besetzen eines Gebäudes. Dadurch kann ein Militärgebäude in der Nähe befindliche Einheiten durchsuchen und ihnen, wenn sie gefunden werden, befehlen, das angegebene Gebäude zu betreten, um alle Plätze im Gebäude vollständig zu besetzen

#### Rückgabewert

* **Ab Version 1.5.0**: success \[0, 1]
* Davor: none

```lua
WarriorsLib.GarrisonWarriors(Buildings.GetFirstBuilding(1, Buildings.GUARDTOWERSMALL),1)
```
