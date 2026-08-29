---
title: "Struktur RectangleF"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.RectangleF Struktur. Speichert ein Set von vier Gleitkommazahlen, die den Ort und die Größe eines Rechtecks darstellen."
type: docs
weight: 5850
url: /de/net/aspose.psd/rectanglef/
---
{{< psd/tize >}}
## RectangleF structure

Speichert ein Set von vier Gleitkommazahlen, das die Position und Größe eines Rechtecks darstellt.

```csharp
public struct RectangleF
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | Initialisiert eine neue Instanz der `RectangleF`-Struktur mit dem angegebenen Ort und der Größe. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | Initialisiert eine neue Instanz der `RectangleF`-Struktur mit dem angegebenen Ort und der Größe. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | Gibt eine neue Instanz der `RectangleF`-Struktur zurück, die die Werte [`X`](./x/), [`Y`](./y/), [`Width`](./width/) und [`Height`](./height/) auf Null gesetzt hat. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | Liest oder setzt die y-Koordinate, die die Summe von [`Y`](./y/) und [`Height`](./height/) dieser `RectangleF`-Struktur ist. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | Liest oder setzt die Höhe dieser `RectangleF`-Struktur. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | Gibt einen Wert zurück, der angibt, ob die [`Width`](./width/)- oder [`Height`](./height/)-Eigenschaft dieser `RectangleF` den Wert Null hat. |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | Liest oder setzt die x-Koordinate der linken Kante dieser `RectangleF`-Struktur. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | Liest oder setzt die Koordinaten der oberen linken Ecke dieser `RectangleF`-Struktur. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | Liest oder setzt die x-Koordinate, die die Summe von [`X`](./x/) und [`Width`](./width/) dieser `RectangleF`-Struktur ist. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | Liest oder setzt die Größe dieser `RectangleF`. |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | Liest oder setzt die y-Koordinate der oberen Kante dieser `RectangleF`-Struktur. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | Liest oder setzt die Breite dieser `RectangleF`-Struktur. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | Liest oder setzt die x-Koordinate der oberen linken Ecke dieser `RectangleF`-Struktur. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | Liest oder setzt die y-Koordinate der oberen linken Ecke dieser `RectangleF`-Struktur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | Erstellt eine `RectangleF`-Struktur mit der oberen linken Ecke und der unteren rechten Ecke an den angegebenen Positionen. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | Erstellt ein neues [`Rectangle`](../rectangle/) aus zwei angegebenen Punkten. Zwei Eckpunkte des erstellten [`Rectangle`](../rectangle/) entsprechen den übergebenen *point1* und *point2*. Diese sind typischerweise die gegenüberliegenden Eckpunkte. |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | Erstellt und gibt eine aufgeblähte Kopie der angegebenen `RectangleF`-Struktur zurück. Die Kopie wird um den angegebenen Betrag aufgebläht. Das ursprüngliche Rechteck bleibt unverändert. |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | Gibt eine `RectangleF`-Struktur zurück, die die Schnittmenge zweier Rechtecke darstellt. Wenn keine Schnittmenge existiert, wird ein leeres `RectangleF` zurückgegeben. |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | Erstellt das kleinste mögliche dritte Rechteck, das beide Rechtecke, die eine Vereinigung bilden, enthalten kann. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | Bestimmt, ob der angegebene Punkt innerhalb dieser `RectangleF`-Struktur liegt. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | Bestimmt, ob der durch *rect* dargestellte rechteckige Bereich vollständig innerhalb dieser `RectangleF`-Struktur liegt. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | Bestimmt, ob der angegebene Punkt innerhalb dieser `RectangleF`-Struktur liegt. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | Prüft, ob *obj* ein `RectangleF` mit derselben Position und Größe wie dieses `RectangleF` ist. |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | Liefert den Hashcode für diese `RectangleF`-Struktur. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | Bläht dieses `RectangleF` um den angegebenen Betrag auf. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | Bläht diese `RectangleF`-Struktur um den angegebenen Betrag auf. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | Ersetzt diese `RectangleF`-Struktur durch die Schnittmenge von ihr selbst und der angegebenen `RectangleF`-Struktur. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | Bestimmt, ob dieses Rechteck mit *rect* schneidet. |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | Normalisiert das Rechteck, indem Breite und Höhe positiv gemacht werden, links kleiner als rechts und oben kleiner als unten ist. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | Konvertiert die Attribute dieses `RectangleF` in eine menschenlesbare Zeichenkette. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | Implementiert den Operator /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | Prüft, ob zwei `RectangleF`-Strukturen dieselbe Position und Größe haben. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | Konvertiert die angegebene [`Rectangle`](../rectangle/)-Struktur in eine `RectangleF`-Struktur. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | Prüft, ob sich zwei `RectangleF`-Strukturen in Position oder Größe unterscheiden. |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | Implementiert den Operator *. |

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


