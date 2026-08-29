---
title: "Struktur Size"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Size-struktur. Representerar storlek"
type: docs
weight: 6050
url: /sv/net/aspose.psd/size/
---
{{< psd/tize >}}
## Size structure

Representerar storlek.

```csharp
public struct Size
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Size](size/#constructor)(Point) | Initierar en ny instans av `Size`-strukturen från den angivna [`Point`](../point/). |
| [Size](size/#constructor_1)(int, int) | Initierar en ny instans av `Size`-strukturen från de angivna dimensionerna. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [Empty](../../aspose.psd/size/empty/) { get; } | Hämtar en ny instans av `Size`-strukturen som har [`Width`](./width/) och [`Height`](./height/) värden satta till noll. |
| [Height](../../aspose.psd/size/height/) { get; set; } | Hämtar eller anger den vertikala komponenten i detta `Size`. |
| [IsEmpty](../../aspose.psd/size/isempty/) { get; } | Hämtar ett värde som indikerar om detta `Size` har bredd och höjd på 0. |
| [Width](../../aspose.psd/size/width/) { get; set; } | Hämtar eller anger den horisontella komponenten i detta `Size`. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Add](../../aspose.psd/size/add/)(Size, Size) | Lägger till bredden och höjden av en `Size`-struktur till bredden och höjden av en annan `Size`-struktur. |
| static [Ceiling](../../aspose.psd/size/ceiling/)(SizeF) | Konverterar den angivna [`SizeF`](../sizef/) strukturen till en `Size`-struktur genom att avrunda värdena i `Size`-strukturen till nästa högre heltalsvärde. |
| static [Round](../../aspose.psd/size/round/)(SizeF) | Konverterar den angivna [`SizeF`](../sizef/) strukturen till en `Size`-struktur genom att avrunda värdena i [`SizeF`](../sizef/) strukturen till närmaste heltal. |
| static [Subtract](../../aspose.psd/size/subtract/)(Size, Size) | Subtraherar bredden och höjden av en `Size`-struktur från bredden och höjden av en annan `Size`-struktur. |
| static [Truncate](../../aspose.psd/size/truncate/)(SizeF) | Konverterar den angivna [`SizeF`](../sizef/) strukturen till en `Size`-struktur genom att trunkera värdena i [`SizeF`](../sizef/) strukturen till nästa lägre heltalsvärde. |
| override [Equals](../../aspose.psd/size/equals/)(object) | Testar för att se om det angivna objektet är en `Size` med samma dimensioner som denna `Size`. |
| override [GetHashCode](../../aspose.psd/size/gethashcode/)() | Returnerar en hashkod för denna `Size`-struktur. |
| override [ToString](../../aspose.psd/size/tostring/)() | Skapar en läsbar sträng som representerar denna `Size`. |
| [operator +](../../aspose.psd/size/op_addition/) | Lägger till bredden och höjden av en `Size`-struktur till bredden och höjden av en annan `Size`-struktur. |
| [operator ==](../../aspose.psd/size/op_equality/) | Testar om två `Size`-strukturer är lika. |
| [explicit operator](../../aspose.psd/size/op_explicit/) | Konverterar den angivna `Size` till en [`Point`](../point/). |
| [implicit operator](../../aspose.psd/size/op_implicit/) | Konverterar den angivna `Size` till en [`SizeF`](../sizef/). |
| [operator !=](../../aspose.psd/size/op_inequality/) | Testar om två `Size`-strukturer är olika. |
| [operator -](../../aspose.psd/size/op_subtraction/) | Subtraherar bredden och höjden av en `Size`-struktur från bredden och höjden av en annan `Size`-struktur. |

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


