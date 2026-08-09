---
title: "Struct Point"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Point struct. Stellt ein geordnetes Paar von ganzzahligen x‑ und y‑Koordinaten dar, das einen Punkt in einer zweidimensionalen Ebene definiert."
type: docs
weight: 5760
url: /de/net/aspose.psd/point/
---
{{< psd/tize >}}
## Point structure

Stellt ein geordnetes Paar von ganzzahligen x- und y-Koordinaten dar, das einen Punkt in einer zweidimensionalen Ebene definiert.

```csharp
public struct Point
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Point](point/#constructor_1)(int) | Initialisiert eine neue Instanz der `Point`‑Struktur mit Koordinaten, die durch einen ganzzahligen Wert angegeben werden. |
| [Point](point/#constructor)(Size) | Initialisiert eine neue Instanz der `Point`‑Struktur aus der [`Size`](../size/)‑Struktur. |
| [Point](point/#constructor_2)(int, int) | Initialisiert eine neue Instanz der `Point`‑Struktur mit den angegebenen Koordinaten. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | Gibt eine neue Instanz der `Point`‑Struktur zurück, deren [`X`](./x/)‑ und [`Y`](./y/)‑Werte auf Null gesetzt sind. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | Gibt einen Wert zurück, der angibt, ob dieser `Point` leer ist. |
| [X](../../aspose.psd/point/x/) { get; set; } | Liest oder setzt die x‑Koordinate dieses `Point`. |
| [Y](../../aspose.psd/point/y/) { get; set; } | Liest oder setzt die y‑Koordinate dieses `Point`. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | Addiert das angegebene [`Size`](../size/) zum angegebenen `Point`. |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | Konvertiert das angegebene [`PointF`](../pointf/) in einen `Point`, indem die Werte des [`PointF`](../pointf/) auf die nächsthöheren Ganzzahlen gerundet werden. |
| static [Round](../../aspose.psd/point/round/)(PointF) | Konvertiert das angegebene [`PointF`](../pointf/) in ein `Point`‑Objekt, indem die `Point`‑Werte auf die nächste Ganzzahl gerundet werden. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | Gibt das Ergebnis der Subtraktion des angegebenen [`Size`](../size/) vom angegebenen `Point` zurück. |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | Konvertiert das angegebene [`PointF`](../pointf/) in einen `Point`, indem die Werte des `Point` abgeschnitten werden. |
| override [Equals](../../aspose.psd/point/equals/)(object) | Gibt an, ob dieser `Point` dieselben Koordinaten wie das angegebene Objekt enthält. |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | Gibt einen Hash‑Code für diesen `Point` zurück. |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | Verschiebt diesen `Point` um den angegebenen `Point`. |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | Verschiebt diesen `Point` um den angegebenen Betrag. |
| override [ToString](../../aspose.psd/point/tostring/)() | Konvertiert diesen `Point` in eine menschenlesbare Zeichenkette. |
| [operator +](../../aspose.psd/point/op_addition/) | Verschiebt einen `Point` um ein gegebenes [`Size`](../size/). |
| [operator ==](../../aspose.psd/point/op_equality/) | Vergleicht zwei `Point`‑Objekte. Das Ergebnis gibt an, ob die Werte der [`X`](./x/)‑ und [`Y`](./y/)‑Eigenschaften der beiden `Point`‑Objekte gleich sind. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | Konvertiert die angegebene `Point`-Struktur in eine [`Size`](../size/) Struktur. |
| [implicit operator](../../aspose.psd/point/op_implicit/) | Konvertiert die angegebene `Point`-Struktur in die [`PointF`](../pointf/) Struktur. |
| [operator !=](../../aspose.psd/point/op_inequality/) | Vergleicht zwei `Point`-Objekte. Das Ergebnis gibt an, ob die Werte der [`X`](./x/)- oder [`Y`](./y/)-Eigenschaften der beiden `Point`-Objekte ungleich sind. |
| [operator -](../../aspose.psd/point/op_subtraction/) | Verschiebt ein `Point` um das Negative einer angegebenen [`Size`](../size/). |

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


