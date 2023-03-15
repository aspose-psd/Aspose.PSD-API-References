---
title: Class GraphicsPath
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.GraphicsPath klass. Representerar en serie sammankopplade linjer och kurvor. Denna klass kan inte ärvas.
type: docs
weight: 4320
url: /sv/net/aspose.psd/graphicspath/
---
## GraphicsPath class

Representerar en serie sammankopplade linjer och kurvor. Denna klass kan inte ärvas.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | Initierar en ny instans av`GraphicsPath` class. |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | Initierar en ny instans av`GraphicsPath` class. |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | Initierar en ny instans av`GraphicsPath` class. |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | Initierar en ny instans av`GraphicsPath` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | Hämtar eller ställer in objektets gränser. |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | Hämtar sökvägssiffrorna. |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | Hämtar eller sätter en[`FillMode`](../fillmode/) uppräkning som avgör hur interiören av former i detta`GraphicsPath` är fyllda. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | Lägger till en ny figur. |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | Lägger till nya figurer. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | Lägger till det angivna`GraphicsPath` till denna väg. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | Lägger till det angivna`GraphicsPath` till denna väg. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | Utför en djup klon av denna grafikbana. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | Konverterar varje kurva i denna väg till en sekvens av anslutna linjesegment. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | Tillämpar den angivna transformationen och konverterar sedan varje kurva i denna`GraphicsPath` i en sekvens av anslutna linjesegment. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | Konverterar varje kurva i denna`GraphicsPath` i en sekvens av anslutna linjesegment. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | Hämtar objektets gränser. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | Hämtar objektets gränser. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | Indikerar om den angivna punkten finns inom (under) konturen av denna`GraphicsPath` när det dras med det angivna[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | Indikerar om den angivna punkten finns inom (under) konturen av denna`GraphicsPath` när det dras med det angivna[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | Indikerar om den angivna punkten finns inom (under) konturen av denna`GraphicsPath` när det dras med det angivna[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | Indikerar om den angivna punkten finns inom (under) konturen av denna`GraphicsPath` när det dras med det angivna[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | Indikerar om den angivna punkten finns inom (under) konturen av denna`GraphicsPath` när det dras med det angivna[`Pen`](../pen/) och använda den angivna[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | Indikerar om den angivna punkten finns inom (under) konturen av denna`GraphicsPath` när det dras med det angivna[`Pen`](../pen/) och använda den angivna[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | Indikerar om den angivna punkten finns inom (under) konturen av denna`GraphicsPath` när det dras med det angivna[`Pen`](../pen/) och använda den angivna[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | Indikerar om den angivna punkten finns inom (under) konturen av denna`GraphicsPath` när det dras med det angivna[`Pen`](../pen/) och använda den angivna[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | Indikerar om den angivna punkten finns i denna`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | Indikerar om den angivna punkten finns i denna`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | Indikerar om den angivna punkten finns i denna`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | Indikerar om den angivna punkten finns i denna`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | Indikerar om den angivna punkten finns i denna`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | Indikerar om den angivna punkten finns i denna`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | Indikerar om den angivna punkten finns i denna`GraphicsPath` i det synliga klippområdet för den angivna[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | Indikerar om den angivna punkten finns i denna`GraphicsPath` , med den angivna[`Graphics`](../graphics/) . |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | Tar bort en figur. |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | Tar bort figurer. |
| [Reset](../../aspose.psd/graphicspath/reset/)() | Tömmer grafikbanan och ställer in[`FillMode`](../fillmode/) tillAlternate . |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | Vänder om ordningen på figurer, former och punkter i varje form av detta`GraphicsPath` . |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | Tillämpar den angivna transformationen på formen. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | Tillämpar en varptransform, definierad av en rektangel och ett parallellogram, på detta`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | Tillämpar en varptransform, definierad av en rektangel och ett parallellogram, på detta`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Tillämpar en varptransform, definierad av en rektangel och ett parallellogram, på detta`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Tillämpar en varptransform, definierad av en rektangel och ett parallellogram, på detta`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | Lägger till en ytterligare kontur till sökvägen. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | Lägger till en ytterligare disposition till`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | Ersätter detta`GraphicsPath` med kurvor som omsluter området som fylls när denna väg ritas av den angivna pennan. |

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


