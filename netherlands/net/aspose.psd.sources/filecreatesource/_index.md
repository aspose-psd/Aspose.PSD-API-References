---
title: Class FileCreateSource
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.Sources.FileCreateSource klas. Vertegenwoordigt een bestandsbron voor creatie.
type: docs
weight: 5590
url: /nl/net/aspose.psd.sources/filecreatesource/
---
## FileCreateSource class

Vertegenwoordigt een bestandsbron voor creatie.

```csharp
public sealed class FileCreateSource : FileSource
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | Initialiseert een nieuw exemplaar van het`FileCreateSource` klasse. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | Initialiseert een nieuw exemplaar van het`FileCreateSource` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | Haalt het bestandspad op om te maken. |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | Krijgt een waarde die aangeeft of het bestand tijdelijk is. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | Haalt de streamcontainer op. |

### Voorbeelden

Dit voorbeeld demonstreert het gebruik van de klasse Font en SolidBrush om tekenreeksen op het afbeeldingsoppervlak te tekenen. In het voorbeeld wordt een nieuwe afbeelding gemaakt en vormen getekend met behulp van Figuren en GraphicsPath

```csharp
[C#]

//Maakt een exemplaar van Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Creëert en initialiseert een instantie van de klasse Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Wist grafisch oppervlak
    graphics.Clear(Color.Wheat);

    //Maakt een exemplaar van Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    // Maak een exemplaar van SolidBrush met rode kleur
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    // Teken een string
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // creëer exportopties.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // sla alle veranderingen op
    image.Save("C:\\temp\\output.gif", options);
}
```

### Zie ook

* class [FileSource](../filesource/)
* naamruimte [Aspose.PSD.Sources](../../aspose.psd.sources/)
* montage [Aspose.PSD](../../)


