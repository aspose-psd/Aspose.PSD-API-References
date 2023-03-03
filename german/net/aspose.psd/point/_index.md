---
title: Struct Point
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.Point structuur. Stellt ein geordnetes Paar ganzzahliger x und yKoordinaten dar das einen Punkt in einer zweidimensionalen Ebene definiert.
type: docs
weight: 5260
url: /de/net/aspose.psd/point/
---
## Point structure

Stellt ein geordnetes Paar ganzzahliger x- und y-Koordinaten dar, das einen Punkt in einer zweidimensionalen Ebene definiert.

```csharp
public struct Point
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Point](point/#constructor_1)(int) | Initialisiert eine neue Instanz von`Point` Struktur mit Koordinaten, die durch einen ganzzahligen Wert angegeben werden. |
| [Point](point/#constructor)(Size) | Initialisiert eine neue Instanz von`Point` Struktur aus der[`Size`](../size/)Struktur. |
| [Point](point/#constructor_2)(int, int) | Initialisiert eine neue Instanz von`Point` Struktur mit den angegebenen Koordinaten. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | Ruft eine neue Instanz von ab`Point` Struktur, die hat[`X`](./x/) Und[`Y`](./y/) Werte auf Null gesetzt. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | Ruft einen Wert ab, der angibt, ob dies`Point` ist leer. |
| [X](../../aspose.psd/point/x/) { get; set; } | Holt oder setzt die x-Koordinate davon`Point` . |
| [Y](../../aspose.psd/point/y/) { get; set; } | Holt oder setzt die y-Koordinate davon`Point` . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | Fügt die angegebenen hinzu[`Size`](../size/) zu den angegebenen`Point` . |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | Konvertiert die angegebene[`PointF`](../pointf/) zu einem`Point` durch Rundung der Werte der[`PointF`](../pointf/) zu den nächsthöheren ganzzahligen Werten. |
| static [Round](../../aspose.psd/point/round/)(PointF) | Konvertiert die angegebene[`PointF`](../pointf/) zu einem`Point` Objekt durch Runden der`Point` Werte auf die nächste ganze Zahl. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | Gibt das Ergebnis der angegebenen Subtraktion zurück[`Size`](../size/) aus dem angegebenen`Point` . |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | Konvertiert die angegebene[`PointF`](../pointf/) zu einem`Point` durch Abschneiden der Werte der`Point` . |
| override [Equals](../../aspose.psd/point/equals/)(object) | Gibt an, ob dies`Point` enthält dieselben Koordinaten wie die angegebenenObject . |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | Gibt dafür einen Hashcode zurück`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | übersetzt dies`Point` durch die angegebenen`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | übersetzt dies`Point`um den angegebenen Betrag. |
| override [ToString](../../aspose.psd/point/tostring/)() | Konvertiert dies`Point` in eine für Menschen lesbare Zeichenfolge. |
| [operator +](../../aspose.psd/point/op_addition/) | übersetzt a`Point` durch eine gegeben[`Size`](../size/) . |
| [operator ==](../../aspose.psd/point/op_equality/) | Vergleicht zwei`Point` Objekte. Das Ergebnis gibt an, ob die Werte der[`X`](./x/) Und[`Y`](./y/) Eigenschaften der beiden`Point` Objekte sind gleich. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | Konvertiert die angegebene`Point` Struktur zu a[`Size`](../size/)Struktur. |
| [implicit operator](../../aspose.psd/point/op_implicit/) | Konvertiert die angegebene`Point` Struktur zu[`PointF`](../pointf/)Struktur. |
| [operator !=](../../aspose.psd/point/op_inequality/) | Vergleicht zwei`Point` Objekte. Das Ergebnis gibt an, ob die Werte der[`X`](./x/) oder[`Y`](./y/) Eigenschaften der beiden`Point` Objekte sind ungleich. |
| [operator -](../../aspose.psd/point/op_subtraction/) | übersetzt a`Point` durch das Negativ eines Gegebenen[`Size`](../size/) . |

### Siehe auch

* namensraum [Aspose.PSD](../../aspose.psd/)
* Montage [Aspose.PSD](../../)


