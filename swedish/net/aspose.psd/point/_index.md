---
title: Struct Point
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Point struktur. Representerar ett ordnat par av heltals x och ykoordinater som definierar en punkt i ett tvådimensionellt plan.
type: docs
weight: 5260
url: /sv/net/aspose.psd/point/
---
## Point structure

Representerar ett ordnat par av heltals x- och y-koordinater som definierar en punkt i ett tvådimensionellt plan.

```csharp
public struct Point
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Point](point/#constructor_1)(int) | Initierar en ny instans av`Point` struktur med koordinater som anges av ett heltalsvärde. |
| [Point](point/#constructor)(Size) | Initierar en ny instans av`Point` struktur från[`Size`](../size/)struktur. |
| [Point](point/#constructor_2)(int, int) | Initierar en ny instans av`Point` struktur med de angivna koordinaterna. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | Får en ny instans av`Point` struktur som har[`X`](./x/) och[`Y`](./y/) värden satt till noll. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | Får ett värde som indikerar om detta`Point` är tom. |
| [X](../../aspose.psd/point/x/) { get; set; } | Hämtar eller ställer in x-koordinaten för detta`Point` . |
| [Y](../../aspose.psd/point/y/) { get; set; } | Hämtar eller ställer in y-koordinaten för detta`Point` . |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | Lägger till det angivna[`Size`](../size/) till det angivna`Point` . |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | Konverterar den angivna[`PointF`](../pointf/) till a`Point` genom att avrunda värdena för[`PointF`](../pointf/) till nästa högre heltalsvärden. |
| static [Round](../../aspose.psd/point/round/)(PointF) | Konverterar den angivna[`PointF`](../pointf/) till a`Point` objekt genom att runda av`Point` värden till närmaste heltal. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | Returnerar resultatet av den specificerade subtraheringen[`Size`](../size/) från det angivna`Point` . |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | Konverterar den angivna[`PointF`](../pointf/) till a`Point` genom att trunkera värdena för`Point` . |
| override [Equals](../../aspose.psd/point/equals/)(object) | Anger om detta`Point` innehåller samma koordinater som de angivnaObject . |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | Returnerar en hash-kod för detta`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | Översätter detta`Point` av den angivna`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | Översätter detta`Point`med det angivna beloppet. |
| override [ToString](../../aspose.psd/point/tostring/)() | Konverterar detta`Point` till en läsbar sträng. |
| [operator +](../../aspose.psd/point/op_addition/) | Översätter en`Point` av en given[`Size`](../size/) . |
| [operator ==](../../aspose.psd/point/op_equality/) | Jämför två`Point` föremål. Resultatet anger om värdena för[`X`](./x/) och[`Y`](./y/) egenskaper hos de två`Point` objekt är lika. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | Konverterar den angivna`Point` struktur till en[`Size`](../size/)struktur. |
| [implicit operator](../../aspose.psd/point/op_implicit/) | Konverterar den angivna`Point` struktur till[`PointF`](../pointf/)struktur. |
| [operator !=](../../aspose.psd/point/op_inequality/) | Jämför två`Point` föremål. Resultatet anger om värdena för[`X`](./x/) eller[`Y`](./y/) egenskaper hos de två`Point` objekt är ojämlika. |
| [operator -](../../aspose.psd/point/op_subtraction/) | Översätter en`Point` av det negativa av en given[`Size`](../size/) . |

### Se även

* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


