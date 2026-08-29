---
title: "Klasse Region"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Region Klasse. Beschreibt das Innere einer Grafikform, die aus Rechtecken und Pfaden besteht. Diese Klasse kann nicht abgeleitet werden."
type: docs
weight: 5860
url: /de/net/aspose.psd/region/
---
{{< psd/tize >}}
## Region class

Beschreibt das Innere einer Grafikform, die aus Rechtecken und Pfaden besteht. Diese Klasse kann nicht vererbt werden.

```csharp
public sealed class Region
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Region](region/#constructor)() | Initialisiert ein neues `Region`. |
| [Region](region/#constructor_1)(GraphicsPath) | Initialisiert ein neues `Region` mit dem angegebenen [`GraphicsPath`](../graphicspath/). |
| [Region](region/#constructor_2)(Rectangle) | Initialisiert ein neues `Region` aus der angegebenen [`Rectangle`](../rectangle/) Struktur. |
| [Region](region/#constructor_3)(RectangleF) | Initialisiert ein neues `Region` aus der angegebenen [`RectangleF`](../rectanglef/) Struktur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Complement](../../aspose.psd/region/complement/#complement)(GraphicsPath) | Aktualisiert dieses `Region`, sodass es den Teil des angegebenen [`GraphicsPath`](../graphicspath/) enthält, der nicht mit diesem `Region` überschneidet. |
| [Complement](../../aspose.psd/region/complement/#complement_1)(Rectangle) | Aktualisiert dieses `Region`, sodass es den Teil der angegebenen [`Rectangle`](../rectangle/) Struktur enthält, der nicht mit diesem `Region` überschneidet. |
| [Complement](../../aspose.psd/region/complement/#complement_2)(RectangleF) | Aktualisiert dieses `Region`, sodass es den Teil der angegebenen [`RectangleF`](../rectanglef/) Struktur enthält, der nicht mit diesem `Region` überschneidet. |
| [Complement](../../aspose.psd/region/complement/#complement_3)(Region) | Aktualisiert dieses `Region`, sodass es den Teil des angegebenen `Region` enthält, der nicht mit diesem `Region` überschneidet. |
| [DeepClone](../../aspose.psd/region/deepclone/)() | Erstellt eine exakte Tiefenkopie dieses `Region`. |
| override [Equals](../../aspose.psd/region/equals/#equals_1)(object) | Prüfen, ob Objekte gleich sind. |
| [Equals](../../aspose.psd/region/equals/#equals)(Region, Graphics) | Prüft, ob das angegebene `Region` identisch mit diesem `Region` auf der angegebenen Zeichenfläche ist. |
| [Exclude](../../aspose.psd/region/exclude/#exclude)(GraphicsPath) | Aktualisiert dieses `Region`, sodass es nur den Teil seines Inneren enthält, der nicht mit dem angegebenen [`GraphicsPath`](../graphicspath/) überschneidet. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_1)(Rectangle) | Aktualisiert dieses `Region`, sodass es nur den Teil seines Inneren enthält, der nicht mit der angegebenen [`Rectangle`](../rectangle/) Struktur überschneidet. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_2)(RectangleF) | Aktualisiert dieses `Region`, sodass es nur den Teil seines Inneren enthält, der nicht mit der angegebenen [`RectangleF`](../rectanglef/) Struktur überschneidet. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_3)(Region) | Aktualisiert dieses `Region`, sodass es nur den Teil seines Inneren enthält, der nicht mit dem angegebenen `Region` überschneidet. |
| override [GetHashCode](../../aspose.psd/region/gethashcode/)() | Hashcode des aktuellen Objekts abrufen. |
| [Intersect](../../aspose.psd/region/intersect/#intersect)(GraphicsPath) | Aktualisiert dieses `Region` zur Schnittmenge mit dem angegebenen [`GraphicsPath`](../graphicspath/). |
| [Intersect](../../aspose.psd/region/intersect/#intersect_1)(Rectangle) | Aktualisiert dieses `Region` auf die Schnittmenge von sich selbst mit der angegebenen [`Rectangle`](../rectangle/) Struktur. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_2)(RectangleF) | Aktualisiert dieses `Region` auf die Schnittmenge von sich selbst mit der angegebenen [`RectangleF`](../rectanglef/) Struktur. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_3)(Region) | Aktualisiert dieses `Region` auf die Schnittmenge von sich selbst mit dem angegebenen `Region`. |
| [IsEmpty](../../aspose.psd/region/isempty/)(Graphics) | Prüft, ob dieses `Region` ein leeres Inneres auf der angegebenen Zeichenfläche hat. |
| [IsInfinite](../../aspose.psd/region/isinfinite/)(Graphics) | Prüft, ob dieses `Region` ein unendliches Inneres auf der angegebenen Zeichenfläche hat. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible)(Point) | Prüft, ob die angegebene [`Point`](../point/) Struktur in diesem `Region` enthalten ist. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_2)(PointF) | Prüft, ob die angegebene [`PointF`](../pointf/) Struktur in diesem `Region` enthalten ist. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_4)(Rectangle) | Prüft, ob irgendein Teil der angegebenen [`Rectangle`](../rectangle/) Struktur in diesem `Region` enthalten ist. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_6)(RectangleF) | Prüft, ob irgendein Teil der angegebenen [`RectangleF`](../rectanglef/) Struktur in diesem `Region` enthalten ist. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_11)(float, float) | Prüft, ob der angegebene Punkt in diesem `Region` enthalten ist. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_1)(Point, Graphics) | Prüft, ob die angegebene [`Point`](../point/) Struktur in diesem `Region` enthalten ist, wenn sie mit dem angegebenen [`Graphics`](../graphics/) gezeichnet wird. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_3)(PointF, Graphics) | Prüft, ob die angegebene [`PointF`](../pointf/) Struktur in diesem `Region` enthalten ist, wenn sie mit dem angegebenen [`Graphics`](../graphics/) gezeichnet wird. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_5)(Rectangle, Graphics) | Prüft, ob irgendein Teil der angegebenen [`Rectangle`](../rectangle/) Struktur in diesem `Region` enthalten ist, wenn sie mit dem angegebenen [`Graphics`](../graphics/) gezeichnet wird. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_7)(RectangleF, Graphics) | Prüft, ob irgendein Teil der angegebenen [`RectangleF`](../rectanglef/) Struktur in diesem `Region` enthalten ist, wenn sie mit dem angegebenen [`Graphics`](../graphics/) gezeichnet wird. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_12)(float, float, Graphics) | Prüft, ob der angegebene Punkt in diesem `Region` enthalten ist, wenn er mit dem angegebenen [`Graphics`](../graphics/) gezeichnet wird. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_8)(int, int, Graphics) | Prüft, ob der angegebene Punkt in diesem `Region`-Objekt enthalten ist, wenn er mit dem angegebenen [`Graphics`](../graphics/)-Objekt gezeichnet wird. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_13)(float, float, float, float) | Prüft, ob irgendein Teil des angegebenen Rechtecks in diesem `Region` enthalten ist. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_9)(int, int, int, int) | Prüft, ob irgendein Teil des angegebenen Rechtecks in diesem `Region` enthalten ist. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_14)(float, float, float, float, Graphics) | Prüft, ob irgendein Teil des angegebenen Rechtecks in diesem `Region` enthalten ist, wenn er mit dem angegebenen [`Graphics`](../graphics/) gezeichnet wird. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_10)(int, int, int, int, Graphics) | Prüft, ob irgendein Teil des angegebenen Rechtecks in diesem `Region` enthalten ist, wenn er mit dem angegebenen [`Graphics`](../graphics/) gezeichnet wird. |
| [MakeEmpty](../../aspose.psd/region/makeempty/)() | Initialisiert dieses `Region` mit einem leeren Inneren. |
| [MakeInfinite](../../aspose.psd/region/makeinfinite/)() | Initialisiert dieses `Region`-Objekt mit einem unendlichen Inneren. |
| [Transform](../../aspose.psd/region/transform/)(Matrix) | Transformiert dieses `Region` mit der angegebenen [`Matrix`](../matrix/). |
| [Translate](../../aspose.psd/region/translate/#translate_1)(float, float) | Verschiebt die Koordinaten dieses `Region` um den angegebenen Betrag. |
| [Translate](../../aspose.psd/region/translate/#translate)(int, int) | Verschiebt die Koordinaten dieses `Region` um den angegebenen Betrag. |
| [Union](../../aspose.psd/region/union/#union)(GraphicsPath) | Aktualisiert dieses `Region` auf die Vereinigung von sich selbst und dem angegebenen [`GraphicsPath`](../graphicspath/). |
| [Union](../../aspose.psd/region/union/#union_1)(Rectangle) | Aktualisiert dieses `Region` auf die Vereinigung von sich selbst und der angegebenen [`Rectangle`](../rectangle/) Struktur. |
| [Union](../../aspose.psd/region/union/#union_2)(RectangleF) | Aktualisiert dieses `Region` auf die Vereinigung von sich selbst und der angegebenen [`RectangleF`](../rectanglef/) Struktur. |
| [Union](../../aspose.psd/region/union/#union_3)(Region) | Aktualisiert dieses `Region` zur Vereinigung von sich selbst und dem angegebenen `Region`. |
| [Xor](../../aspose.psd/region/xor/#xor)(GraphicsPath) | Aktualisiert dieses `Region` zur Vereinigung minus der Schnittmenge von sich selbst mit dem angegebenen [`GraphicsPath`](../graphicspath/). |
| [Xor](../../aspose.psd/region/xor/#xor_1)(Rectangle) | Aktualisiert dieses `Region` zur Vereinigung minus der Schnittmenge von sich selbst mit der angegebenen [`Rectangle`](../rectangle/) Struktur. |
| [Xor](../../aspose.psd/region/xor/#xor_2)(RectangleF) | Aktualisiert dieses `Region` zur Vereinigung minus der Schnittmenge von sich selbst mit der angegebenen [`RectangleF`](../rectanglef/) Struktur. |
| [Xor](../../aspose.psd/region/xor/#xor_3)(Region) | Aktualisiert dieses `Region` zur Vereinigung minus der Schnittmenge von sich selbst mit dem angegebenen `Region`. |

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


