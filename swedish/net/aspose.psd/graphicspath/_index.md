---
title: "Klass GraphicsPath"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.GraphicsPath-klass. Representerar en serie av sammanlänkade linjer och kurvor. Denna klass kan inte ärvas."
type: docs
weight: 4790
url: /sv/net/aspose.psd/graphicspath/
---
{{< psd/tize >}}
## GraphicsPath class

Representerar en serie av sammanhängande linjer och kurvor. Denna klass kan inte ärvas.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | Initierar en ny instans av klassen `GraphicsPath`. |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | Initierar en ny instans av klassen `GraphicsPath`. |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | Initierar en ny instans av klassen `GraphicsPath`. |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | Initierar en ny instans av klassen `GraphicsPath`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | Hämtar eller anger objektets gränser. |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | Hämtar sökvägsfigurerna. |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | Hämtar eller anger en [`FillMode`](../fillmode/)‑enumeration som bestämmer hur insidan av former i denna `GraphicsPath` fylls. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | Lägger till en ny figur. |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | Lägger till nya figurer. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | Lägger till den angivna `GraphicsPath` till denna sökväg. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | Lägger till den angivna `GraphicsPath` till denna sökväg. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | Utför en djup kloning av denna grafikväg. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | Konverterar varje kurva i denna sökväg till en sekvens av sammanlänkade linjesegment. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | Tillämpar den angivna transformen och konverterar sedan varje kurva i denna `GraphicsPath` till en sekvens av sammanlänkade linjesegment. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | Konverterar varje kurva i denna `GraphicsPath` till en sekvens av sammanlänkade linjesegment. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | Hämtar objektets gränser. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | Hämtar objektets gränser. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | Indikerar om den angivna punkten ligger inom (under) konturen av denna `GraphicsPath` när den ritas med den angivna [`Pen`](../pen/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | Indikerar om den angivna punkten ligger inom (under) konturen av denna `GraphicsPath` när den ritas med den angivna [`Pen`](../pen/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | Indikerar om den angivna punkten ligger inom (under) konturen av denna `GraphicsPath` när den ritas med den angivna [`Pen`](../pen/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | Indikerar om den angivna punkten ligger inom (under) konturen av denna `GraphicsPath` när den ritas med den angivna [`Pen`](../pen/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | Indikerar om den angivna punkten ligger inom (under) konturen av denna `GraphicsPath` när den ritas med den angivna [`Pen`](../pen/) och med den angivna [`Graphics`](../graphics/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | Indikerar om den angivna punkten ligger inom (under) konturen av denna `GraphicsPath` när den ritas med den angivna [`Pen`](../pen/) och med den angivna [`Graphics`](../graphics/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | Indikerar om den angivna punkten ligger inom (under) konturen av denna `GraphicsPath` när den ritas med den angivna [`Pen`](../pen/) och med den angivna [`Graphics`](../graphics/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | Indikerar om den angivna punkten ligger inom (under) konturen av denna `GraphicsPath` när den ritas med den angivna [`Pen`](../pen/) och med den angivna [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | Indikerar om den angivna punkten ligger inom denna `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | Indikerar om den angivna punkten ligger inom denna `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | Indikerar om den angivna punkten ligger inom denna `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | Indikerar om den angivna punkten ligger inom denna `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | Indikerar om den angivna punkten ligger inom denna `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | Indikerar om den angivna punkten ligger inom denna `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | Indikerar om den angivna punkten ligger inom denna `GraphicsPath` i den synliga klippningsregionen för den angivna [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | Indikerar om den angivna punkten ligger inom denna `GraphicsPath`, med den angivna [`Graphics`](../graphics/). |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | Tar bort en figur. |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | Tar bort figurer. |
| [Reset](../../aspose.psd/graphicspath/reset/)() | Tömmer grafikvägen och sätter [`FillMode`](../fillmode/) till Alternate. |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | Vänder ordningen på figurer, former och punkter i varje form av denna `GraphicsPath`. |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | Tillämpar den angivna transformationen på formen. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på detta `GraphicsPath`. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på detta `GraphicsPath`. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på detta `GraphicsPath`. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på detta `GraphicsPath`. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | Lägger till en extra kontur till sökvägen. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | Lägger till en extra kontur till `GraphicsPath`. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | Ersätter detta `GraphicsPath` med kurvor som omsluter området som fylls när denna sökväg ritas med den angivna pennan. |

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


