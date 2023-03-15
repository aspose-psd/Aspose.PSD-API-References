---
title: Class Figure
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Figure klass. Figuren. En behållare för former.
type: docs
weight: 1200
url: /sv/net/aspose.psd/figure/
---
## Figure class

Figuren. En behållare för former.

```csharp
public class Figure : ObjectWithBounds
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Figure](figure/)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | Hämtar eller ställer in objektets gränser. |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om denna siffra är stängd. En stängd figur kommer bara att göra skillnad om den första och den sista figurens former är kontinuerliga former. I sådana fall kommer den första punkten i den första formen att vara förbunden med en rät linje från den sista punkten i den sista formen. |
| [Segments](../../aspose.psd/figure/segments/) { get; } | Hämtar hela figursegmenten. |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | Får figurformerna. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | Lägger till en form till figuren. |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | Lägger till ett antal former till figuren. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | Hämtar objektets gränser. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | Hämtar objektets gränser. |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | Tar bort en form från figuren. |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | Tar bort ett antal former från figuren. |
| [Reverse](../../aspose.psd/figure/reverse/)() | Vänder om den här figurens ordningsföljd och formernas punktordning. |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | Tillämpar den angivna transformationen på formen. |

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

* class [ObjectWithBounds](../objectwithbounds/)
* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


