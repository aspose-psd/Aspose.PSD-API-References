---
title: "Klass PolygonShape"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Shapes.PolygonShape klass. Representerar en polygonform"
type: docs
weight: 6010
url: /sv/net/aspose.psd.shapes/polygonshape/
---
{{< psd/tize >}}
## PolygonShape class

Representerar en polygonform.

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PolygonShape](polygonshape/#constructor)() | Initierar en ny instans av klassen `PolygonShape`. |
| [PolygonShape](polygonshape/#constructor_1)(PointF[]) | Initierar en ny instans av klassen `PolygonShape`. |
| [PolygonShape](polygonshape/#constructor_2)(PointF[], bool) | Initierar en ny instans av klassen `PolygonShape`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/polygonshape/bounds/) { get; } | Hämtar objektets gränser. |
| override [Center](../../aspose.psd.shapes/polygonshape/center/) { get; } | Hämtar formens centrum. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Hämtar den avslutande formpunkten. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Hämtar ett värde som indikerar om formen har segment. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Hämtar eller anger ett värde som indikerar om formen är sluten. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Hämtar eller anger kurvpunkterna. |
| override [Segments](../../aspose.psd.shapes/polygonshape/segments/) { get; } | Hämtar formens segment. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Hämtar den startande formpunkten. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds)(Matrix) | Hämtar objektets gränser. |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds_1)(Matrix, Pen) | Hämtar objektets gränser. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Vänder ordningen på punkterna för denna form. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Tillämpar den angivna transformationen på formen. |

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

* class [Shape](../../aspose.psd/shape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


