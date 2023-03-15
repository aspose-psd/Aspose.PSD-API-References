---
title: IGradientFillSettings.Scale
second_title: Aspose.PSD voor .NET API-referentie
description: IGradientFillSettings eigendom. Krijgt of stelt de schaal in.
type: docs
weight: 100
url: /nl/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
## IGradientFillSettings.Scale property

Krijgt of stelt de schaal in.

```csharp
public int Scale { get; set; }
```

### Eigendoms-waarde

De schaal.

### Voorbeelden

Het volgende voorbeeld laat zien hoe u de eigenschap Scale gebruikt om FillLayer met verloop te schalen.

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // een opvullaag krijgen
    FillLayer fillLayer = null;
    foreach (var layer in image.Layers)
    {
        fillLayer = layer as FillLayer;
        if (fillLayer != null)
        {
            break;
        }
    }

    var settings = fillLayer.FillSettings as IGradientFillSettings;

    // schaalwaarde bijwerken
    settings.Scale = 200;
    fillLayer.Update(); // Werkt pixelgegevens bij

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Zie ook

* interface [IGradientFillSettings](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../igradientfillsettings/)
* montage [Aspose.PSD](../../../)


