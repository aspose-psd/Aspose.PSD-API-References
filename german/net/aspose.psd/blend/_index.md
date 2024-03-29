---
title: Class Blend
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.Blend klas. Definiert ein Mischmuster. Diese Klasse kann nicht vererbt werden.
type: docs
weight: 110
url: /de/net/aspose.psd/blend/
---
## Blend class

Definiert ein Mischmuster. Diese Klasse kann nicht vererbt werden.

```csharp
public sealed class Blend
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Blend](blend/#constructor)() | Initialisiert eine neue Instanz von`Blend` Klasse. Die Anzahl der Elemente in den Faktor- und Mischarrays ist gleich 1. |
| [Blend](blend/#constructor_1)(int) | Initialisiert eine neue Instanz von`Blend` Klasse mit der angegebenen Anzahl an Faktoren und Positionen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Factors](../../aspose.psd/blend/factors/) { get; set; } | Ruft das Array der Mischfaktoren für den Farbverlauf ab oder legt es fest. |
| [Positions](../../aspose.psd/blend/positions/) { get; set; } | Ruft das Array von Mischpositionen für den Farbverlauf ab oder legt es fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.psd/blend/equals/)(object) | Testet, ob das angegebene Objekt a ist`Blend` Klasse und entspricht dieser`Blend` Klasse. |
| override [GetHashCode](../../aspose.psd/blend/gethashcode/)() | Gibt einen Hash-Code für diese Instanz zurück. |

### Bemerkungen

Die typische Verwendung der Mischklasse besteht darin, ein Mischmuster für Pinsel zu definieren. Daher sollten die Blend-Eigenschaften sorgfältig initialisiert werden. Null-Arrays sind nicht erlaubt. Der Pinsel löst die entsprechende Ausnahme aus, wenn Blend Factors oder Positions-Array leer sind oder ihre Länge nicht gleich ist. Wenn das Positions-Array zwei oder mehr Elemente enthält, sollte das erste Element 0 und das letzte 1 sein.

### Siehe auch

* namensraum [Aspose.PSD](../../aspose.psd/)
* Montage [Aspose.PSD](../../)


