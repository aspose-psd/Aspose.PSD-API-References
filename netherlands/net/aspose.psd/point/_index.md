---
title: Struct Point
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.Point structuur. Vertegenwoordigt een geordend paar integer x en ycoördinaten dat een punt in een tweedimensionaal vlak definieert.
type: docs
weight: 5260
url: /nl/net/aspose.psd/point/
---
## Point structure

Vertegenwoordigt een geordend paar integer x- en y-coördinaten dat een punt in een tweedimensionaal vlak definieert.

```csharp
public struct Point
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Point](point/#constructor_1)(int) | Initialiseert een nieuw exemplaar van het`Point` structuur met behulp van coördinaten gespecificeerd door een geheel getal. |
| [Point](point/#constructor)(Size) | Initialiseert een nieuw exemplaar van het`Point` structuur uit de[`Size`](../size/)structuur. |
| [Point](point/#constructor_2)(int, int) | Initialiseert een nieuw exemplaar van het`Point` structuur met de opgegeven coördinaten. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | Krijgt een nieuw exemplaar van de`Point` structuur die heeft[`X`](./x/) En[`Y`](./y/) waarden ingesteld op nul. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | Krijgt een waarde die aangeeft of dit`Point` is leeg. |
| [X](../../aspose.psd/point/x/) { get; set; } | Haalt of stelt de x-coördinaat hiervan in`Point` . |
| [Y](../../aspose.psd/point/y/) { get; set; } | Haalt of stelt de y-coördinaat hiervan in`Point` . |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | Voegt het gespecificeerde toe[`Size`](../size/) naar het gespecificeerde`Point` . |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | Converteert het gespecificeerde[`PointF`](../pointf/) naar een`Point` door de waarden van de af te ronden[`PointF`](../pointf/) naar de volgende hogere gehele waarden. |
| static [Round](../../aspose.psd/point/round/)(PointF) | Converteert het gespecificeerde[`PointF`](../pointf/) naar een`Point` object door het afronden van de`Point` waarden tot op het dichtstbijzijnde gehele getal. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | Retourneert het opgegeven resultaat van aftrekken[`Size`](../size/) van het gespecificeerde`Point` . |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | Converteert het gespecificeerde[`PointF`](../pointf/) naar een`Point` door de waarden van de af te kappen`Point` . |
| override [Equals](../../aspose.psd/point/equals/)(object) | Specificeert of dit`Point` bevat dezelfde coördinaten als de opgegevenObject . |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | Retourneert hiervoor een hash-code`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | Vertaalt dit`Point` door de opgegeven`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | Vertaalt dit`Point`met het opgegeven bedrag. |
| override [ToString](../../aspose.psd/point/tostring/)() | Converteert dit`Point` naar een door mensen leesbare string. |
| [operator +](../../aspose.psd/point/op_addition/) | Vertaalt een`Point` door een gegeven[`Size`](../size/) . |
| [operator ==](../../aspose.psd/point/op_equality/) | Vergelijkt er twee`Point` voorwerpen. Het resultaat geeft aan of de waarden van de[`X`](./x/) En[`Y`](./y/) eigenschappen van de twee`Point` objecten zijn gelijk. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | Converteert het gespecificeerde`Point` structuur aan een[`Size`](../size/)structuur. |
| [implicit operator](../../aspose.psd/point/op_implicit/) | Converteert het gespecificeerde`Point` structuur aan de[`PointF`](../pointf/)structuur. |
| [operator !=](../../aspose.psd/point/op_inequality/) | Vergelijkt er twee`Point` voorwerpen. Het resultaat geeft aan of de waarden van de[`X`](./x/) of[`Y`](./y/) eigenschappen van de twee`Point` objecten zijn ongelijk. |
| [operator -](../../aspose.psd/point/op_subtraction/) | Vertaalt een`Point` door de ontkenning van een gegeven[`Size`](../size/) . |

### Zie ook

* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


