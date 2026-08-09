---
title: "Struktur Rectangle"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Rectangle-Struktur. Speichert ein Set von vier Ganzzahlen, die den Ort und die Größe eines Rechtecks darstellen."
type: docs
weight: 5840
url: /de/net/aspose.psd/rectangle/
---
{{< psd/tize >}}
## Rectangle structure

Speichert ein Set von vier Ganzzahlen, das die Position und Größe eines Rechtecks darstellt.

```csharp
public struct Rectangle
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | Initialisiert eine neue Instanz der `Rectangle`-Struktur mit dem angegebenen Ort und der angegebenen Größe. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | Initialisiert eine neue Instanz der `Rectangle`-Struktur mit dem angegebenen Ort und der angegebenen Größe. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | Gibt eine neue Instanz der `Rectangle`-Struktur zurück, deren [`X`](./x/), [`Y`](./y/), [`Width`](./width/) und [`Height`](./height/)-Werte auf Null gesetzt sind. |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | Liest oder setzt die y-Koordinate, die die Summe der [`Y`](./y/)- und [`Height`](./height/)-Eigenschaftswerte dieser `Rectangle`-Struktur ist. |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | Liest oder setzt die Höhe dieser `Rectangle`-Struktur. |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | Gibt einen Wert zurück, der angibt, ob alle numerischen Eigenschaften dieser `Rectangle`-Struktur den Wert Null haben. |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | Liest oder setzt die x-Koordinate der linken Kante dieser `Rectangle`-Struktur. |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | Liest oder setzt die Koordinaten der oberen linken Ecke dieser `Rectangle`-Struktur. |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | Liest oder setzt die x-Koordinate, die die Summe der [`X`](./x/)- und [`Width`](./width/)-Eigenschaftswerte dieser `Rectangle`-Struktur ist. |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | Liest oder setzt die Größe dieser `Rectangle`. |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | Liest oder setzt die y-Koordinate der oberen Kante dieser `Rectangle`-Struktur. |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | Liest oder setzt die Breite dieser `Rectangle`-Struktur. |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | Liest oder setzt die x-Koordinate der oberen linken Ecke dieser `Rectangle`-Struktur. |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | Liest oder setzt die y-Koordinate der oberen linken Ecke dieser `Rectangle`-Struktur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | Konvertiert die angegebene [`RectangleF`](../rectanglef/)-Struktur in eine `Rectangle`-Struktur, indem die [`RectangleF`](../rectanglef/)-Werte auf die nächsthöheren Ganzzahlen gerundet werden. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | Erstellt eine `Rectangle`-Struktur mit den angegebenen Kantenpositionen. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | Erstellt ein neues `Rectangle` aus zwei angegebenen Punkten. Zwei Vertikalen des erstellten `Rectangle` entsprechen den übergebenen *point1* und *point2*. Diese sind typischerweise die gegenüberliegenden Eckpunkte. |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | Erstellt und gibt eine aufgeblähte Kopie der angegebenen `Rectangle`-Struktur zurück. Die Kopie wird um den angegebenen Betrag aufgebläht. Die ursprüngliche `Rectangle`-Struktur bleibt unverändert. |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | Gibt eine dritte `Rectangle`-Struktur zurück, die die Schnittmenge zweier anderer `Rectangle`-Strukturen darstellt. Wenn es keine Schnittmenge gibt, wird ein leeres `Rectangle` zurückgegeben. |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | Konvertiert das angegebene [`RectangleF`](../rectanglef/) in ein `Rectangle`, indem die [`RectangleF`](../rectanglef/)-Werte auf die nächstgelegenen Ganzzahlen gerundet werden. |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | Konvertiert das angegebene [`RectangleF`](../rectanglef/) in ein `Rectangle`, indem die [`RectangleF`](../rectanglef/)-Werte abgeschnitten werden. |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | Gibt eine `Rectangle`-Struktur zurück, die die Vereinigung zweier `Rectangle`-Strukturen enthält. |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | Bestimmt, ob der angegebene Punkt innerhalb dieser `Rectangle`-Struktur enthalten ist. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | Bestimmt, ob der durch *rect* dargestellte rechteckige Bereich vollständig innerhalb dieser `Rectangle`-Struktur enthalten ist. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | Bestimmt, ob der angegebene Punkt innerhalb dieser `Rectangle`-Struktur enthalten ist. |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | Prüft, ob *obj* eine `Rectangle`-Struktur mit derselben Position und Größe wie diese `Rectangle`-Struktur ist. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | Gibt den Hashcode für diese `Rectangle`-Struktur zurück. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | Vergrößert diese `Rectangle` um den angegebenen Betrag. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | Vergrößert diese `Rectangle` um den angegebenen Betrag. |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | Ersetzt diese `Rectangle` durch die Schnittmenge von ihr selbst und der angegebenen `Rectangle`. |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | Bestimmt, ob dieses Rechteck mit *rect* schneidet. |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | Normalisiert das Rechteck, indem Breite und Höhe positiv gemacht werden, links kleiner als rechts und oben kleiner als unten ist. |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | Konvertiert die Attribute dieser `Rectangle` in einen menschenlesbaren String. |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | Prüft, ob zwei `Rectangle`-Strukturen dieselbe Position und Größe haben. |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | Prüft, ob sich zwei `Rectangle`-Strukturen in Position oder Größe unterscheiden. |

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


