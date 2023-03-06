---
title: Struct Rectangle
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Rectangle struktur. Lagrar en uppsättning av fyra heltal som representerar platsen och storleken på en rektangel.
type: docs
weight: 5340
url: /sv/net/aspose.psd/rectangle/
---
## Rectangle structure

Lagrar en uppsättning av fyra heltal som representerar platsen och storleken på en rektangel.

```csharp
public struct Rectangle
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | Initierar en ny instans av`Rectangle` struktur med angiven plats och storlek. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | Initierar en ny instans av`Rectangle` struktur med angiven plats och storlek. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | Får en ny instans av`Rectangle` struktur som har[`X`](./x/) ,[`Y`](./y/) ,[`Width`](./width/) och[`Height`](./height/) värden satt till noll. |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | Hämtar eller ställer in y-koordinaten som är summan av[`Y`](./y/) och[`Height`](./height/) fastighetsvärden av detta`Rectangle`struktur. |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | Hämtar eller ställer in höjden på detta`Rectangle`struktur. |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | Får ett värde som indikerar om alla numeriska egenskaper för detta`Rectangle` har värden noll. |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | Hämtar eller ställer in x-koordinaten för den vänstra kanten av denna`Rectangle`struktur. |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | Hämtar eller ställer in koordinaterna för det övre vänstra hörnet av denna`Rectangle`struktur. |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | Får eller sätter x-koordinaten som är summan av[`X`](./x/) och[`Width`](./width/) fastighetsvärden av detta`Rectangle`struktur. |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | Hämtar eller ställer in storleken på detta`Rectangle` . |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | Hämtar eller ställer in y-koordinaten för den övre kanten av denna`Rectangle`struktur. |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | Hämtar eller ställer in bredden på detta`Rectangle`struktur. |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | Hämtar eller ställer in x-koordinaten för det övre vänstra hörnet av denna`Rectangle`struktur. |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | Hämtar eller ställer in y-koordinaten för det övre vänstra hörnet av denna`Rectangle`struktur. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | Konverterar den angivna[`RectangleF`](../rectanglef/) struktur till en`Rectangle` struktur genom att runda av[`RectangleF`](../rectanglef/) värden till nästa högre heltalsvärden. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | Skapar en`Rectangle` struktur med de angivna kantplatserna. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | Skapar en ny`Rectangle` från två angivna punkter. Två vertikaler av det skapade`Rectangle` kommer att vara lika med godkänd*point1* och*point2* . Dessa skulle vanligtvis vara motsatta hörn. |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | Skapar och returnerar en uppblåst kopia av den angivna`Rectangle`strukturera. Kopian är uppblåst med angivet belopp. Originalet`Rectangle` strukturen förblir oförändrad. |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | Returnerar en tredjedel`Rectangle` struktur som representerar skärningspunkten mellan två andra`Rectangle` strukturer. Om det inte finns någon korsning, en tom`Rectangle` returneras. |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | Konverterar den angivna[`RectangleF`](../rectanglef/) till a`Rectangle` genom att runda[`RectangleF`](../rectanglef/) värden till närmaste heltalsvärden. |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | Konverterar den angivna[`RectangleF`](../rectanglef/) till a`Rectangle` genom att trunkera[`RectangleF`](../rectanglef/) värden. |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | Får en`Rectangle` struktur som innehåller föreningen av två`Rectangle` strukturer. |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | Bestämmer om den angivna punkten finns inom denna`Rectangle`struktur. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | Bestämmer om det rektangulära området representerat av*rect* är helt innesluten i detta`Rectangle`struktur. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | Bestämmer om den angivna punkten finns inom denna`Rectangle`struktur. |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | Testar om*obj* är en`Rectangle`struktur med samma placering och storlek på denna`Rectangle`struktur. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | Returnerar hash-koden för detta`Rectangle`struktur. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | Blåser upp detta`Rectangle`med det angivna beloppet. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | Blåser upp detta`Rectangle`med det angivna beloppet. |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | Ersätter detta`Rectangle` med skärningspunkten mellan sig själv och det specificerade`Rectangle` . |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | Bestämmer om denna rektangel skär med*rect* . |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | Normaliserar rektangeln genom att göra dens bredd och höjd positiv, vänster mindre än höger och toppen mindre än botten. |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | Justerar platsen för denna rektangel med det angivna beloppet. |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | Justerar platsen för denna rektangel med det angivna beloppet. |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | Konverterar attributen för detta`Rectangle` till en läsbar sträng. |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | Testar om två`Rectangle` strukturer har samma plats och storlek. |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | Testar om två`Rectangle` strukturer skiljer sig åt i plats eller storlek. |

### Se även

* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


