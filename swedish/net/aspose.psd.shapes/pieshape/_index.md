---
title: Class PieShape
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Shapes.PieShape klass. Representerar en pajform.
type: docs
weight: 5500
url: /sv/net/aspose.psd.shapes/pieshape/
---
## PieShape class

Representerar en pajform.

```csharp
public class PieShape : EllipseShape
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PieShape](pieshape/#constructor)() | Initierar en ny instans av`PieShape` class. |
| [PieShape](pieshape/#constructor_1)(RectangleF, float, float) | Initierar en ny instans av`PieShape` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | Hämtar objektets gränser. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | Hämtar formens centrum. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | Får ett värde som indikerar om formen har segment. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | Får den nedre vänstra rektangelpunkten. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | Får den vänstra övre rektangelpunkten. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | Hämtar rektangelhöjden. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | Hämtar rektangelbredden. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | Får den högra nedre rektangelpunkten. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | Får den högra övre rektangelpunkten. |
| override [Segments](../../aspose.psd.shapes/pieshape/segments/) { get; } | Hämtar formsegmenten. |
| [StartAngle](../../aspose.psd.shapes/pieshape/startangle/) { get; set; } | Hämtar eller ställer in startvinkeln. |
| [SweepAngle](../../aspose.psd.shapes/pieshape/sweepangle/) { get; set; } | Hämtar eller ställer in svepvinkeln. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix) | Hämtar objektets gränser. |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | Hämtar objektets gränser. |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | Tillämpar den angivna transformationen på formen. |

### Exempel

Det här exemplet skapar en ny bild och ritar en mängd olika former med hjälp av Figurer och GraphicsPath på bildytan

```csharp
[C#]

//Skapa en instans av bild
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Skapa och initiera en instans av klassen Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Rensa grafikytan
    graphics.Clear(Color.Wheat);

    //Skapa en instans av klassen GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Skapa en instans av figurklassen
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //Lägg till form till figurobjekt
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Skapa en instans av figurklassen
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //Lägg till form till figurobjekt
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //Lägg till figurobjekt till GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //Rita bana med pennobjekt av färg svart
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // Skapa exportalternativ och initiera dem.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // spara alla ändringar.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### Se även

* class [EllipseShape](../ellipseshape/)
* namnutrymme [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* hopsättning [Aspose.PSD](../../)


