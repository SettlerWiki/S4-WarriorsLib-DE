# WarriorsLib.RecruitWarriors

## `WarriorsLib.RecruitWarriors(`buildingid, warriortype, amount, party`)`

Lassen Sie ein Gebäude beginnen oder stoppen Sie die Rekrutierung von Siedlern. ``&#x20;

Die Anzahl der Einheiten, die Sie für die Rekrutierung in die Warteschlange stellen möchten. Dieser Wert ist bis auf einige Ausnahmen additiv. Sie können negative Werte übergeben, um die Anzahl der Einheiten in der Warteschlange zu reduzieren. Das Spiel verwendet nur die folgenden Werte.

| Value | Description                                                                                          |
| ----- | ---------------------------------------------------------------------------------------------------- |
| -5    | Subtrahieren Sie fünf Einheiten von der Warteschlange.                                               |
| -1    | Subtrahieren Sie eine Einheit von der Warteschlange                                                  |
| 0     | Löscht die Warteschlange. Dadurch wird das Gebäude daran gehindert, weitere Einheiten zu produzieren |
| 1     | Fügen Sie der Warteschlange eine Einheit hinzu.                                                      |
| 5     | Fügen Sie der Warteschlange fünf Einheiten hinzu                                                     |
| 100   | Das Spiel wird dies als unendlich interpretieren und die Warteschlange niemals verkleinern.          |

#### Rückgabewert

none

```lua
coming soon
```