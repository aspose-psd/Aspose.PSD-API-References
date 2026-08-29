---
title: "WarpSettings.GridSize"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "WarpSettings eigenschap. Haalt de grootte van het warp-raster op of stelt deze in. Standaard is 1"
type: docs
weight: 30
url: /nl/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/gridsize/
---
{{< psd/tize >}}
## WarpSettings.GridSize property

Haalt op of stelt de grootte van het warp-rooster in. Standaard is 1.

```csharp
public Size GridSize { get; set; }
```

## Voorbeelden

De volgende code toont de ondersteuning van de WarpSettings.GridSize eigenschap.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Warp-instellingen ophalen
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Nieuwe grootte instellen
    // Voor Photoshop kan de waarde tussen 1 en 50 liggen en kun je een PSD-bestand niet correct opslaan.
    warpSettings.GridSize = new Size(100, 100);

    // Geldige waarde instellen
    warpSettings.GridSize = new Size(3, 3);

    // Voorbeeldbestand renderen met x3 raster
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Zie ook

* struct [Size](../../../aspose.psd/size/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


