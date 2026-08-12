---
title: "Struktur Rectangle"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Rectangle struct. Lagrar en uppsättning av fyra heltal som representerar platsen och storleken på en rektangel."
type: docs
weight: 5840
url: /sv/net/aspose.psd/rectangle/
---
{{< psd/tize >}}
## Rectangle structure

Lagrar en uppsättning av fyra heltal som representerar platsen och storleken på en rektangel.

```csharp
public struct Rectangle
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | Initierar en ny instans av strukturen `Rectangle` med den angivna platsen och storleken. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | Initierar en ny instans av strukturen `Rectangle` med den angivna platsen och storleken. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | Hämtar en ny instans av `Rectangle`-strukturen som har [`X`](./x/), [`Y`](./y/), [`Width`](./width/) och [`Height`](./height/) värden satta till noll. |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | Hämtar eller anger y-koordinaten som är summan av [`Y`](./y/) och [`Height`](./height/) egenskapsvärdena för denna `Rectangle`-struktur. |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | Hämtar eller anger höjden på denna `Rectangle`-struktur. |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | Hämtar ett värde som indikerar om alla numeriska egenskaper i denna `Rectangle` har värden på noll. |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | Hämtar eller anger x-koordinaten för den vänstra kanten av denna `Rectangle`-struktur. |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | Hämtar eller anger koordinaterna för det övre vänstra hörnet av denna `Rectangle`-struktur. |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | Hämtar eller anger x-koordinaten som är summan av [`X`](./x/) och [`Width`](./width/) egenskapsvärdena för denna `Rectangle`-struktur. |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | Hämtar eller anger storleken på denna `Rectangle`. |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | Hämtar eller anger y-koordinaten för den övre kanten av denna `Rectangle`-struktur. |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | Hämtar eller anger bredden på denna `Rectangle`-struktur. |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | Hämtar eller anger x-koordinaten för det övre vänstra hörnet av denna `Rectangle`-struktur. |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | Hämtar eller anger y-koordinaten för det övre vänstra hörnet av denna `Rectangle`-struktur. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | Konverterar den angivna [`RectangleF`](../rectanglef/)-strukturen till en `Rectangle`-struktur genom att avrunda [`RectangleF`](../rectanglef/)‑värdena till nästa högre heltalsvärde. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | Skapar en `Rectangle`-struktur med de angivna kantpositionerna. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | Skapar en ny `Rectangle` från två angivna punkter. De två vertikalerna i den skapade `Rectangle` kommer att vara lika med de angivna *point1* och *point2*. Dessa är vanligtvis de motsatta hörnen. |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | Skapar och returnerar en uppblåst kopia av den angivna `Rectangle`-strukturen. Kopian uppblåses med det angivna beloppet. Den ursprungliga `Rectangle`-strukturen förblir oförändrad. |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | Returnerar en tredje `Rectangle`-struktur som representerar skärningspunkten mellan två andra `Rectangle`-strukturer. Om det inte finns någon skärning returneras en tom `Rectangle`. |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | Konverterar den angivna [`RectangleF`](../rectanglef/) till en `Rectangle` genom att avrunda [`RectangleF`](../rectanglef/) värdena till närmaste heltal. |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | Konverterar den angivna [`RectangleF`](../rectanglef/) till en `Rectangle` genom att trunkera [`RectangleF`](../rectanglef/) värdena. |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | Hämtar en `Rectangle`-struktur som innehåller unionen av två `Rectangle`-strukturer. |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | Bestämmer om den angivna punkten finns inom denna `Rectangle`-struktur. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | Bestämmer om det rektangulära området som representeras av *rect* är helt innehållet inom denna `Rectangle`-struktur. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | Bestämmer om den angivna punkten finns inom denna `Rectangle`-struktur. |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | Testar om *obj* är en `Rectangle`-struktur med samma plats och storlek som denna `Rectangle`-struktur. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | Returnerar hashkoden för denna `Rectangle`-struktur. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | Uppblåser denna `Rectangle` med det angivna beloppet. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | Uppblåser denna `Rectangle` med det angivna beloppet. |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | Ersätter detta `Rectangle` med skärningen av sig själv och den angivna `Rectangle`. |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | Bestämmer om denna rektangel skär med *rect*. |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | Normaliserar rektangeln genom att göra dess bredd och höjd positiva, vänster mindre än höger och topp mindre än botten. |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | Justerar platsen för denna rektangel med det angivna beloppet. |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | Justerar platsen för denna rektangel med det angivna beloppet. |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | Konverterar attributen för detta `Rectangle` till en människoläsbar sträng. |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | Testar om två `Rectangle`-strukturer har samma position och storlek. |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | Testar om två `Rectangle`-strukturer skiljer sig åt i position eller storlek. |

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


