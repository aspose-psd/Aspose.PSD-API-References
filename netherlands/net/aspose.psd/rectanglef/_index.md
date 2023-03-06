---
title: Struct RectangleF
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.RectangleF structuur. Slaat een set van vier getallen met drijvende komma op die de locatie en grootte van een rechthoek vertegenwoordigen.
type: docs
weight: 5350
url: /nl/net/aspose.psd/rectanglef/
---
## RectangleF structure

Slaat een set van vier getallen met drijvende komma op die de locatie en grootte van een rechthoek vertegenwoordigen.

```csharp
public struct RectangleF
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | Initialiseert een nieuw exemplaar van het`RectangleF` structuur met de opgegeven locatie en grootte. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | Initialiseert een nieuw exemplaar van het`RectangleF` structuur met de opgegeven locatie en grootte. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | Krijgt een nieuw exemplaar van de`RectangleF` structuur die heeft[`X`](./x/) ,[`Y`](./y/) ,[`Width`](./width/) En[`Height`](./height/) waarden ingesteld op nul. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | Haalt of stelt de y-coördinaat in die de som is van[`Y`](./y/) En[`Height`](./height/) van dit`RectangleF`structuur. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | Haalt of stelt de hoogte hiervan in`RectangleF`structuur. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | Krijgt een waarde die aangeeft of de[`Width`](./width/) of[`Height`](./height/) eigendom hiervan`RectangleF` heeft een waarde van nul. |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | Haalt of stelt de x-coördinaat van de linkerrand hiervan in`RectangleF`structuur. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | Haalt of stelt de coördinaten van de linkerbovenhoek hiervan in`RectangleF`structuur. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | Haalt of stelt de x-coördinaat in die de som is van[`X`](./x/) En[`Width`](./width/) van dit`RectangleF`structuur. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | Haalt of stelt de grootte hiervan in`RectangleF` . |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | Haalt of stelt de y-coördinaat van de bovenrand hiervan in`RectangleF`structuur. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | Haalt of stelt de breedte hiervan in`RectangleF`structuur. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | Haalt of stelt de x-coördinaat van de linkerbovenhoek hiervan in`RectangleF`structuur. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | Haalt of stelt de y-coördinaat van de linkerbovenhoek hiervan in`RectangleF`structuur. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | Creëert een`RectangleF` structuur met linkerbovenhoek en rechteronderhoek op de opgegeven locaties. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | Maakt een nieuw[`Rectangle`](../rectangle/) vanaf twee gespecificeerde punten. Twee hoekpunten van het gecreëerde[`Rectangle`](../rectangle/) zal gelijk zijn aan het doorgegeven*point1* En*point2* . Dit zijn meestal de tegenovergestelde hoekpunten. |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | Creëert en retourneert een opgeblazen kopie van het gespecificeerde`RectangleF`structuur. De kopie wordt opgeblazen met de opgegeven hoeveelheid. De oorspronkelijke rechthoek blijft ongewijzigd. |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | Geeft als resultaat een`RectangleF` structuur die het snijpunt van twee rechthoeken voorstelt. Als er geen kruising is, en leeg`RectangleF` wordt geretourneerd. |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | Maakt de kleinst mogelijke derde rechthoek die beide rechthoeken kan bevatten die een unie vormen. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | Bepaalt of het gespecificeerde punt hierin is opgenomen`RectangleF`structuur. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | Bepaalt of het rechthoekige gebied vertegenwoordigd door*rect* zit hier helemaal in`RectangleF`structuur. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | Bepaalt of het gespecificeerde punt hierin is opgenomen`RectangleF`structuur. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | Test of*obj* is een`RectangleF` met dezelfde locatie en grootte hiervan`RectangleF` . |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | Krijgt de hash-code hiervoor`RectangleF`structuur. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | Blaast dit op`RectangleF`met het opgegeven bedrag. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | Blaast dit op`RectangleF` structuur met het opgegeven bedrag. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | Vervangt dit`RectangleF`structuur met de kruising van zichzelf en het gespecificeerde`RectangleF`structuur. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | Bepaalt of deze rechthoek snijdt met*rect* . |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | Normaliseert de rechthoek door de breedte en hoogte positief te maken, links minder dan rechts en boven minder dan onder. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid. |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | Converteert de attributen hiervan`RectangleF` naar een door mensen leesbare string. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | Implementeert de operator /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | Test of twee`RectangleF` structuren hebben dezelfde locatie en grootte. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | Converteert het gespecificeerde[`Rectangle`](../rectangle/) structuur aan een`RectangleF`structuur. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | Test of twee`RectangleF` structuren verschillen in locatie of grootte. |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | Implementeert de operator *. |

### Zie ook

* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


