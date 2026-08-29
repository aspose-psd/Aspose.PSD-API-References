---
title: "Klass HatchBrush"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Brushes.HatchBrush-klass. Definierar en rektangulär pensel med ett korsningsmönster, en förgrundsfärg och en bakgrundsfärg. Denna klass kan inte ärvas"
type: docs
weight: 130
url: /sv/net/aspose.psd.brushes/hatchbrush/
---
{{< psd/tize >}}
## HatchBrush class

Definierar en rektangulär pensel med ett korsningsmönster, en förgrundsfärg och en bakgrundsfärg. Denna klass kan inte ärvas.

```csharp
public sealed class HatchBrush : Brush
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [HatchBrush](hatchbrush/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | Hämtar eller anger färgen på utrymmena mellan korsningslinjerna. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Hämtar ett värde som indikerar om denna instans har frigjorts. |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | Hämtar eller anger färgen på korsningslinjerna. |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | Hämtar eller anger korsningsstilen för denna pensel. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Hämtar eller anger penselns opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att penseln är helt synlig, värdet 1 betyder att penseln är helt ogenomskinlig. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Skapar en ny djupklon av den aktuella [`Brush`](../../aspose.psd/brush/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Frigör den aktuella instansen. |

## Exempel

Detta exempel visar skapandet och användningen av Pen‑objekt. Exemplet skapar en ny Image och ritar rektanglar på Image‑ytan.

```csharp
[C#]

//Skapa en instans av Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Skapa en instans av Graphics och initiera den med ett Image‑objekt
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Rensa Graphics‑ytan med vit färg.
    graphics.Clear(Aspose.PSD.Color.White);

    //Skapa en instans av Pen med färgen röd och bredd 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Skapa en instans av HatchBrush och ange dess egenskaper
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Skapa en instans av Pen
    //initiera den med HatchBrush‑objektet och bredden
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Rita rektanglar genom att ange Pen‑objektet
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Rita rektanglar genom att ange Pen‑objektet
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Skapa exportalternativ och initiera dem.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // spara alla ändringar.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Se även

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


