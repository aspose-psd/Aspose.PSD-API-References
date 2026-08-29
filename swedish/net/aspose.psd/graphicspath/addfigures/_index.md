---
title: "GraphicsPath.AddFigures"
second_title: "Aspose.PSD för .NET API‑referens"
description: "GraphicsPath-metod. Lägger till nya figurer"
type: docs
weight: 60
url: /sv/net/aspose.psd/graphicspath/addfigures/
---
{{< psd/tize >}}
## GraphicsPath.AddFigures method

Lägger till nya figurer.

```csharp
public void AddFigures(Figure[] figures)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| figurer | Figure[] | Figurerna att lägga till. |

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

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


