---
title: "Figure.AddShape"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Figure-metod. Lägger till en form i figuren"
type: docs
weight: 60
url: /sv/net/aspose.psd/figure/addshape/
---
{{< psd/tize >}}
## Figure.AddShape method

Lägger till en form i figuren.

```csharp
public void AddShape(Shape shape)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| form | Form | Formen att lägga till. |

## Exempel

Detta exempel använder GraphicsPath- och Graphics-klassen för att skapa och manipulera figurer på en bildyta. Exemplet skapar en ny bild och ritar banor med hjälp av GraphicsPath-klassen. I slutet anropas DrawPath‑metoden som exponeras av Graphics-klassen för att rendera banorna på ytan. Slutligen exporteras bilden till Tiff‑filformat.

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
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Lägg till former till Figure-objektet
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Lägg till Figure-objektet till GraphicsPath
    graphicspath.AddFigure(figure);

    //Rita bana med Pen-objektet i färgen svart
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Skapa en instans av TiffOptions och ange dess olika egenskaper
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // spara alla ändringar.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Se även

* class [Shape](../../shape/)
* class [Figure](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


