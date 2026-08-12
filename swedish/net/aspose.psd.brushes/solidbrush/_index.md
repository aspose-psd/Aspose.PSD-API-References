---
title: "Klass SolidBrush"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Brushes.SolidBrush-klass. Solid brush är avsedd för kontinuerlig ritning med en specifik färg. Denna klass kan inte ärvas"
type: docs
weight: 200
url: /sv/net/aspose.psd.brushes/solidbrush/
---
{{< psd/tize >}}
## SolidBrush class

Solid brush är avsedd för kontinuerlig ritning med en specifik färg. Denna klass kan inte ärvas.

```csharp
public sealed class SolidBrush : Brush
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SolidBrush](solidbrush/#constructor)() | Initierar en ny instans av `SolidBrush`‑klassen. |
| [SolidBrush](solidbrush/#constructor_1)(Color) | Initierar en ny instans av `SolidBrush`‑klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Color](../../aspose.psd.brushes/solidbrush/color/) { get; set; } | Hämtar eller anger penselfärgen. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Hämtar ett värde som indikerar om denna instans har frigjorts. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Hämtar eller anger penselns opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att penseln är helt synlig, värdet 1 betyder att penseln är helt ogenomskinlig. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Skapar en ny djupklon av den aktuella [`Brush`](../../aspose.psd/brush/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Frigör den aktuella instansen. |

## Exempel

Detta exempel använder Graphics-klass för att skapa primitiva former på bildytan. För att demonstrera operationen skapar exemplet en ny bild i PSD-format och ritar primitiva former på bildytan med Draw‑metoder som exponeras av Graphics‑klassen och exporterar den sedan till PSD-filformat.

```csharp
[C#]

//Skapa en instans av Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Skapa och initiera en instans av Graphics-klassen
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Rensa Graphics-ytan
    graphics.Clear(Color.Wheat);

    //Rita en båge genom att ange Pen‑objektet med svart färg, 
    //en rektangel som omger bågen, startvinkel och svepvinkel
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Rita en Bezier genom att ange Pen‑objektet med blå färg och koordinatpunkter.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Rita en kurva genom att ange Pen‑objektet med grön färg och en array av punkter
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Rita en ellips med Pen‑objektet och en omgivande rektangel
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Rita en linje 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Rita ett pajsegment
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Rita en polygon genom att ange Pen‑objektet med röd färg och en array av punkter
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Rita en rektangel
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Skapa ett SolidBrush‑objekt och ange dess olika egenskaper
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Rita en sträng med SolidBrush‑objektet och Font, vid en specifik punkt
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Skapa en instans av PngOptions och ange dess olika egenskaper
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // spara alla ändringar.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Se även

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


