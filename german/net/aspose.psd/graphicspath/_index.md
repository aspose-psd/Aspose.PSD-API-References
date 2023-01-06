---
title: GraphicsPath
second_title: Aspose.PSD für .NET-API-Referenz
description: Repräsentiert eine Reihe verbundener Linien und Kurven. Diese Klasse kann nicht vererbt werden.
type: docs
weight: 4250
url: /de/net/aspose.psd/graphicspath/
---
## GraphicsPath class

Repräsentiert eine Reihe verbundener Linien und Kurven. Diese Klasse kann nicht vererbt werden.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [GraphicsPath](graphicspath#constructor)() | Initialisiert eine neue Instanz von[`GraphicsPath`](../graphicspath) Klasse. |
| [GraphicsPath](graphicspath#constructor_1)(Figure[]) | Initialisiert eine neue Instanz von[`GraphicsPath`](../graphicspath) Klasse. |
| [GraphicsPath](graphicspath#constructor_3)(FillMode) | Initialisiert eine neue Instanz von[`GraphicsPath`](../graphicspath) Klasse. |
| [GraphicsPath](graphicspath#constructor_2)(Figure[], FillMode) | Initialisiert eine neue Instanz von[`GraphicsPath`](../graphicspath) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds) { get; } | Ruft die Grenzen des Objekts ab oder legt sie fest. |
| [Figures](../../aspose.psd/graphicspath/figures) { get; } | Ruft die Wegzahlen ab. |
| [FillMode](../../aspose.psd/graphicspath/fillmode) { get; set; } | Holt oder setzt a[`FillMode`](../fillmode) Aufzählung, die bestimmt, wie die Innenräume der Formen in diesem[`GraphicsPath`](../graphicspath) sind gefüllt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure)(Figure) | Fügt eine neue Figur hinzu. |
| [AddFigures](../../aspose.psd/graphicspath/addfigures)(Figure[]) | Fügt neue Zahlen hinzu. |
| [AddPath](../../aspose.psd/graphicspath/addpath#addpath)(GraphicsPath) | Fügt die angegebene an[`GraphicsPath`](../graphicspath) zu diesem Pfad. |
| [AddPath](../../aspose.psd/graphicspath/addpath#addpath_1)(GraphicsPath, bool) | Fügt die angegebene an[`GraphicsPath`](../graphicspath) zu diesem Pfad. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone)() | Führt einen tiefen Klon dieses Grafikpfads durch. |
| [Flatten](../../aspose.psd/graphicspath/flatten#flatten)() | Konvertiert jede Kurve in diesem Pfad in eine Folge verbundener Liniensegmente. |
| [Flatten](../../aspose.psd/graphicspath/flatten#flatten_1)(Matrix) | Wendet die angegebene Transformation an und wandelt dann jede Kurve in diese um[`GraphicsPath`](../graphicspath) in eine Folge verbundener Liniensegmente. |
| [Flatten](../../aspose.psd/graphicspath/flatten#flatten_2)(Matrix, float) | Wandelt jede Kurve in diese um[`GraphicsPath`](../graphicspath) in eine Folge verbundener Liniensegmente. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds#getbounds)(Matrix) | Ruft die Grenzen des Objekts ab. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds#getbounds_1)(Matrix, Pen) | Ruft die Grenzen des Objekts ab. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible)(Point, Pen) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Umrisslinie davon enthalten ist[`GraphicsPath`](../graphicspath) wenn mit den angegebenen gezeichnet[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible_2)(PointF, Pen) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Umrisslinie davon enthalten ist[`GraphicsPath`](../graphicspath) wenn mit den angegebenen gezeichnet[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible_6)(float, float, Pen) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Umrisslinie davon enthalten ist[`GraphicsPath`](../graphicspath) wenn mit den angegebenen gezeichnet[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible_4)(int, int, Pen) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Umrisslinie davon enthalten ist[`GraphicsPath`](../graphicspath) wenn mit den angegebenen gezeichnet[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible_1)(Point, Pen, Graphics) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Umrisslinie davon enthalten ist[`GraphicsPath`](../graphicspath) wenn mit den angegebenen gezeichnet[`Pen`](../pen) und unter Verwendung der angegebenen[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible_3)(PointF, Pen, Graphics) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Umrisslinie davon enthalten ist[`GraphicsPath`](../graphicspath) wenn mit den angegebenen gezeichnet[`Pen`](../pen) und unter Verwendung der angegebenen[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible_7)(float, float, Pen, Graphics) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Umrisslinie davon enthalten ist[`GraphicsPath`](../graphicspath) wenn mit den angegebenen gezeichnet[`Pen`](../pen) und unter Verwendung der angegebenen[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible_5)(int, int, Pen, Graphics) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Umrisslinie davon enthalten ist[`GraphicsPath`](../graphicspath) wenn mit den angegebenen gezeichnet[`Pen`](../pen) und unter Verwendung der angegebenen[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible)(Point) | Gibt an, ob der angegebene Punkt darin enthalten ist[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible_2)(PointF) | Gibt an, ob der angegebene Punkt darin enthalten ist[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible_6)(float, float) | Gibt an, ob der angegebene Punkt darin enthalten ist[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible_4)(int, int) | Gibt an, ob der angegebene Punkt darin enthalten ist[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible_1)(Point, Graphics) | Gibt an, ob der angegebene Punkt darin enthalten ist[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible_3)(PointF, Graphics) | Gibt an, ob der angegebene Punkt darin enthalten ist[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible_7)(float, float, Graphics) | Gibt an, ob der angegebene Punkt darin enthalten ist[`GraphicsPath`](../graphicspath) im sichtbaren Clip-Bereich des angegebenen[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible_5)(int, int, Graphics) | Gibt an, ob der angegebene Punkt darin enthalten ist[`GraphicsPath`](../graphicspath) , unter Verwendung der angegebenen[`Graphics`](../graphics) . |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure)(Figure) | Entfernt eine Figur. |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures)(Figure[]) | Entfernt Zahlen. |
| [Reset](../../aspose.psd/graphicspath/reset)() | Leert den Grafikpfad und setzt die[`FillMode`](../fillmode) zuAlternate . |
| [Reverse](../../aspose.psd/graphicspath/reverse)() | Kehrt die Reihenfolge der Figuren, Formen und Punkte in jeder Form davon um[`GraphicsPath`](../graphicspath) . |
| override [Transform](../../aspose.psd/graphicspath/transform)(Matrix) | Wendet die angegebene Transformation auf die Form an. |
| [Warp](../../aspose.psd/graphicspath/warp#warp)(PointF[], RectangleF) | Wendet eine durch ein Rechteck und ein Parallelogramm definierte Warp-Transformation darauf an[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.psd/graphicspath/warp#warp_1)(PointF[], RectangleF, Matrix) | Wendet eine durch ein Rechteck und ein Parallelogramm definierte Warp-Transformation darauf an[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.psd/graphicspath/warp#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Wendet eine durch ein Rechteck und ein Parallelogramm definierte Warp-Transformation darauf an[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.psd/graphicspath/warp#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Wendet eine durch ein Rechteck und ein Parallelogramm definierte Warp-Transformation darauf an[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.psd/graphicspath/widen#widen)(Pen) | Fügt dem Pfad eine zusätzliche Kontur hinzu. |
| [Widen](../../aspose.psd/graphicspath/widen#widen_1)(Pen, Matrix) | Fügt einen zusätzlichen Umriss hinzu[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.psd/graphicspath/widen#widen_2)(Pen, Matrix, float) | Ersetzt dies[`GraphicsPath`](../graphicspath) mit Kurven, die den Bereich umschließen, der gefüllt wird, wenn dieser Pfad mit dem angegebenen Stift gezeichnet wird. |

### Beispiele

Dieses Beispiel verwendet GraphicsPath und die Graphics-Klasse, um Figuren auf einer Bildoberfläche zu erstellen und zu manipulieren. Beispiel erstellt ein neues Bild und zeichnet Pfade mit Hilfe der GraphicsPath-Klasse. Am Ende wird die DrawPath-Methode aufgerufen, die von der Graphics-Klasse bereitgestellt wird, um die Pfade auf der Oberfläche zu rendern. Schließlich wird das Bild in das Tiff-Dateiformat exportiert.

```csharp
[C#]

//Eine Instanz von Image erstellen 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Eine Instanz der Graphics-Klasse erstellen und initialisieren
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Grafikoberfläche löschen
    graphics.Clear(Color.Wheat);

    //Eine Instanz der GraphicsPath-Klasse erstellen
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Eine Instanz der Figure-Klasse erstellen
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Formen zum Figurobjekt hinzufügen
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Figure-Objekt zu GraphicsPath hinzufügen
    graphicspath.AddFigure(figure);

    // Pfad mit Stiftobjekt der Farbe Schwarz zeichnen
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Eine Instanz von TiffOptions erstellen und ihre verschiedenen Eigenschaften festlegen
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // Alle Änderungen speichern.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Siehe auch

* class [ObjectWithBounds](../objectwithbounds)
* namensraum [Aspose.PSD](../../aspose.psd)
* Montage [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
