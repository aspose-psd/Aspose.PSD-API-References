---
title: "Struktur Point"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Point-struct. Representerar ett ordnat par av heltals‑x‑ och y‑koordinater som definierar en punkt i ett tvådimensionellt plan."
type: docs
weight: 5760
url: /sv/net/aspose.psd/point/
---
{{< psd/tize >}}
## Point structure

Representerar ett ordnat par av heltals‑x‑ och y‑koordinater som definierar en punkt i ett tvådimensionellt plan.

```csharp
public struct Point
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Point](point/#constructor_1)(int) | Initierar en ny instans av `Point`‑strukturen med koordinater som specificeras av ett heltal. |
| [Point](point/#constructor)(Size) | Initierar en ny instans av `Point`‑strukturen från [`Size`](../size/)-strukturen. |
| [Point](point/#constructor_2)(int, int) | Initierar en ny instans av `Point`‑strukturen med de angivna koordinaterna. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | Hämtar en ny instans av `Point`-strukturen som har värdena [`X`](./x/) och [`Y`](./y/) satta till noll. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | Hämtar ett värde som indikerar om detta `Point` är tomt. |
| [X](../../aspose.psd/point/x/) { get; set; } | Hämtar eller anger x-koordinaten för detta `Point`. |
| [Y](../../aspose.psd/point/y/) { get; set; } | Hämtar eller anger y-koordinaten för detta `Point`. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | Lägger till den angivna [`Size`](../size/) till det angivna `Point`. |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | Konverterar den angivna [`PointF`](../pointf/) till ett `Point` genom att avrunda värdena i [`PointF`](../pointf/) till nästa högre heltalsvärde. |
| static [Round](../../aspose.psd/point/round/)(PointF) | Konverterar den angivna [`PointF`](../pointf/) till ett `Point`-objekt genom att avrunda `Point`-värdena till närmaste heltal. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | Returnerar resultatet av att subtrahera den angivna [`Size`](../size/) från det angivna `Point`. |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | Konverterar den angivna [`PointF`](../pointf/) till ett `Point` genom att trunkera värdena i `Point`. |
| override [Equals](../../aspose.psd/point/equals/)(object) | Anger om detta `Point` innehåller samma koordinater som det angivna Object. |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | Returnerar en hashkod för detta `Point`. |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | Flyttar detta `Point` med det angivna `Point`. |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | Flyttar detta `Point` med den angivna mängden. |
| override [ToString](../../aspose.psd/point/tostring/)() | Konverterar detta `Point` till en människoläsbar sträng. |
| [operator +](../../aspose.psd/point/op_addition/) | Flyttar ett `Point` med en given [`Size`](../size/). |
| [operator ==](../../aspose.psd/point/op_equality/) | Jämför två `Point`-objekt. Resultatet anger om värdena för egenskaperna [`X`](./x/) och [`Y`](./y/) i de två `Point`-objekten är lika. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | Konverterar den angivna `Point`-strukturen till en [`Size`](../size/)-struktur. |
| [implicit operator](../../aspose.psd/point/op_implicit/) | Konverterar den angivna `Point`-strukturen till [`PointF`](../pointf/)-strukturen. |
| [operator !=](../../aspose.psd/point/op_inequality/) | Jämför två `Point`-objekt. Resultatet anger om värdena för egenskaperna [`X`](./x/) eller [`Y`](./y/) i de två `Point`-objekten är olika. |
| [operator -](../../aspose.psd/point/op_subtraction/) | Flyttar ett `Point` med den negativa av en given [`Size`](../size/). |

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


