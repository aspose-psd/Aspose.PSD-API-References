---
title: "Klass FileCreateSource"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Sources.FileCreateSource-klass. Representerar en filkälla för skapande"
type: docs
weight: 6090
url: /sv/net/aspose.psd.sources/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource class

Representerar en filkälla för skapande.

```csharp
public sealed class FileCreateSource : FileSource
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | Initierar en ny instans av klassen `FileCreateSource`. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | Initierar en ny instans av klassen `FileCreateSource`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | Hämtar filsökvägen för skapande. |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | Hämtar ett värde som indikerar om filen blir temporär. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | Hämtar strömbehållaren. |

## Exempel

Detta exempel demonstrerar användningen av Font- och SolidBrush-klassen för att rita strängar på Image-ytan. Exemplet skapar en ny Image och ritar former med Figures och GraphicsPath.

```csharp
[C#]

//Skapar en instans av Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Skapar och initierar en instans av Graphics-klass
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Rensar Graphics-ytan
    graphics.Clear(Color.Wheat);

    //Skapar en instans av Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Skapa en instans av SolidBrush med röd färg
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Rita en sträng
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // skapa exportalternativ.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // spara alla ändringar
    image.Save("C:\\temp\\output.gif", options);
}
```

### Se även

* class [FileSource](../filesource/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)


