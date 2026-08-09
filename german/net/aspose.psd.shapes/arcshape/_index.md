---
title: "Klasse ArcShape"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Shapes.ArcShape Klasse. Stellt eine Bogenform dar"
type: docs
weight: 5960
url: /de/net/aspose.psd.shapes/arcshape/
---
{{< psd/tize >}}
## ArcShape class

Stellt eine Bogenform dar.

```csharp
public sealed class ArcShape : PieShape, IOrderedShape
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ArcShape](arcshape/#constructor)() | Initialisiert eine neue Instanz der `ArcShape` Klasse. |
| [ArcShape](arcshape/#constructor_1)(RectangleF, float, float) | Initialisiert eine neue Instanz der `ArcShape` Klasse. |
| [ArcShape](arcshape/#constructor_2)(RectangleF, float, float, bool) | Initialisiert eine neue Instanz der `ArcShape` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | Liest die Begrenzungen des Objekts. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | Liest das Zentrum der Form. |
| [EndPoint](../../aspose.psd.shapes/arcshape/endpoint/) { get; } | Liest den Endpunkt der Form. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | Liest einen Wert, der angibt, ob die Form Segmente hat. |
| [IsClosed](../../aspose.psd.shapes/arcshape/isclosed/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die geordnete Form geschlossen ist. Beim Verarbeiten einer geschlossenen geordneten Form haben die Start- und Endpunkte keine Bedeutung. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | Liest den linken unteren Rechteckpunkt. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | Liest den linken oberen Rechteckpunkt. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | Liest die Rechteckhöhe. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | Liest die Rechteckbreite. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | Liest den rechten unteren Rechteckpunkt. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | Liest den rechten oberen Rechteckpunkt. |
| override [Segments](../../aspose.psd.shapes/arcshape/segments/) { get; } | Liest die Segmente der Form. |
| [StartAngle](../../aspose.psd.shapes/pieshape/startangle/) { get; set; } | Ruft den Startwinkel ab oder legt ihn fest. |
| [StartPoint](../../aspose.psd.shapes/arcshape/startpoint/) { get; } | Ruft den Startpunkt der Form ab. |
| [SweepAngle](../../aspose.psd.shapes/pieshape/sweepangle/) { get; set; } | Ruft den Sweep-Winkel ab oder legt ihn fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/arcshape/getbounds/#getbounds)(Matrix) | Liest die Begrenzungen des Objekts. |
| override [GetBounds](../../aspose.psd.shapes/arcshape/getbounds/#getbounds_1)(Matrix, Pen) | Liest die Begrenzungen des Objekts. |
| [Reverse](../../aspose.psd.shapes/arcshape/reverse/)() | Kehrt die Reihenfolge der Punkte für diese Form um. |
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

* class [PieShape](../pieshape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


