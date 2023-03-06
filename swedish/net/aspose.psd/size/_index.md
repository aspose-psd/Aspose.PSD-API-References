---
title: Struct Size
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Size struktur. Representerar storlek.
type: docs
weight: 5550
url: /sv/net/aspose.psd/size/
---
## Size structure

Representerar storlek.

```csharp
public struct Size
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Size](size/#constructor)(Point) | Initierar en ny instans av`Size` struktur från den angivna[`Point`](../point/) . |
| [Size](size/#constructor_1)(int, int) | Initierar en ny instans av`Size` struktur från de angivna måtten. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [Empty](../../aspose.psd/size/empty/) { get; } | Får en ny instans av`Size` struktur som har[`Width`](./width/) och[`Height`](./height/) värden satt till noll. |
| [Height](../../aspose.psd/size/height/) { get; set; } | Hämtar eller ställer in den vertikala komponenten av detta`Size` . |
| [IsEmpty](../../aspose.psd/size/isempty/) { get; } | Får ett värde som indikerar om detta`Size` har en bredd och höjd på 0. |
| [Width](../../aspose.psd/size/width/) { get; set; } | Hämtar eller ställer in den horisontella komponenten av detta`Size` . |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [Add](../../aspose.psd/size/add/)(Size, Size) | Lägger till bredd och höjd för en`Size` struktur till en annans bredd och höjd`Size`struktur. |
| static [Ceiling](../../aspose.psd/size/ceiling/)(SizeF) | Konverterar den angivna[`SizeF`](../sizef/) struktur till en`Size` strukturera genom att avrunda värdena för`Size` struktur till nästa högre heltalsvärden. |
| static [Round](../../aspose.psd/size/round/)(SizeF) | Konverterar den angivna[`SizeF`](../sizef/) struktur till en`Size` strukturera genom att avrunda värdena för[`SizeF`](../sizef/) struktur till närmaste heltalsvärden. |
| static [Subtract](../../aspose.psd/size/subtract/)(Size, Size) | Subtraherar bredden och höjden på en`Size` struktur från en annans bredd och höjd`Size`struktur. |
| static [Truncate](../../aspose.psd/size/truncate/)(SizeF) | Konverterar den angivna[`SizeF`](../sizef/) struktur till en`Size` struktur genom att trunkera värdena för[`SizeF`](../sizef/) struktur till nästa lägre heltalsvärden. |
| override [Equals](../../aspose.psd/size/equals/)(object) | Testar för att se om det angivna objektet är en`Size` med samma mått som denna`Size` . |
| override [GetHashCode](../../aspose.psd/size/gethashcode/)() | Returnerar en hash-kod för detta`Size`struktur. |
| override [ToString](../../aspose.psd/size/tostring/)() | Skapar en läsbar sträng som representerar detta`Size` . |
| [operator +](../../aspose.psd/size/op_addition/) | Lägger till bredd och höjd för en`Size` struktur till en annans bredd och höjd`Size`struktur. |
| [operator ==](../../aspose.psd/size/op_equality/) | Testar om två`Size` strukturerna är lika. |
| [explicit operator](../../aspose.psd/size/op_explicit/) | Konverterar den angivna`Size` till a[`Point`](../point/) . |
| [implicit operator](../../aspose.psd/size/op_implicit/) | Konverterar den angivna`Size` till a[`SizeF`](../sizef/) . |
| [operator !=](../../aspose.psd/size/op_inequality/) | Testar om två`Size` strukturer är olika. |
| [operator -](../../aspose.psd/size/op_subtraction/) | Subtraherar bredden och höjden på en`Size` struktur från en annans bredd och höjd`Size`struktur. |

### Se även

* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


