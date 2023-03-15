---
title: Struct Rectangle
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.Rectangle structuur. Slaat een set van vier gehele getallen op die de locatie en grootte van een rechthoek vertegenwoordigen.
type: docs
weight: 5340
url: /nl/net/aspose.psd/rectangle/
---
## Rectangle structure

Slaat een set van vier gehele getallen op die de locatie en grootte van een rechthoek vertegenwoordigen.

```csharp
public struct Rectangle
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | Initialiseert een nieuw exemplaar van het`Rectangle` structuur met de opgegeven locatie en grootte. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | Initialiseert een nieuw exemplaar van het`Rectangle` structuur met de opgegeven locatie en grootte. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | Krijgt een nieuw exemplaar van de`Rectangle` structuur die heeft[`X`](./x/) ,[`Y`](./y/) ,[`Width`](./width/) En[`Height`](./height/) waarden ingesteld op nul. |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | Haalt of stelt de y-coördinaat in die de som is van de[`Y`](./y/) En[`Height`](./height/) eigendomswaarden hiervan`Rectangle`structuur. |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | Haalt of stelt de hoogte hiervan in`Rectangle`structuur. |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | Krijgt een waarde die aangeeft of alle numerieke eigenschappen hiervan`Rectangle` hebben waarden van nul. |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | Haalt of stelt de x-coördinaat van de linkerrand hiervan in`Rectangle`structuur. |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | Haalt of stelt de coördinaten van de linkerbovenhoek hiervan in`Rectangle`structuur. |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | Haalt of stelt de x-coördinaat in die de som is van[`X`](./x/) En[`Width`](./width/) eigendomswaarden hiervan`Rectangle`structuur. |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | Haalt of stelt de grootte hiervan in`Rectangle` . |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | Haalt of stelt de y-coördinaat van de bovenrand hiervan in`Rectangle`structuur. |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | Haalt of stelt de breedte hiervan in`Rectangle`structuur. |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | Haalt of stelt de x-coördinaat van de linkerbovenhoek hiervan in`Rectangle`structuur. |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | Haalt of stelt de y-coördinaat van de linkerbovenhoek hiervan in`Rectangle`structuur. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | Converteert het gespecificeerde[`RectangleF`](../rectanglef/) structuur aan een`Rectangle` structuur door afronding van de[`RectangleF`](../rectanglef/) waarden naar de volgende hogere gehele waarden. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | Creëert een`Rectangle` structuur met de gespecificeerde randlocaties. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | Maakt een nieuw`Rectangle` vanaf twee gespecificeerde punten. Twee verticale vlakken van het gecreëerde`Rectangle` zal gelijk zijn aan het doorgegeven*point1* En*point2* . Dit zijn meestal de tegenovergestelde hoekpunten. |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | Creëert en retourneert een opgeblazen kopie van het gespecificeerde`Rectangle`structuur. De kopie wordt opgeblazen met de opgegeven hoeveelheid. Het origineel`Rectangle` structuur blijft ongewijzigd. |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | Geeft een derde terug`Rectangle` structuur die de kruising van twee andere vertegenwoordigt`Rectangle` structuren. Als er geen kruising is, een leeg`Rectangle` wordt geretourneerd. |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | Converteert het gespecificeerde[`RectangleF`](../rectanglef/) naar een`Rectangle` door de ronding af te ronden[`RectangleF`](../rectanglef/) waarden naar de dichtstbijzijnde gehele waarden. |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | Converteert het gespecificeerde[`RectangleF`](../rectanglef/) naar een`Rectangle` door het inkorten van de[`RectangleF`](../rectanglef/) waarden. |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | Krijgt een`Rectangle` structuur die de vereniging van twee bevat`Rectangle` structuren. |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | Bepaalt of het gespecificeerde punt hierin is opgenomen`Rectangle`structuur. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | Bepaalt of het rechthoekige gebied vertegenwoordigd door*rect* zit hier helemaal in`Rectangle`structuur. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | Bepaalt of het gespecificeerde punt hierin is opgenomen`Rectangle`structuur. |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | Test of*obj* is een`Rectangle`structuur met dezelfde locatie en grootte hiervan`Rectangle`structuur. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | Retourneert hiervoor de hash-code`Rectangle`structuur. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | Blaast dit op`Rectangle`met het opgegeven bedrag. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | Blaast dit op`Rectangle`met het opgegeven bedrag. |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | Vervangt dit`Rectangle` met het snijpunt van zichzelf en het gespecificeerde`Rectangle` . |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | Bepaalt of deze rechthoek snijdt met*rect* . |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | Normaliseert de rechthoek door de breedte en hoogte positief te maken, links minder dan rechts en boven minder dan onder. |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid. |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid. |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | Converteert de attributen hiervan`Rectangle` naar een door mensen leesbare string. |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | Test of twee`Rectangle` structuren hebben dezelfde locatie en grootte. |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | Test of twee`Rectangle` structuren verschillen in locatie of grootte. |

### Zie ook

* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


