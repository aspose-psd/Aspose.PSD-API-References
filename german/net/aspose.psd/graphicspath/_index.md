---
title: "Klasse GraphicsPath"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.GraphicsPath-Klasse. Stellt eine Reihe zusammenhängender Linien und Kurven dar. Diese Klasse kann nicht abgeleitet werden."
type: docs
weight: 4790
url: /de/net/aspose.psd/graphicspath/
---
{{< psd/tize >}}
## GraphicsPath class

Stellt eine Reihe verbundener Linien und Kurven dar. Diese Klasse kann nicht abgeleitet werden.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | Initialisiert eine neue Instanz der `GraphicsPath`-Klasse. |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | Initialisiert eine neue Instanz der `GraphicsPath`-Klasse. |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | Initialisiert eine neue Instanz der `GraphicsPath`-Klasse. |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | Initialisiert eine neue Instanz der `GraphicsPath`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | Liest oder setzt die Grenzen des Objekts. |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | Liefert die Pfadfiguren. |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | Liefert oder setzt eine [`FillMode`](../fillmode/)-Aufzählung, die bestimmt, wie die Innenbereiche von Formen in diesem `GraphicsPath` gefüllt werden. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | Fügt eine neue Figur hinzu. |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | Fügt neue Figuren hinzu. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | Hängt den angegebenen `GraphicsPath` an diesen Pfad an. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | Hängt den angegebenen `GraphicsPath` an diesen Pfad an. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | Führt eine tiefe Kopie dieses Grafikpfads aus. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | Konvertiert jede Kurve in diesem Pfad in eine Sequenz zusammenhängender Liniensegmente. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | Wendet die angegebene Transformation an und konvertiert dann jede Kurve in diesem `GraphicsPath` in eine Sequenz zusammenhängender Liniensegmente. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | Konvertiert jede Kurve in diesem `GraphicsPath` in eine Sequenz zusammenhängender Liniensegmente. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | Liest die Begrenzungen des Objekts. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | Liest die Begrenzungen des Objekts. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `GraphicsPath` liegt, wenn er mit dem angegebenen [`Pen`](../pen/) gezeichnet wird. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `GraphicsPath` liegt, wenn er mit dem angegebenen [`Pen`](../pen/) gezeichnet wird. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `GraphicsPath` liegt, wenn er mit dem angegebenen [`Pen`](../pen/) gezeichnet wird. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `GraphicsPath` liegt, wenn er mit dem angegebenen [`Pen`](../pen/) gezeichnet wird. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `GraphicsPath` liegt, wenn er mit dem angegebenen [`Pen`](../pen/) und dem angegebenen [`Graphics`](../graphics/) gezeichnet wird. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `GraphicsPath` liegt, wenn er mit dem angegebenen [`Pen`](../pen/) und dem angegebenen [`Graphics`](../graphics/) gezeichnet wird. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `GraphicsPath` liegt, wenn er mit dem angegebenen [`Pen`](../pen/) und dem angegebenen [`Graphics`](../graphics/) gezeichnet wird. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `GraphicsPath` liegt, wenn er mit dem angegebenen [`Pen`](../pen/) und dem angegebenen [`Graphics`](../graphics/) gezeichnet wird. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | Gibt an, ob der angegebene Punkt innerhalb dieses `GraphicsPath` liegt. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | Gibt an, ob der angegebene Punkt innerhalb dieses `GraphicsPath` liegt. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | Gibt an, ob der angegebene Punkt innerhalb dieses `GraphicsPath` liegt. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | Gibt an, ob der angegebene Punkt innerhalb dieses `GraphicsPath` liegt. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | Gibt an, ob der angegebene Punkt innerhalb dieses `GraphicsPath` liegt. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | Gibt an, ob der angegebene Punkt innerhalb dieses `GraphicsPath` liegt. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | Gibt an, ob der angegebene Punkt innerhalb dieses `GraphicsPath` im sichtbaren Clip‑Bereich des angegebenen [`Graphics`](../graphics/) liegt. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | Gibt an, ob der angegebene Punkt innerhalb dieses `GraphicsPath` liegt, wobei das angegebene [`Graphics`](../graphics/) verwendet wird. |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | Entfernt eine Figur. |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | Entfernt Figuren. |
| [Reset](../../aspose.psd/graphicspath/reset/)() | Leert den Grafikpfad und setzt [`FillMode`](../fillmode/) auf Alternate. |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | Kehrt die Reihenfolge von Figuren, Formen und Punkten in jeder Form dieses `GraphicsPath` um. |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | Wendet die angegebene Transformation auf die Form an. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | Wendet eine Verzerrungstransformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen `GraphicsPath` an. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | Wendet eine Verzerrungstransformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen `GraphicsPath` an. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Wendet eine Verzerrungstransformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen `GraphicsPath` an. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Wendet eine Verzerrungstransformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen `GraphicsPath` an. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | Fügt dem Pfad eine zusätzliche Kontur hinzu. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | Fügt dem `GraphicsPath` eine zusätzliche Kontur hinzu. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | Ersetzt diesen `GraphicsPath` durch Kurven, die den Bereich umschließen, der gefüllt wird, wenn dieser Pfad mit dem angegebenen Stift gezeichnet wird. |

## Beispiele

Dieses Beispiel verwendet die Klassen GraphicsPath und Graphics, um Figuren auf einer Bildoberfläche zu erstellen und zu manipulieren. Das Beispiel erstellt ein neues Bild und zeichnet Pfade mit Hilfe der Klasse GraphicsPath. Am Ende wird die von der Klasse Graphics bereitgestellte Methode DrawPath aufgerufen, um die Pfade auf der Oberfläche zu rendern. Schließlich wird das Bild in das Tiff-Dateiformat exportiert.

```csharp
[C#]

//Erstelle eine Instanz von Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Erstelle und initialisiere eine Instanz der Klasse Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Leere die Graphics-Oberfläche
    graphics.Clear(Color.Wheat);

    //Erstelle eine Instanz der Klasse GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Erstelle eine Instanz der Klasse Figure
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Füge Formen zum Figure-Objekt hinzu
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Füge das Figure-Objekt zu GraphicsPath hinzu
    graphicspath.AddFigure(figure);

    //Zeichne Pfad mit Pen-Objekt in der Farbe Schwarz
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Erstellen Sie eine Instanz von TiffOptions und setzen Sie deren verschiedene Eigenschaften
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // Speichere alle Änderungen.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Siehe auch

* class [ObjectWithBounds](../objectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


