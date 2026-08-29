---
title: "Klass Figure"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Figure klass. Figuren. En behållare för former"
type: docs
weight: 1210
url: /sv/net/aspose.psd/figure/
---
{{< psd/tize >}}
## Figure class

Figuren. En behållare för former.

```csharp
public class Figure : ObjectWithBounds
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Figure](figure/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | Hämtar eller anger objektets gränser. |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | Hämtar eller anger ett värde som indikerar om denna figur är sluten. En sluten figur gör bara skillnad i fall där den första och den sista figurens former är kontinuerliga former. I sådant fall kommer den första punkten i den första formen att kopplas ihop med en rak linje från den sista punkten i den sista formen. |
| [Segments](../../aspose.psd/figure/segments/) { get; } | Hämtar hela figursegmenten. |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | Hämtar figurens former. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | Lägger till en form i figuren. |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | Lägger till ett intervall av former i figuren. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | Hämtar objektets gränser. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | Hämtar objektets gränser. |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | Tar bort en form från figuren. |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | Tar bort ett intervall av former från figuren. |
| [Reverse](../../aspose.psd/figure/reverse/)() | Vänder på figurens formordning och formernas punktordning. |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | Tillämpar den angivna transformationen på formen. |

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

* class [ObjectWithBounds](../objectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


