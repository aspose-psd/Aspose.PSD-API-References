---
title: Class PolygonShape
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Shapes.PolygonShape klass. Representerar en polygonform.
type: docs
weight: 5510
url: /sv/net/aspose.psd.shapes/polygonshape/
---
## PolygonShape class

Representerar en polygonform.

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PolygonShape](polygonshape/#constructor)() | Initierar en ny instans av`PolygonShape` class. |
| [PolygonShape](polygonshape/#constructor_1)(PointF[]) | Initierar en ny instans av`PolygonShape` class. |
| [PolygonShape](polygonshape/#constructor_2)(PointF[], bool) | Initierar en ny instans av`PolygonShape` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/polygonshape/bounds/) { get; } | Hämtar objektets gränser. |
| override [Center](../../aspose.psd.shapes/polygonshape/center/) { get; } | Hämtar formens centrum. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Får slutformpunkten. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Får ett värde som indikerar om formen har segment. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Hämtar eller ställer in ett värde som anger om formen är stängd. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Hämtar eller ställer in kurvpunkterna. |
| override [Segments](../../aspose.psd.shapes/polygonshape/segments/) { get; } | Hämtar formsegmenten. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Får startpunkten för formen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds)(Matrix) | Hämtar objektets gränser. |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds_1)(Matrix, Pen) | Hämtar objektets gränser. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Vänder om ordningen på punkterna för denna form. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Tillämpar den angivna transformationen på formen. |

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

* class [Shape](../../aspose.psd/shape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* namnutrymme [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* hopsättning [Aspose.PSD](../../)


