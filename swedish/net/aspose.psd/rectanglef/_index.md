---
title: "Struktur RectangleF"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.RectangleF-struktur. Lagrar en uppsättning av fyra flyttal som representerar platsen och storleken på en rektangel."
type: docs
weight: 5850
url: /sv/net/aspose.psd/rectanglef/
---
{{< psd/tize >}}
## RectangleF structure

Lagrar en uppsättning av fyra flyttal som representerar platsen och storleken på en rektangel.

```csharp
public struct RectangleF
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | Initierar en ny instans av `RectangleF`-strukturen med den angivna platsen och storleken. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | Initierar en ny instans av `RectangleF`-strukturen med den angivna platsen och storleken. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | Hämtar en ny instans av `RectangleF`-strukturen som har värdena [`X`](./x/), [`Y`](./y/), [`Width`](./width/) och [`Height`](./height/) satta till noll. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | Hämtar eller anger y-koordinaten som är summan av [`Y`](./y/) och [`Height`](./height/) för denna `RectangleF`-struktur. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | Hämtar eller anger höjden på denna `RectangleF`-struktur. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | Hämtar ett värde som indikerar om egenskapen [`Width`](./width/) eller [`Height`](./height/) för denna `RectangleF` har värdet noll. |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | Hämtar eller anger x-koordinaten för den vänstra kanten av denna `RectangleF`-struktur. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | Hämtar eller anger koordinaterna för det övre vänstra hörnet av denna `RectangleF`-struktur. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | Hämtar eller anger x-koordinaten som är summan av [`X`](./x/) och [`Width`](./width/) för denna `RectangleF`-struktur. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | Hämtar eller anger storleken på denna `RectangleF`. |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | Hämtar eller anger y-koordinaten för den övre kanten av denna `RectangleF`-struktur. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | Hämtar eller anger bredden på denna `RectangleF`-struktur. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | Hämtar eller anger x-koordinaten för det övre vänstra hörnet av denna `RectangleF`-struktur. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | Hämtar eller anger y-koordinaten för det övre vänstra hörnet av denna `RectangleF`-struktur. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | Skapar en `RectangleF`-struktur med det övre vänstra hörnet och det nedre högra hörnet på de angivna positionerna. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | Skapar en ny [`Rectangle`](../rectangle/) från två angivna punkter. De två hörnen i den skapade [`Rectangle`](../rectangle/) kommer att motsvara de överförda *point1* och *point2*. Dessa är vanligtvis de motsatta hörnen. |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | Skapar och returnerar en uppblåst kopia av den angivna `RectangleF`-strukturen. Kopian uppblåses med den angivna mängden. Den ursprungliga rektangeln förblir oförändrad. |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | Returnerar en `RectangleF`-struktur som representerar skärningspunkten mellan två rektanglar. Om det inte finns någon skärning returneras en tom `RectangleF`. |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | Skapar den minsta möjliga tredje rektangeln som kan innehålla båda två rektanglarna som bildar en union. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | Bestämmer om den angivna punkten finns inom denna `RectangleF`-struktur. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | Bestämmer om det rektangulära området som representeras av *rect* är helt innehållet inom denna `RectangleF`-struktur. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | Bestämmer om den angivna punkten finns inom denna `RectangleF`-struktur. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | Testar om *obj* är en `RectangleF` med samma position och storlek som denna `RectangleF`. |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | Hämtar hash‑koden för denna `RectangleF`-struktur. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | Utvidgar denna `RectangleF` med det angivna värdet. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | Utvidgar denna `RectangleF`-struktur med det angivna värdet. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | Ersätter denna `RectangleF`-struktur med skärningsområdet mellan den själv och den angivna `RectangleF`-strukturen. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | Bestämmer om denna rektangel skär med *rect*. |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | Normaliserar rektangeln genom att göra dess bredd och höjd positiva, vänster mindre än höger och topp mindre än botten. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | Justerar platsen för denna rektangel med det angivna beloppet. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | Justerar platsen för denna rektangel med det angivna beloppet. |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | Konverterar attributen för denna `RectangleF` till en människoläsbar sträng. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | Implementerar operatorn /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | Testar om två `RectangleF`-strukturer har samma position och storlek. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | Konverterar den angivna [`Rectangle`](../rectangle/)-strukturen till en `RectangleF`-struktur. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | Testar om två `RectangleF`-strukturer skiljer sig i position eller storlek. |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | Implementerar operatorn *. |

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


