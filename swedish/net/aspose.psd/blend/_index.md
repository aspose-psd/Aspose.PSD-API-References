---
title: "Klassen Blend"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Blend-klass. Definierar ett blandningsmönster. Denna klass kan inte ärvas"
type: docs
weight: 110
url: /sv/net/aspose.psd/blend/
---
{{< psd/tize >}}
## Blend class

Definierar ett blandningsmönster. Denna klass kan inte ärvas.

```csharp
public sealed class Blend
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Blend](blend/#constructor)() | Initierar en ny instans av `Blend`-klassen. Antalet element i faktor- och blandningsarrayerna kommer att vara lika med 1. |
| [Blend](blend/#constructor_1)(int) | Initierar en ny instans av `Blend`-klassen med det angivna antalet faktorer och positioner. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Factors](../../aspose.psd/blend/factors/) { get; set; } | Hämtar eller anger arrayen med blandningsfaktorer för gradienten. |
| [Positions](../../aspose.psd/blend/positions/) { get; set; } | Hämtar eller anger arrayen med blandningspositioner för gradienten. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.psd/blend/equals/)(object) | Testar om det angivna objektet är en `Blend`-klass och är ekvivalent med denna `Blend`-klass. |
| override [GetHashCode](../../aspose.psd/blend/gethashcode/)() | Returnerar en hashkod för denna instans. |

## Anmärkningar

Den typiska användningen av blend-klassen är att definiera ett blend-mönster för penseln. Därför bör blend-egenskaperna initieras noggrant. Null-arrayer är inte tillåtna. Penseln kommer att kasta ett lämpligt undantag om blend-faktorer eller positionsarray är tomma eller deras längd inte är densamma. Om det finns två eller fler element i positionsarrayen ska det första elementet vara 0 och det sista vara 1.

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


