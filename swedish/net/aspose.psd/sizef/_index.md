---
title: "Struktur SizeF"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.SizeF-struktur. Lagrar ett ordnat par flyttal som vanligtvis är bredden och höjden på en rektangel."
type: docs
weight: 6060
url: /sv/net/aspose.psd/sizef/
---
{{< psd/tize >}}
## SizeF structure

Lagrar ett ordnat par av flyttal, vanligtvis bredden och höjden på en rektangel.

```csharp
public struct SizeF
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SizeF](sizef/#constructor)(PointF) | Initierar en ny instans av `SizeF`-strukturen från den angivna [`PointF`](../pointf/). |
| [SizeF](sizef/#constructor_1)(SizeF) | Initierar en ny instans av `SizeF`-strukturen från den angivna `SizeF`. |
| [SizeF](sizef/#constructor_2)(float, float) | Initierar en ny instans av `SizeF`-strukturen från de angivna dimensionerna. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [Empty](../../aspose.psd/sizef/empty/) { get; } | Hämtar en ny instans av `SizeF`-strukturen som har [`Width`](./width/) och [`Height`](./height/) värden satta till noll. |
| [Height](../../aspose.psd/sizef/height/) { get; set; } | Hämtar eller anger den vertikala komponenten för detta `SizeF`. |
| [IsEmpty](../../aspose.psd/sizef/isempty/) { get; } | Hämtar ett värde som indikerar om detta `SizeF` har noll bredd och höjd. |
| [Width](../../aspose.psd/sizef/width/) { get; set; } | Hämtar eller anger den horisontella komponenten för detta `SizeF`. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Add](../../aspose.psd/sizef/add/)(SizeF, SizeF) | Lägger till bredden och höjden för en `SizeF`-struktur till bredden och höjden för en annan `SizeF`-struktur. |
| static [Subtract](../../aspose.psd/sizef/subtract/)(SizeF, SizeF) | Subtraherar bredden och höjden för en `SizeF`-struktur från bredden och höjden för en annan `SizeF`-struktur. |
| override [Equals](../../aspose.psd/sizef/equals/)(object) | Testar om det angivna objektet är en `SizeF` med samma dimensioner som detta `SizeF`. |
| override [GetHashCode](../../aspose.psd/sizef/gethashcode/)() | Returnerar en hashkod för denna [`Size`](../size/) struktur. |
| [ToPointF](../../aspose.psd/sizef/topointf/)() | Konverterar en `SizeF` till en [`PointF`](../pointf/). |
| [ToSize](../../aspose.psd/sizef/tosize/)() | Konverterar en `SizeF` till en [`Size`](../size/) struktur med trunkerade storleksvärden. |
| override [ToString](../../aspose.psd/sizef/tostring/)() | Skapar en människoläsbar sträng som representerar detta `SizeF`. |
| [operator +](../../aspose.psd/sizef/op_addition/) | Lägger till bredden och höjden för en `SizeF`-struktur till bredden och höjden för en annan `SizeF`-struktur. |
| [operator ==](../../aspose.psd/sizef/op_equality/) | Testar om två `SizeF`-strukturer är lika. |
| [explicit operator](../../aspose.psd/sizef/op_explicit/) | Konverterar den angivna `SizeF` till en [`PointF`](../pointf/). |
| [operator !=](../../aspose.psd/sizef/op_inequality/) | Testar om två `SizeF`-strukturer är olika. |
| [operator -](../../aspose.psd/sizef/op_subtraction/) | Subtraherar bredden och höjden för en `SizeF`-struktur från bredden och höjden för en annan `SizeF`-struktur. |

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


