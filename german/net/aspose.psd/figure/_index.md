---
title: Class Figure
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.Figure klas. Die Figur. Ein Behälter für Formen.
type: docs
weight: 1200
url: /de/net/aspose.psd/figure/
---
## Figure class

Die Figur. Ein Behälter für Formen.

```csharp
public class Figure : ObjectWithBounds
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Figure](figure/)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | Ruft die Grenzen des Objekts ab oder legt sie fest. |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob diese Figur geschlossen ist. Eine geschlossene Figur macht nur dann einen Unterschied, wenn die Formen der ersten und der letzten Figur fortlaufende Formen sind. In diesem Fall wird der erste Punkt der ersten Form durch eine gerade Linie mit dem letzten Punkt der letzten Form verbunden |
| [Segments](../../aspose.psd/figure/segments/) { get; } | Ruft die ganzen Figursegmente ab. |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | Ruft die Figurenformen ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | Fügt der Figur eine Form hinzu. |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | Fügt der Figur eine Reihe von Formen hinzu. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | Ruft die Grenzen des Objekts ab. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | Ruft die Grenzen des Objekts ab. |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | Entfernt eine Form aus der Figur. |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | Entfernt eine Reihe von Formen aus der Figur. |
| [Reverse](../../aspose.psd/figure/reverse/)() | Kehrt die Reihenfolge dieser Figurformen und die Punktreihenfolge um. |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | Wendet die angegebene Transformation auf die Form an. |

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

* class [ObjectWithBounds](../objectwithbounds/)
* namensraum [Aspose.PSD](../../aspose.psd/)
* Montage [Aspose.PSD](../../)


