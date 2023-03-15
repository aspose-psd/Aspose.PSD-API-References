---
title: Struct Rectangle
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.Rectangle structuur. Speichert einen Satz von vier Ganzzahlen die die Position und Größe eines Rechtecks darstellen.
type: docs
weight: 5340
url: /de/net/aspose.psd/rectangle/
---
## Rectangle structure

Speichert einen Satz von vier Ganzzahlen, die die Position und Größe eines Rechtecks darstellen.

```csharp
public struct Rectangle
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | Initialisiert eine neue Instanz von`Rectangle` Struktur mit der angegebenen Position und Größe. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | Initialisiert eine neue Instanz von`Rectangle` Struktur mit der angegebenen Position und Größe. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | Ruft eine neue Instanz von ab`Rectangle` Struktur, die hat[`X`](./x/) ,[`Y`](./y/) ,[`Width`](./width/) Und[`Height`](./height/) Werte auf Null gesetzt. |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | Holt oder setzt die y-Koordinate, die die Summe von ist[`Y`](./y/) Und[`Height`](./height/) Eigenschaftswerte davon`Rectangle`Struktur. |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | Holt oder setzt die Höhe davon`Rectangle`Struktur. |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | Ruft einen Wert ab, der angibt, ob alle numerischen Eigenschaften von this`Rectangle` Werte von Null haben. |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | Holt oder setzt die x-Koordinate der linken Kante davon`Rectangle`Struktur. |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | Holt oder setzt die Koordinaten der oberen linken Ecke davon`Rectangle`Struktur. |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | Holt oder setzt die x-Koordinate, die die Summe von ist[`X`](./x/) Und[`Width`](./width/) Eigenschaftswerte davon`Rectangle`Struktur. |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | Holt oder setzt die Größe davon`Rectangle` . |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | Holt oder setzt die y-Koordinate der Oberkante davon`Rectangle`Struktur. |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | Holt oder setzt die Breite davon`Rectangle`Struktur. |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | Liest oder setzt die x-Koordinate der oberen linken Ecke davon`Rectangle`Struktur. |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | Holt oder setzt die y-Koordinate der oberen linken Ecke davon`Rectangle`Struktur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | Konvertiert die angegebene[`RectangleF`](../rectanglef/) Struktur zu a`Rectangle` Struktur durch Rundung der[`RectangleF`](../rectanglef/) Werte auf die nächsthöheren ganzzahligen Werte. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | Erstellt ein`Rectangle` Struktur mit den angegebenen Kantenpositionen. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | Erstellt eine neue`Rectangle` von zwei angegebenen Punkten. Zwei Vertikalen des Geschaffenen`Rectangle` wird gleich der bestandenen sein*point1* Und*point2* . Dies wären typischerweise die gegenüberliegenden Scheitelpunkte. |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | Erstellt und gibt eine vergrößerte Kopie der angegebenen zurück`Rectangle`Struktur. Die Kopie wird um den angegebenen Betrag aufgeblasen. Das Original`Rectangle` Struktur bleibt unverändert. |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | Gibt ein Drittel zurück`Rectangle` Struktur, die die Schnittmenge von zwei anderen darstellt`Rectangle` Strukturen. Wenn es keine Schnittmenge gibt, ein Leerzeichen`Rectangle` wird zurückgegeben. |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | Konvertiert die angegebene[`RectangleF`](../rectanglef/) zu einem`Rectangle` durch Runden der[`RectangleF`](../rectanglef/) Werte auf die nächsten ganzzahligen Werte. |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | Konvertiert die angegebene[`RectangleF`](../rectanglef/) zu einem`Rectangle` durch Abschneiden der[`RectangleF`](../rectanglef/) Werte. |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | erhält a`Rectangle` Struktur, die die Vereinigung von zwei enthält`Rectangle` Strukturen. |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | Bestimmt, ob der angegebene Punkt darin enthalten ist`Rectangle`Struktur. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | Bestimmt, ob der rechteckige Bereich dargestellt wird durch*rect* ist ganz darin enthalten`Rectangle`Struktur. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | Bestimmt, ob der angegebene Punkt darin enthalten ist`Rectangle`Struktur. |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | Testet ob*obj* ist ein`Rectangle`Struktur mit der gleichen Lage und Größe von diesem`Rectangle`Struktur. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | Gibt den Hash-Code dafür zurück`Rectangle`Struktur. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | bläst dies auf`Rectangle`um den angegebenen Betrag. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | bläst dies auf`Rectangle`um den angegebenen Betrag. |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | Ersetzt dies`Rectangle` mit dem Schnittpunkt von sich selbst und dem angegebenen`Rectangle` . |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | Bestimmt, ob sich dieses Rechteck mit schneidet*rect* . |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | Normalisiert das Rechteck, indem Breite und Höhe positiv werden, links kleiner als rechts und oben kleiner als unten. |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | Wandelt die Attribute davon um`Rectangle` in eine für Menschen lesbare Zeichenfolge. |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | Testet ob zwei`Rectangle` Strukturen haben dieselbe Position und Größe. |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | Testet ob zwei`Rectangle` Strukturen unterscheiden sich in Lage oder Größe. |

### Siehe auch

* namensraum [Aspose.PSD](../../aspose.psd/)
* Montage [Aspose.PSD](../../)


