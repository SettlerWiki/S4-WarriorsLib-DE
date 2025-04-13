# WarriorsLib.SetBuildingWorkarea

## `WarriorsLib.SetBuildingWorkarea(buildingID, x, y, player)`

Legen Sie den Arbeitsbereich für ein Gebäude fest. Dies ist das gleiche Ereignis, das Spieler auslösen können, indem sie auf das Zielsymbol in der Seitenleiste eines ausgewählten Gebäudes klicken.

#### Rückgabewert

* **Ab Version 1.5.0**: success \[0, 1]
* Davor: none

```lua
WarriorsLib.SetBuildingWorkarea(Buildings.GetFirstBuilding(3, Buildings.BARRACKS),70, 33, 3)
```
