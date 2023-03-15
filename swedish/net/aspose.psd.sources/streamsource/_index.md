---
title: Class StreamSource
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Sources.StreamSource klass. Representerar en strömkälla.
type: docs
weight: 5620
url: /sv/net/aspose.psd.sources/streamsource/
---
## StreamSource class

Representerar en strömkälla.

```csharp
public sealed class StreamSource : Source
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [StreamSource](streamsource/#constructor)(Stream) | Initierar en ny instans av`StreamSource` class. |
| [StreamSource](streamsource/#constructor_1)(Stream, bool) | Initierar en ny instans av`StreamSource` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [DisposeStream](../../aspose.psd.sources/streamsource/disposestream/) { get; } | Får ett värde som anger om strömmen ska kasseras när behållaren kasseras. |
| [Stream](../../aspose.psd.sources/streamsource/stream/) { get; } | Hämtar strömmen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/streamsource/getstreamcontainer/)() | Hämtar strömbehållaren. |

### Exempel

Det här exemplet använder klassen Graphics för att skapa primitiva former på bildytan. För att demonstrera funktionen skapar exemplet en ny bild i PSD-format och ritar primitiva former på bildytan med hjälp av Draw-metoder exponerade av Graphics-klassen och exporterar den sedan till PSD-filformat.

```csharp
[C#]

//Skapa en instans av bild 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Skapa och initiera en instans av klassen Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Rensa grafikytan
    graphics.Clear(Color.Wheat);

    //Rita en båge genom att ange Pen-objektet som har svart färg, 
    //a rektangel som omger bågen, startvinkeln och svepvinkeln
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Rita en Bezier genom att ange Pen-objektet som har blå färg och koordinatpunkter.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Rita en kurva genom att ange att Pen-objektet har grön färg och en array av punkter
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Rita en ellips med hjälp av Pen-objektet och en omgivande rektangel
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Dra ett streck 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Rita ett pajsegment
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Rita en polygon genom att ange att Pen-objektet har röd färg och en array av punkter
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Rita en rektangel
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Skapa ett SolidBrush-objekt och ställ in dess olika egenskaper
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Rita en sträng med SolidBrush-objektet och Font, vid en viss punkt
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Skapa en instans av PngOptions och ställ in dess olika egenskaper
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // spara alla ändringar.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Se även

* class [Source](../../aspose.psd/source/)
* namnutrymme [Aspose.PSD.Sources](../../aspose.psd.sources/)
* hopsättning [Aspose.PSD](../../)


