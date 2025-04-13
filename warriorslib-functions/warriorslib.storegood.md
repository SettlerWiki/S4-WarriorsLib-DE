# WarriorsLib.StoreGood

## `WarriorsLib.StoreGood(buildingID, goodtype, enable, player)`

Gibt an, welche Waren ein Lager lagern soll.

`enable`

Wenn TRUE, beginnt das Gebäude, Waren des angegebenen Typs zu lagern. Wenn FALSE, wird es aufhören, sie zu speichern.

#### Rückgabewert

* **Ab Version 1.5.0**: success \[0, 1]
* Davor: none

```lua
Buildings.AddBuilding(118, 58, 3, Buildings.STORAGEAREA)
WarriorsLib.StoreGood (Buildings.GetFirstBuilding(3, Buildings.STORAGEAREA), Goods.GOLDBAR, 1, 3)
```
