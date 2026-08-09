---
title: "Klasse PolygonShape"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Shapes.PolygonShape Klasse. Stellt eine Polygonform dar."
type: docs
weight: 6010
url: /de/net/aspose.psd.shapes/polygonshape/
---
{{< psd/tize >}}
## PolygonShape class

Stellt eine Polygonform dar.

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PolygonShape](polygonshape/#constructor)() | Initialisiert eine neue Instanz der `PolygonShape` Klasse. |
| [PolygonShape](polygonshape/#constructor_1)(PointF[]) | Initialisiert eine neue Instanz der `PolygonShape` Klasse. |
| [PolygonShape](polygonshape/#constructor_2)(PointF[], bool) | Initialisiert eine neue Instanz der `PolygonShape` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/polygonshape/bounds/) { get; } | Liest die Begrenzungen des Objekts. |
| override [Center](../../aspose.psd.shapes/polygonshape/center/) { get; } | Liest das Zentrum der Form. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Liest den Endpunkt der Form. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Liest einen Wert, der angibt, ob die Form Segmente hat. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Ruft den Wert ab oder legt ihn fest, der angibt, ob die Form geschlossen ist. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Ruft die Kurvenpunkte ab oder legt sie fest. |
| override [Segments](../../aspose.psd.shapes/polygonshape/segments/) { get; } | Liest die Segmente der Form. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Ruft den Startpunkt der Form ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds)(Matrix) | Liest die Begrenzungen des Objekts. |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds_1)(Matrix, Pen) | Liest die Begrenzungen des Objekts. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Kehrt die Reihenfolge der Punkte für diese Form um. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Wendet die angegebene Transformation auf die Form an. |

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

* class [Shape](../../aspose.psd/shape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


