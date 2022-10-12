---
title: Region
second_title: Aspose.PSD für .NET-API-Referenz
description: Beschreibt das Innere einer Grafikform die aus Rechtecken und Pfaden besteht. Diese Klasse kann nicht vererbt werden.
type: docs
weight: 5290
url: /de/net/aspose.psd/region/
---
## Region class

Beschreibt das Innere einer Grafikform, die aus Rechtecken und Pfaden besteht. Diese Klasse kann nicht vererbt werden.

```csharp
public sealed class Region
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Region](region#constructor)() | Initialisiert eine neue[`Region`](../region) . |
| [Region](region#constructor_1)(GraphicsPath) | Initialisiert eine neue[`Region`](../region) mit den angegebenen[`GraphicsPath`](../graphicspath) . |
| [Region](region#constructor_2)(Rectangle) | Initialisiert eine neue[`Region`](../region) aus dem angegebenen[`Rectangle`](../rectangle)Struktur. |
| [Region](region#constructor_3)(RectangleF) | Initialisiert eine neue[`Region`](../region) aus dem angegebenen[`RectangleF`](../rectanglef)Struktur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Complement](../../aspose.psd/region/complement#complement)(GraphicsPath) | aktualisiert dies[`Region`](../region) um den Teil des angegebenen zu enthalten[`GraphicsPath`](../graphicspath) das überschneidet sich damit nicht[`Region`](../region) . |
| [Complement](../../aspose.psd/region/complement#complement_1)(Rectangle) | aktualisiert dies[`Region`](../region) um den Teil des angegebenen zu enthalten[`Rectangle`](../rectangle) Struktur, die sich damit nicht überschneidet[`Region`](../region) . |
| [Complement](../../aspose.psd/region/complement#complement_2)(RectangleF) | aktualisiert dies[`Region`](../region) um den Teil des angegebenen zu enthalten[`RectangleF`](../rectanglef) Struktur, die sich damit nicht überschneidet[`Region`](../region) . |
| [Complement](../../aspose.psd/region/complement#complement_3)(Region) | aktualisiert dies[`Region`](../region) um den Teil des angegebenen zu enthalten[`Region`](../region) das überschneidet sich damit nicht[`Region`](../region) . |
| [DeepClone](../../aspose.psd/region/deepclone)() | Erstellt eine exakte tiefe Kopie davon[`Region`](../region) . |
| [Equals](../../aspose.psd/region/equals#equals)(Region, Graphics) | Testet, ob die angegebene[`Region`](../region) ist damit identisch[`Region`](../region) auf der angegebenen Zeichenfläche. |
| [Exclude](../../aspose.psd/region/exclude#exclude)(GraphicsPath) | aktualisiert dies[`Region`](../region) um nur den Teil seines Inneren zu enthalten, der sich nicht mit dem angegebenen schneidet[`GraphicsPath`](../graphicspath) . |
| [Exclude](../../aspose.psd/region/exclude#exclude_1)(Rectangle) | aktualisiert dies[`Region`](../region) um nur den Teil seines Inneren zu enthalten, der sich nicht mit dem angegebenen schneidet[`Rectangle`](../rectangle)Struktur. |
| [Exclude](../../aspose.psd/region/exclude#exclude_2)(RectangleF) | aktualisiert dies[`Region`](../region) um nur den Teil seines Inneren zu enthalten, der sich nicht mit dem angegebenen schneidet[`RectangleF`](../rectanglef)Struktur. |
| [Exclude](../../aspose.psd/region/exclude#exclude_3)(Region) | aktualisiert dies[`Region`](../region) um nur den Teil seines Inneren zu enthalten, der sich nicht mit dem angegebenen schneidet[`Region`](../region) . |
| [Intersect](../../aspose.psd/region/intersect#intersect)(GraphicsPath) | aktualisiert dies[`Region`](../region) zum Schnittpunkt von sich selbst mit dem angegebenen[`GraphicsPath`](../graphicspath) . |
| [Intersect](../../aspose.psd/region/intersect#intersect_1)(Rectangle) | aktualisiert dies[`Region`](../region) zum Schnittpunkt von sich selbst mit dem angegebenen[`Rectangle`](../rectangle)Struktur. |
| [Intersect](../../aspose.psd/region/intersect#intersect_2)(RectangleF) | aktualisiert dies[`Region`](../region) zum Schnittpunkt von sich selbst mit dem angegebenen[`RectangleF`](../rectanglef)Struktur. |
| [Intersect](../../aspose.psd/region/intersect#intersect_3)(Region) | aktualisiert dies[`Region`](../region) zum Schnittpunkt von sich selbst mit dem angegebenen[`Region`](../region) . |
| [IsEmpty](../../aspose.psd/region/isempty)(Graphics) | Testet ob dies[`Region`](../region) hat einen leeren Innenraum auf der angegebenen Zeichenfläche. |
| [IsInfinite](../../aspose.psd/region/isinfinite)(Graphics) | Testet ob dies[`Region`](../region) hat einen unendlichen Innenraum auf der angegebenen Zeichenfläche. |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible)(Point) | Testet, ob die angegebene[`Point`](../point)Struktur ist darin enthalten[`Region`](../region) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_2)(PointF) | Testet, ob die angegebene[`PointF`](../pointf)Struktur ist darin enthalten[`Region`](../region) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_4)(Rectangle) | Testet, ob irgendein Teil der angegebenen[`Rectangle`](../rectangle)Struktur ist darin enthalten[`Region`](../region) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_6)(RectangleF) | Testet, ob irgendein Teil der angegebenen[`RectangleF`](../rectanglef)Struktur ist darin enthalten[`Region`](../region) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_11)(float, float) | Prüft, ob der angegebene Punkt darin enthalten ist[`Region`](../region) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_1)(Point, Graphics) | Testet, ob die angegebene[`Point`](../point)Struktur ist darin enthalten[`Region`](../region) wenn gezogen mit den angegebenen[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_3)(PointF, Graphics) | Testet, ob die angegebene[`PointF`](../pointf)Struktur ist darin enthalten[`Region`](../region) wenn gezogen mit den angegebenen[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_5)(Rectangle, Graphics) | Testet, ob irgendein Teil der angegebenen[`Rectangle`](../rectangle)Struktur ist darin enthalten[`Region`](../region) wenn gezogen mit den angegebenen[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_7)(RectangleF, Graphics) | Testet, ob irgendein Teil der angegebenen[`RectangleF`](../rectanglef)Struktur ist darin enthalten[`Region`](../region) wenn gezogen mit den angegebenen[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_12)(float, float, Graphics) | Prüft, ob der angegebene Punkt darin enthalten ist[`Region`](../region) wenn gezogen mit den angegebenen[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_8)(int, int, Graphics) | Prüft, ob der angegebene Punkt darin enthalten ist[`Region`](../region) Objekt beim Zeichnen mit dem angegebenen[`Graphics`](../graphics) Objekt. |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_13)(float, float, float, float) | Testet, ob ein Teil des angegebenen Rechtecks darin enthalten ist[`Region`](../region) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_9)(int, int, int, int) | Testet, ob ein Teil des angegebenen Rechtecks darin enthalten ist[`Region`](../region) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_14)(float, float, float, float, Graphics) | Testet, ob ein Teil des angegebenen Rechtecks darin enthalten ist[`Region`](../region) wenn gezogen mit den angegebenen[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_10)(int, int, int, int, Graphics) | Testet, ob ein Teil des angegebenen Rechtecks darin enthalten ist[`Region`](../region) wenn gezogen mit den angegebenen[`Graphics`](../graphics) . |
| [MakeEmpty](../../aspose.psd/region/makeempty)() | Initialisiert dies[`Region`](../region) zu einem leeren Innenraum. |
| [MakeInfinite](../../aspose.psd/region/makeinfinite)() | Initialisiert dies[`Region`](../region) Objekt zu einem unendlichen Inneren. |
| [Transform](../../aspose.psd/region/transform)(Matrix) | Transformiert dies[`Region`](../region) durch die angegebenen[`Matrix`](../matrix) . |
| [Translate](../../aspose.psd/region/translate#translate_1)(float, float) | Versetzt die Koordinaten davon[`Region`](../region) um den angegebenen Betrag. |
| [Translate](../../aspose.psd/region/translate#translate)(int, int) | Versetzt die Koordinaten davon[`Region`](../region) um den angegebenen Betrag. |
| [Union](../../aspose.psd/region/union#union)(GraphicsPath) | aktualisiert dies[`Region`](../region) zur Vereinigung von sich selbst und dem Spezifizierten[`GraphicsPath`](../graphicspath) . |
| [Union](../../aspose.psd/region/union#union_1)(Rectangle) | aktualisiert dies[`Region`](../region) zur Vereinigung von sich selbst und dem Spezifizierten[`Rectangle`](../rectangle)Struktur. |
| [Union](../../aspose.psd/region/union#union_2)(RectangleF) | aktualisiert dies[`Region`](../region) zur Vereinigung von sich selbst und dem Spezifizierten[`RectangleF`](../rectanglef)Struktur. |
| [Union](../../aspose.psd/region/union#union_3)(Region) | aktualisiert dies[`Region`](../region) zur Vereinigung von sich selbst und dem Spezifizierten[`Region`](../region) . |
| [Xor](../../aspose.psd/region/xor#xor)(GraphicsPath) | aktualisiert dies[`Region`](../region) zur Vereinigung abzüglich der Schnittmenge von sich selbst mit der angegebenen[`GraphicsPath`](../graphicspath) . |
| [Xor](../../aspose.psd/region/xor#xor_1)(Rectangle) | aktualisiert dies[`Region`](../region) zur Vereinigung abzüglich der Schnittmenge von sich selbst mit der angegebenen[`Rectangle`](../rectangle)Struktur. |
| [Xor](../../aspose.psd/region/xor#xor_2)(RectangleF) | aktualisiert dies[`Region`](../region) zur Vereinigung abzüglich der Schnittmenge von sich selbst mit der angegebenen[`RectangleF`](../rectanglef)Struktur. |
| [Xor](../../aspose.psd/region/xor#xor_3)(Region) | aktualisiert dies[`Region`](../region) zur Vereinigung abzüglich der Schnittmenge von sich selbst mit der angegebenen[`Region`](../region) . |

### Siehe auch

* namensraum [Aspose.PSD](../../aspose.psd)
* Montage [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
