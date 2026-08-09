---
title: "Klasse Blend"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Blend-Klasse. Definiert ein Mischmuster. Diese Klasse kann nicht abgeleitet werden"
type: docs
weight: 110
url: /de/net/aspose.psd/blend/
---
{{< psd/tize >}}
## Blend class

Definiert ein Mischmuster. Diese Klasse kann nicht abgeleitet werden.

```csharp
public sealed class Blend
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Blend](blend/#constructor)() | Initialisiert eine neue Instanz der `Blend`-Klasse. Die Anzahl der Elemente in den Faktor- und Blend-Arrays wird 1 sein. |
| [Blend](blend/#constructor_1)(int) | Initialisiert eine neue Instanz der `Blend`-Klasse mit der angegebenen Anzahl von Faktoren und Positionen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Factors](../../aspose.psd/blend/factors/) { get; set; } | Liest oder setzt das Array der Blend-Faktoren für den Farbverlauf. |
| [Positions](../../aspose.psd/blend/positions/) { get; set; } | Liest oder setzt das Array der Blend-Positionen für den Farbverlauf. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.psd/blend/equals/)(object) | Testet, ob das angegebene Objekt eine `Blend`-Klasse ist und dieser `Blend`-Klasse entspricht. |
| override [GetHashCode](../../aspose.psd/blend/gethashcode/)() | Gibt einen Hashcode für diese Instanz zurück. |

## Hinweise

Die typische Verwendung der Blend-Klasse besteht darin, ein Blend-Muster für den Pinsel zu definieren. Daher sollten die Blend-Eigenschaften sorgfältig initialisiert werden. Null‑Arrays sind nicht zulässig. Der Pinsel wirft die entsprechende Ausnahme, wenn Blend‑Faktoren‑ oder Positions‑Array leer sind oder deren Länge nicht gleich ist. Wenn das Positions‑Array zwei oder mehr Elemente enthält, muss das erste Element 0 und das letzte 1 sein.

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


