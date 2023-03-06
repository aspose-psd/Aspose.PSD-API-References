---
title: IGradientFillSettings.Scale
second_title: Aspose.PSD för .NET API-referens
description: IGradientFillSettings fast egendom. Hämtar eller ställer in skalan.
type: docs
weight: 100
url: /sv/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
## IGradientFillSettings.Scale property

Hämtar eller ställer in skalan.

```csharp
public int Scale { get; set; }
```

### Fastighetsvärde

Skalan.

### Exempel

Följande exempel visar hur man använder Scale-egenskapen för att skala FillLayer med gradient.

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // att få ett fyllningslager
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

    // uppdatera skalvärdet
    settings.Scale = 200;
    fillLayer.Update(); // Uppdaterar pixeldata

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Se även

* interface [IGradientFillSettings](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../igradientfillsettings/)
* hopsättning [Aspose.PSD](../../../)


