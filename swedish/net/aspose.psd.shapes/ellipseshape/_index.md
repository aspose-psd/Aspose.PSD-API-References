---
title: "Klass EllipseShape"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Shapes.EllipseShape-klass. Representerar en ellipsform"
type: docs
weight: 5990
url: /sv/net/aspose.psd.shapes/ellipseshape/
---
{{< psd/tize >}}
## EllipseShape class

Representerar en ellipsform.

```csharp
public class EllipseShape : RectangleShape
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [EllipseShape](ellipseshape/#constructor)() | Initierar en ny instans av `EllipseShape`-klassen. |
| [EllipseShape](ellipseshape/#constructor_1)(RectangleF) | Initierar en ny instans av `EllipseShape`-klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | Hämtar objektets gränser. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | Hämtar formens centrum. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | Hämtar ett värde som indikerar om formen har segment. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | Hämtar den vänstra nedre rektangelpunkten. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | Hämtar den vänstra övre rektangelpunkten. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | Hämtar rektangelns höjd. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | Hämtar rektangelns bredd. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | Hämtar den högra nedre rektangelpunkten. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | Hämtar den högra övre rektangelpunkten. |
| override [Segments](../../aspose.psd.shapes/ellipseshape/segments/) { get; } | Hämtar formens segment. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix) | Hämtar objektets gränser. |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | Hämtar objektets gränser. |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | Tillämpar den angivna transformationen på formen. |

## Exempel

Detta exempel skapar en ny Image och ritar en mängd olika former med hjälp av Figures och GraphicsPath på Image-ytan.

```csharp
[C#]

//Skapa en instans av Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Skapa och initiera en instans av Graphics-klassen
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Rensa Graphics-ytan
    graphics.Clear(Color.Wheat);

    //Skapa en instans av GraphicsPath-klassen
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Skapa en instans av Figure-klassen
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //Lägg till form till Figure-objektet
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Skapa en instans av Figure-klassen
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //Lägg till form till Figure-objektet
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //Lägg till Figure-objektet till GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //Rita bana med Pen-objektet i färgen svart
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // Skapa exportalternativ och initiera dem.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // spara alla ändringar.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### Se även

* class [RectangleShape](../rectangleshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


