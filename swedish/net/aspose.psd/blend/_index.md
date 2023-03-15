---
title: Class Blend
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Blend klass. Definierar ett blandningsmönster. Denna klass kan inte ärvas.
type: docs
weight: 110
url: /sv/net/aspose.psd/blend/
---
## Blend class

Definierar ett blandningsmönster. Denna klass kan inte ärvas.

```csharp
public sealed class Blend
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Blend](blend/#constructor)() | Initierar en ny instans av`Blend` klass. Antalet element i faktor- och blandningsmatriserna kommer att vara lika med 1. |
| [Blend](blend/#constructor_1)(int) | Initierar en ny instans av`Blend` klass med det angivna antalet faktorer och positioner. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Factors](../../aspose.psd/blend/factors/) { get; set; } | Hämtar eller ställer in arrayen av blandningsfaktorer för gradienten. |
| [Positions](../../aspose.psd/blend/positions/) { get; set; } | Hämtar eller ställer in arrayen av blandningspositioner för gradienten. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.psd/blend/equals/)(object) | Testar om det angivna objektet är en`Blend` klass och motsvarar detta`Blend` class. |
| override [GetHashCode](../../aspose.psd/blend/gethashcode/)() | Returnerar en hash-kod för denna instans. |

### Anmärkningar

Den typiska blandningsklassanvändningen definierar ett blandningsmönster för pensel. Och därför bör blandningsegenskaperna initieras noggrant. Nullmatriser är inte tillåtna. Borsten kommer att göra det lämpliga undantaget om blandningsfaktorer eller positionsmatrisen är tomma eller deras längd inte är densamma. Om det finns två eller flera element i positionsmatrisen ska det första elementet vara 0 och det sista ska vara 1.

### Se även

* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


