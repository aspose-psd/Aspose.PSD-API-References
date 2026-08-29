---
title: "Klasse EllipseShape"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Shapes.EllipseShape Klasse. Stellt eine Ellipsenform dar."
type: docs
weight: 5990
url: /de/net/aspose.psd.shapes/ellipseshape/
---
{{< psd/tize >}}
## EllipseShape class

Stellt eine Ellipsenform dar.

```csharp
public class EllipseShape : RectangleShape
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [EllipseShape](ellipseshape/#constructor)() | Initialisiert eine neue Instanz der `EllipseShape` Klasse. |
| [EllipseShape](ellipseshape/#constructor_1)(RectangleF) | Initialisiert eine neue Instanz der `EllipseShape` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | Liest die Begrenzungen des Objekts. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | Liest das Zentrum der Form. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | Liest einen Wert, der angibt, ob die Form Segmente hat. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | Liest den linken unteren Rechteckpunkt. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | Liest den linken oberen Rechteckpunkt. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | Liest die Rechteckhöhe. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | Liest die Rechteckbreite. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | Liest den rechten unteren Rechteckpunkt. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | Liest den rechten oberen Rechteckpunkt. |
| override [Segments](../../aspose.psd.shapes/ellipseshape/segments/) { get; } | Liest die Segmente der Form. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix) | Liest die Begrenzungen des Objekts. |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | Liest die Begrenzungen des Objekts. |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | Wendet die angegebene Transformation auf die Form an. |

## Beispiele

Dieses Beispiel erstellt ein neues Image und zeichnet eine Vielzahl von Formen mithilfe von Figures und GraphicsPath auf der Image-Oberfläche.

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
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //Form zum Figure-Objekt hinzufügen
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Erstelle eine Instanz der Klasse Figure
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //Form zum Figure-Objekt hinzufügen
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //Füge das Figure-Objekt zu GraphicsPath hinzu
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //Zeichne Pfad mit Pen-Objekt in der Farbe Schwarz
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // Erstelle Exportoptionen und initialisiere sie.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // Speichere alle Änderungen.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### Siehe auch

* class [RectangleShape](../rectangleshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


