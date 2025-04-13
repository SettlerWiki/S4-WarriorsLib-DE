# WarriorsLib.UnGarrisonWarriors

## `WarriorsLib.UnGarrisonWarriors(buldingid, column, bowman, player)`

Ein Gebäude unbesetzen. Dies bewirkt, dass ein Militärgebäude Einheiten ausstößt.

`column`

Die Spalte der auszuwerfenden Einheit. Verwenden Sie 0 (Null), um die Einheit ganz links auszuwerfen (in Bezug auf die Seitenwand des ausgewählten Gebäudes) . Verwenden Sie -1, um so viele Einheiten wie möglich auszuwerfen. Dieser Wert liegt normalerweise im Bereich -1...5

`bowman`

Bei TRUE wird ein Bogenschütze ausgeworfen. Andernfalls wird ein Schwertkämpfer ausgeworfen. Dieser Parameter wird ignoriert, wenn die Spalte -1 ist.

#### Rückgabewert

* **Ab Version 1.5.0**: success \[0, 1]
* Davor: none

```lua
WarriorsLib.UnGarrisonWarriors(Buildings.GetFirstBuilding(1, Buildings.GUARDTOWERSMALL),-1,1,1)
```
