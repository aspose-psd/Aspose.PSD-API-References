---
title: Rectangle
second_title: Aspose.PSD für .NET-API-Referenz
description: Speichert einen Satz von vier Ganzzahlen die die Position und Größe eines Rechtecks darstellen.
type: docs
weight: 5270
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
| [Rectangle](rectangle#constructor)(Point, Size) | Initialisiert eine neue Instanz von[`Rectangle`](../rectangle) Struktur mit der angegebenen Position und Größe. |
| [Rectangle](rectangle#constructor_1)(int, int, int, int) | Initialisiert eine neue Instanz von[`Rectangle`](../rectangle) Struktur mit der angegebenen Position und Größe. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty) { get; } | Ruft eine neue Instanz von ab[`Rectangle`](../rectangle) Struktur, die hat[`X`](./x) ,[`Y`](./y) ,[`Width`](./width) und[`Height`](./height) Werte auf Null gesetzt. |
| [Bottom](../../aspose.psd/rectangle/bottom) { get; set; } | Holt oder setzt die y-Koordinate, die die Summe von ist[`Y`](./y) und[`Height`](./height) Eigenschaftswerte davon[`Rectangle`](../rectangle)Struktur. |
| [Height](../../aspose.psd/rectangle/height) { get; set; } | Holt oder setzt die Höhe davon[`Rectangle`](../rectangle)Struktur. |
| [IsEmpty](../../aspose.psd/rectangle/isempty) { get; } | Ruft einen Wert ab, der angibt, ob alle numerischen Eigenschaften von this[`Rectangle`](../rectangle) Werte von Null haben. |
| [Left](../../aspose.psd/rectangle/left) { get; set; } | Holt oder setzt die x-Koordinate der linken Kante davon[`Rectangle`](../rectangle)Struktur. |
| [Location](../../aspose.psd/rectangle/location) { get; set; } | Holt oder setzt die Koordinaten der oberen linken Ecke davon[`Rectangle`](../rectangle)Struktur. |
| [Right](../../aspose.psd/rectangle/right) { get; set; } | Holt oder setzt die x-Koordinate, die die Summe von ist[`X`](./x) und[`Width`](./width) Eigenschaftswerte davon[`Rectangle`](../rectangle)Struktur. |
| [Size](../../aspose.psd/rectangle/size) { get; set; } | Holt oder setzt die Größe davon[`Rectangle`](../rectangle) . |
| [Top](../../aspose.psd/rectangle/top) { get; set; } | Holt oder setzt die y-Koordinate der Oberkante davon[`Rectangle`](../rectangle)Struktur. |
| [Width](../../aspose.psd/rectangle/width) { get; set; } | Holt oder setzt die Breite davon[`Rectangle`](../rectangle)Struktur. |
| [X](../../aspose.psd/rectangle/x) { get; set; } | Liest oder setzt die x-Koordinate der oberen linken Ecke davon[`Rectangle`](../rectangle)Struktur. |
| [Y](../../aspose.psd/rectangle/y) { get; set; } | Holt oder setzt die y-Koordinate der oberen linken Ecke davon[`Rectangle`](../rectangle)Struktur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling)(RectangleF) | Konvertiert die angegebene[`RectangleF`](../rectanglef) Struktur zu a[`Rectangle`](../rectangle) Struktur durch Rundung der[`RectangleF`](../rectanglef) Werte auf die nächsthöheren ganzzahligen Werte. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom)(int, int, int, int) | Erstellt ein[`Rectangle`](../rectangle) Struktur mit den angegebenen Kantenpositionen. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints)(Point, Point) | Erstellt eine neue[`Rectangle`](../rectangle) von zwei angegebenen Punkten. Zwei Vertikalen des Geschaffenen[`Rectangle`](../rectangle) wird gleich der bestandenen sein*point1* und*point2* . Dies wären typischerweise die gegenüberliegenden Scheitelpunkte. |
| static [Inflate](../../aspose.psd/rectangle/inflate)(Rectangle, int, int) | Erstellt und gibt eine vergrößerte Kopie der angegebenen zurück[`Rectangle`](../rectangle) Struktur. Die Kopie wird um den angegebenen Betrag aufgeblasen. Das Original[`Rectangle`](../rectangle) Struktur bleibt unverändert. |
| static [Intersect](../../aspose.psd/rectangle/intersect)(Rectangle, Rectangle) | Gibt ein Drittel zurück[`Rectangle`](../rectangle) Struktur, die die Schnittmenge von zwei anderen darstellt[`Rectangle`](../rectangle) Strukturen. Wenn es keine Schnittmenge gibt, ein Leerzeichen[`Rectangle`](../rectangle) wird zurückgegeben. |
| static [Round](../../aspose.psd/rectangle/round)(RectangleF) | Konvertiert die angegebene[`RectangleF`](../rectanglef) zu einem[`Rectangle`](../rectangle) durch Runden der[`RectangleF`](../rectanglef) Werte auf die nächsten ganzzahligen Werte. |
| static [Truncate](../../aspose.psd/rectangle/truncate)(RectangleF) | Konvertiert die angegebene[`RectangleF`](../rectanglef) zu einem[`Rectangle`](../rectangle) durch Abschneiden der[`RectangleF`](../rectanglef) Werte. |
| static [Union](../../aspose.psd/rectangle/union)(Rectangle, Rectangle) | erhält a[`Rectangle`](../rectangle) Struktur, die die Vereinigung von zwei enthält[`Rectangle`](../rectangle) Strukturen. |
| [Contains](../../aspose.psd/rectangle/contains#contains)(Point) | Bestimmt, ob der angegebene Punkt darin enthalten ist[`Rectangle`](../rectangle)Struktur. |
| [Contains](../../aspose.psd/rectangle/contains#contains_1)(Rectangle) | Bestimmt, ob der rechteckige Bereich dargestellt wird durch*rect* ist ganz darin enthalten[`Rectangle`](../rectangle)Struktur. |
| [Contains](../../aspose.psd/rectangle/contains#contains_2)(int, int) | Bestimmt, ob der angegebene Punkt darin enthalten ist[`Rectangle`](../rectangle)Struktur. |
| override [Equals](../../aspose.psd/rectangle/equals)(object) | Testet ob*obj* ist ein[`Rectangle`](../rectangle) Struktur mit der gleichen Lage und Größe von diesem[`Rectangle`](../rectangle)Struktur. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode)() | Gibt den Hash-Code dafür zurück[`Rectangle`](../rectangle)Struktur. |
| [Inflate](../../aspose.psd/rectangle/inflate#inflate)(Size) | bläst dies auf[`Rectangle`](../rectangle) um den angegebenen Betrag. |
| [Inflate](../../aspose.psd/rectangle/inflate#inflate_1)(int, int) | bläst dies auf[`Rectangle`](../rectangle) um den angegebenen Betrag. |
| [Intersect](../../aspose.psd/rectangle/intersect)(Rectangle) | Ersetzt dies[`Rectangle`](../rectangle) mit dem Schnittpunkt von sich selbst und dem angegebenen[`Rectangle`](../rectangle) . |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith)(Rectangle) | Bestimmt, ob sich dieses Rechteck mit schneidet*rect* . |
| [Normalize](../../aspose.psd/rectangle/normalize)() | Normalisiert das Rechteck, indem Breite und Höhe positiv werden, links kleiner als rechts und oben kleiner als unten. |
| [Offset](../../aspose.psd/rectangle/offset#offset)(Point) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| [Offset](../../aspose.psd/rectangle/offset#offset_1)(int, int) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| override [ToString](../../aspose.psd/rectangle/tostring)() | Wandelt die Attribute davon um[`Rectangle`](../rectangle) in eine für Menschen lesbare Zeichenfolge. |
| [operator ==](../../aspose.psd/rectangle/op_equality) | Testet ob zwei[`Rectangle`](../rectangle) Strukturen haben dieselbe Position und Größe. |
| [operator !=](../../aspose.psd/rectangle/op_inequality) | Testet ob zwei[`Rectangle`](../rectangle) Strukturen unterscheiden sich in Lage oder Größe. |

### Siehe auch

* namensraum [Aspose.PSD](../../aspose.psd)
* Montage [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
