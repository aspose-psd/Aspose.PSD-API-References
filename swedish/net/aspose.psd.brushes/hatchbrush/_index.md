---
title: Class HatchBrush
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Brushes.HatchBrush klass. Definierar en rektangulär pensel med en skräckstil en förgrundsfärg och en bakgrundsfärg. Denna klass kan inte ärvas.
type: docs
weight: 130
url: /sv/net/aspose.psd.brushes/hatchbrush/
---
## HatchBrush class

Definierar en rektangulär pensel med en skräckstil, en förgrundsfärg och en bakgrundsfärg. Denna klass kan inte ärvas.

```csharp
public sealed class HatchBrush : Brush
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [HatchBrush](hatchbrush/)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | Hämtar eller ställer in färgen på mellanrummen mellan strecklinjerna. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | Hämtar eller ställer in färgen på strecklinjer. |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | Hämtar eller ställer in den här borstens lucka. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Hämtar eller ställer in borstens opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att borsten är helt synlig, värdet 1 betyder att borsten är helt ogenomskinlig. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Skapar en ny djup klon av strömmen[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Tar bort den aktuella instansen. |

### Exempel

Det här exemplet visar skapande och användning av Pen-objekt. Exemplet skapar en ny bild och ritar rektanglar på bildytan.

```csharp
[C#]

//Skapa en instans av bild
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Skapa en instans av Graphics och initiera den med Image object
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Rensa grafikytan med vit färg
    graphics.Clear(Aspose.PSD.Color.White);

    //Skapa en instans av Pen med färgen Röd och bredd 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Skapa en instans av HatchBrush och ställ in dess egenskaper
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Skapa en instans av Pen
    //initiera det med HatchBrush-objekt och bredd
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Rita rektanglar genom att ange Pen-objekt
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Rita rektanglar genom att ange Pen-objekt
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Skapa exportalternativ och initiera dem.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // spara alla ändringar.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Se även

* class [Brush](../../aspose.psd/brush/)
* namnutrymme [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* hopsättning [Aspose.PSD](../../)


