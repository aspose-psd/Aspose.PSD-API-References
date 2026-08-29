---
title: "Struktur PointF"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.PointF Struktur. Stellt ein geordnetes Paar von Gleitkomma‑x‑ und y‑Koordinaten dar, das einen Punkt in einer zweidimensionalen Ebene definiert."
type: docs
weight: 5770
url: /de/net/aspose.psd/pointf/
---
{{< psd/tize >}}
## PointF structure

Stellt ein geordnetes Paar von Gleitkomma-x- und y-Koordinaten dar, das einen Punkt in einer zweidimensionalen Ebene definiert.

```csharp
public struct PointF
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PointF](pointf/)(float, float) | Initialisiert eine neue Instanz der `PointF`‑Struktur mit den angegebenen Koordinaten. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Empty](../../aspose.psd/pointf/empty/) { get; } | Ruft eine neue Instanz der `PointF`‑Struktur ab, deren [`X`](./x/)‑ und [`Y`](./y/)‑Werte auf Null gesetzt sind. |
| [IsEmpty](../../aspose.psd/pointf/isempty/) { get; } | Ruft einen Wert ab, der angibt, ob dieses `PointF` leer ist. |
| [X](../../aspose.psd/pointf/x/) { get; set; } | Ruft die x‑Koordinate dieses `PointF` ab oder legt sie fest. |
| [Y](../../aspose.psd/pointf/y/) { get; set; } | Ruft die y‑Koordinate dieses `PointF` ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Add](../../aspose.psd/pointf/add/#add)(PointF, Size) | Verschiebt ein gegebenes `PointF` um die angegebene [`Size`](../size/). |
| static [Add](../../aspose.psd/pointf/add/#add_1)(PointF, SizeF) | Verschiebt ein gegebenes `PointF` um eine angegebene [`SizeF`](../sizef/). |
| static [Subtract](../../aspose.psd/pointf/subtract/#subtract)(PointF, Size) | Verschiebt ein `PointF` um das Negative einer angegebenen Größe. |
| static [Subtract](../../aspose.psd/pointf/subtract/#subtract_1)(PointF, SizeF) | Verschiebt ein `PointF` um das Negative einer angegebenen Größe. |
| override [Equals](../../aspose.psd/pointf/equals/)(object) | Gibt an, ob dieses `PointF` dieselben Koordinaten wie das angegebene Objekt enthält. |
| override [GetHashCode](../../aspose.psd/pointf/gethashcode/)() | Gibt einen Hash‑Code für diese `PointF`‑Struktur zurück. |
| override [ToString](../../aspose.psd/pointf/tostring/)() | Konvertiert dieses `PointF` in eine menschenlesbare Zeichenkette. |
| [operator +](../../aspose.psd/pointf/op_addition/#op_addition) | Verschiebt ein `PointF` um eine gegebene [`Size`](../size/). (2 Operatoren) |
| [operator ==](../../aspose.psd/pointf/op_equality/) | Vergleicht zwei `PointF`‑Strukturen. Das Ergebnis gibt an, ob die Werte der [`X`](./x/)‑ und [`Y`](./y/)‑Eigenschaften der beiden `PointF`‑Strukturen gleich sind. |
| [operator !=](../../aspose.psd/pointf/op_inequality/) | Bestimmt, ob die Koordinaten der angegebenen Punkte nicht gleich sind. |
| [operator -](../../aspose.psd/pointf/op_subtraction/#op_subtraction) | Verschiebt ein `PointF` um das Negative einer angegebenen [`Size`](../size/). (2 Operatoren) |

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


