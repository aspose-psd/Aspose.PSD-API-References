---
title: Struct RectangleF
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.RectangleF structuur. Speichert einen Satz von vier Fließkommazahlen die die Position und Größe eines Rechtecks darstellen.
type: docs
weight: 5350
url: /de/net/aspose.psd/rectanglef/
---
## RectangleF structure

Speichert einen Satz von vier Fließkommazahlen, die die Position und Größe eines Rechtecks darstellen.

```csharp
public struct RectangleF
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | Initialisiert eine neue Instanz von`RectangleF` Struktur mit der angegebenen Position und Größe. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | Initialisiert eine neue Instanz von`RectangleF` Struktur mit der angegebenen Position und Größe. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | Ruft eine neue Instanz von ab`RectangleF` Struktur, die hat[`X`](./x/) ,[`Y`](./y/) ,[`Width`](./width/) Und[`Height`](./height/) Werte auf Null gesetzt. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | Holt oder setzt die y-Koordinate, die die Summe von ist[`Y`](./y/) Und[`Height`](./height/) von diesem`RectangleF`Struktur. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | Holt oder setzt die Höhe davon`RectangleF`Struktur. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | Ruft einen Wert ab, der angibt, ob die[`Width`](./width/) oder[`Height`](./height/) Eigentum davon`RectangleF` hat den Wert null. |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | Holt oder setzt die x-Koordinate der linken Kante davon`RectangleF`Struktur. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | Holt oder setzt die Koordinaten der oberen linken Ecke davon`RectangleF`Struktur. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | Holt oder setzt die x-Koordinate, die die Summe von ist[`X`](./x/) Und[`Width`](./width/) von diesem`RectangleF`Struktur. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | Holt oder setzt die Größe davon`RectangleF` . |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | Holt oder setzt die y-Koordinate der Oberkante davon`RectangleF`Struktur. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | Holt oder setzt die Breite davon`RectangleF`Struktur. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | Liest oder setzt die x-Koordinate der oberen linken Ecke davon`RectangleF`Struktur. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | Holt oder setzt die y-Koordinate der oberen linken Ecke davon`RectangleF`Struktur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | Erstellt ein`RectangleF` Struktur mit oberer linker Ecke und unterer rechter Ecke an den angegebenen Positionen. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | Erstellt eine neue[`Rectangle`](../rectangle/) von zwei angegebenen Punkten. Zwei Scheitelpunkte des Geschaffenen[`Rectangle`](../rectangle/) wird gleich der bestandenen sein*point1* Und*point2* . Dies wären typischerweise die gegenüberliegenden Scheitelpunkte. |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | Erstellt und gibt eine vergrößerte Kopie der angegebenen zurück`RectangleF`Struktur. Die Kopie wird um den angegebenen Betrag aufgeblasen. Das ursprüngliche Rechteck bleibt unverändert. |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | Gibt a zurück`RectangleF` Struktur, die den Schnittpunkt zweier Rechtecke darstellt. Wenn es keine Kreuzung gibt, und leer`RectangleF` wird zurückgegeben. |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | Erstellt das kleinstmögliche dritte Rechteck, das beide von zwei Rechtecken enthalten kann, die eine Vereinigung bilden. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | Bestimmt, ob der angegebene Punkt darin enthalten ist`RectangleF`Struktur. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | Bestimmt, ob der rechteckige Bereich dargestellt wird durch*rect* ist ganz darin enthalten`RectangleF`Struktur. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | Bestimmt, ob der angegebene Punkt darin enthalten ist`RectangleF`Struktur. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | Testet ob*obj* ist ein`RectangleF` mit der gleichen Lage und Größe von diesem`RectangleF` . |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | Ruft den Hash-Code dafür ab`RectangleF`Struktur. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | bläst dies auf`RectangleF`um den angegebenen Betrag. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | bläst dies auf`RectangleF` Struktur um den angegebenen Betrag. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | Ersetzt dies`RectangleF`Struktur mit der Schnittmenge von sich selbst und der angegebenen`RectangleF`Struktur. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | Bestimmt, ob sich dieses Rechteck mit schneidet*rect* . |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | Normalisiert das Rechteck, indem Breite und Höhe positiv werden, links kleiner als rechts und oben kleiner als unten. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | Wandelt die Attribute davon um`RectangleF` in eine für Menschen lesbare Zeichenfolge. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | Implementiert den Operator /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | Testet ob zwei`RectangleF` Strukturen haben dieselbe Position und Größe. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | Konvertiert die angegebene[`Rectangle`](../rectangle/) Struktur zu a`RectangleF`Struktur. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | Testet ob zwei`RectangleF` Strukturen unterscheiden sich in Lage oder Größe. |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | Implementiert den Operator *. |

### Siehe auch

* namensraum [Aspose.PSD](../../aspose.psd/)
* Montage [Aspose.PSD](../../)


