---
title: "Klasse Figure"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Figure Klasse. Die Figur. Ein Container für Formen"
type: docs
weight: 1210
url: /de/net/aspose.psd/figure/
---
{{< psd/tize >}}
## Figure class

Die Figur. Ein Container für Formen.

```csharp
public class Figure : ObjectWithBounds
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Figure](figure/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | Liest oder setzt die Grenzen des Objekts. |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob diese Figur geschlossen ist. Eine geschlossene Figur macht nur einen Unterschied, wenn die ersten und letzten Formen der Figur kontinuierliche Formen sind. In einem solchen Fall wird der erste Punkt der ersten Form durch eine gerade Linie mit dem letzten Punkt der letzten Form verbunden. |
| [Segments](../../aspose.psd/figure/segments/) { get; } | Liest die gesamten Figursegmente. |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | Liest die Formen der Figur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | Fügt der Figur eine Form hinzu. |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | Fügt der Figur einen Bereich von Formen hinzu. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | Liest die Begrenzungen des Objekts. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | Liest die Begrenzungen des Objekts. |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | Entfernt eine Form aus der Figur. |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | Entfernt einen Bereich von Formen aus der Figur. |
| [Reverse](../../aspose.psd/figure/reverse/)() | Kehrt die Reihenfolge der Formen dieser Figur sowie die Punktreihenfolge der Formen um. |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | Wendet die angegebene Transformation auf die Form an. |

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


