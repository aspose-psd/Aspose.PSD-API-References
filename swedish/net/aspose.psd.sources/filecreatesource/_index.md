---
title: Class FileCreateSource
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Sources.FileCreateSource klass. Representerar en filkälla för skapande.
type: docs
weight: 5590
url: /sv/net/aspose.psd.sources/filecreatesource/
---
## FileCreateSource class

Representerar en filkälla för skapande.

```csharp
public sealed class FileCreateSource : FileSource
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | Initierar en ny instans av`FileCreateSource` class. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | Initierar en ny instans av`FileCreateSource` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | Hämtar filsökvägen att skapa. |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | Får ett värde som indikerar om filen kommer att vara temporär. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | Hämtar strömbehållaren. |

### Exempel

Det här exemplet visar användningen av klassen Font och SolidBrush för att rita strängar på bildytan. Exemplet skapar en ny bild och ritar former med hjälp av Figurer och GraphicsPath

```csharp
[C#]

//Skapar en instans av bild
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Skapar och initierar en instans av klassen Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Rensar grafikytan
    graphics.Clear(Color.Wheat);

    //Skapar en instans av Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Skapa en instans av SolidBrush med röd färg
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Rita ett snöre
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // skapa exportalternativ.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // spara alla ändringar
    image.Save("C:\\temp\\output.gif", options);
}
```

### Se även

* class [FileSource](../filesource/)
* namnutrymme [Aspose.PSD.Sources](../../aspose.psd.sources/)
* hopsättning [Aspose.PSD](../../)


