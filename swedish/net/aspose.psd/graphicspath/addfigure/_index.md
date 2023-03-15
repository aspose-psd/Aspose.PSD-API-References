---
title: GraphicsPath.AddFigure
second_title: Aspose.PSD för .NET API-referens
description: GraphicsPath metod. Lägger till en ny figur.
type: docs
weight: 50
url: /sv/net/aspose.psd/graphicspath/addfigure/
---
## GraphicsPath.AddFigure method

Lägger till en ny figur.

```csharp
public void AddFigure(Figure figure)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| figure | Figure | Siffran att lägga till. |

### Exempel

det här exemplet används GraphicsPath och Graphics-klassen för att skapa och manipulera figurer på en bildyta. Exempel skapar en ny bild och ritar banor med hjälp av klassen GraphicsPath. I slutet anropas DrawPath-metoden som exponeras av Graphics-klassen för att rendera banorna på ytan. Slutligen exporteras bilden till Tiff-filformat.

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
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Lägg till former till figurobjekt
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Lägg till figurobjekt till GraphicsPath
    graphicspath.AddFigure(figure);

    //Rita bana med pennobjekt av färg svart
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Skapa en instans av TiffOptions och ställ in dess olika egenskaper
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // spara alla ändringar.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Se även

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* namnutrymme [Aspose.PSD](../../graphicspath/)
* hopsättning [Aspose.PSD](../../../)


