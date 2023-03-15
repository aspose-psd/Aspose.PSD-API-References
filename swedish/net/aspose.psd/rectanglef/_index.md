---
title: Struct RectangleF
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.RectangleF struktur. Lagrar en uppsättning av fyra flyttalstal som representerar platsen och storleken på en rektangel.
type: docs
weight: 5350
url: /sv/net/aspose.psd/rectanglef/
---
## RectangleF structure

Lagrar en uppsättning av fyra flyttalstal som representerar platsen och storleken på en rektangel.

```csharp
public struct RectangleF
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | Initierar en ny instans av`RectangleF` struktur med angiven plats och storlek. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | Initierar en ny instans av`RectangleF` struktur med angiven plats och storlek. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | Får en ny instans av`RectangleF` struktur som har[`X`](./x/) ,[`Y`](./y/) ,[`Width`](./width/) och[`Height`](./height/) värden satt till noll. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | Hämtar eller sätter y-koordinaten som är summan av[`Y`](./y/) och[`Height`](./height/) av detta`RectangleF`struktur. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | Hämtar eller ställer in höjden på detta`RectangleF`struktur. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | Får ett värde som indikerar om[`Width`](./width/) eller[`Height`](./height/) egendom av denna`RectangleF` har värdet noll. |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | Hämtar eller ställer in x-koordinaten för den vänstra kanten av denna`RectangleF`struktur. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | Hämtar eller ställer in koordinaterna för det övre vänstra hörnet av denna`RectangleF`struktur. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | Får eller sätter x-koordinaten som är summan av[`X`](./x/) och[`Width`](./width/) av detta`RectangleF`struktur. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | Hämtar eller ställer in storleken på detta`RectangleF` . |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | Hämtar eller ställer in y-koordinaten för den övre kanten av denna`RectangleF`struktur. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | Hämtar eller ställer in bredden på detta`RectangleF`struktur. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | Hämtar eller ställer in x-koordinaten för det övre vänstra hörnet av denna`RectangleF`struktur. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | Hämtar eller ställer in y-koordinaten för det övre vänstra hörnet av denna`RectangleF`struktur. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | Skapar en`RectangleF` struktur med övre vänstra hörnet och nedre högra hörnet på de angivna platserna. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | Skapar en ny[`Rectangle`](../rectangle/) från två angivna punkter. Två hörn av det skapade[`Rectangle`](../rectangle/) kommer att vara lika med godkänd*point1* och*point2* . Dessa skulle vanligtvis vara motsatta hörn. |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | Skapar och returnerar en uppblåst kopia av den angivna`RectangleF`strukturera. Kopian är uppblåst med angivet belopp. Den ursprungliga rektangeln förblir oförändrad. |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | Returnerar en`RectangleF` struktur som representerar skärningspunkten mellan två rektanglar. Om det inte finns någon korsning, och tom`RectangleF` returneras. |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | Skapar den minsta möjliga tredje rektangeln som kan innehålla båda de två rektanglarna som bildar en union. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | Bestämmer om den angivna punkten finns inom denna`RectangleF`struktur. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | Bestämmer om det rektangulära området representerat av*rect* är helt innesluten i detta`RectangleF`struktur. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | Bestämmer om den angivna punkten finns inom denna`RectangleF`struktur. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | Testar om*obj* är en`RectangleF` med samma placering och storlek på denna`RectangleF` . |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | Hämtar hashkoden för detta`RectangleF`struktur. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | Blåser upp detta`RectangleF`med det angivna beloppet. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | Blåser upp detta`RectangleF` struktur med angivet belopp. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | Ersätter detta`RectangleF`struktur med skärningspunkten mellan sig själv och det specificerade`RectangleF`struktur. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | Bestämmer om denna rektangel skär med*rect* . |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | Normaliserar rektangeln genom att göra dens bredd och höjd positiv, vänster mindre än höger och toppen mindre än botten. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | Justerar platsen för denna rektangel med det angivna beloppet. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | Justerar platsen för denna rektangel med det angivna beloppet. |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | Konverterar attributen för detta`RectangleF` till en läsbar sträng. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | Implementerar operatorn /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | Testar om två`RectangleF` strukturer har samma plats och storlek. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | Konverterar den angivna[`Rectangle`](../rectangle/) struktur till en`RectangleF`struktur. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | Testar om två`RectangleF` strukturer skiljer sig åt i plats eller storlek. |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | Implementerar operatorn *. |

### Se även

* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


