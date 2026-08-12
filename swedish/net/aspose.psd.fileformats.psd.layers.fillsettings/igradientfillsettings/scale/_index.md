---
title: "IGradientFillSettings.Scale"
second_title: "Aspose.PSD för .NET API‑referens"
description: "IGradientFillSettings egenskap. Hämtar eller anger den normaliserade gradientskalan i procent"
type: docs
weight: 90
url: /sv/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
{{< psd/tize >}}
## IGradientFillSettings.Scale property

Hämtar eller anger den **normaliserade** gradientskalan (i procent).

```csharp
public int Scale { get; set; }
```

### Property Value

Skalan.

## Exempel

Följande exempel visar hur man använder Scale-egenskapen för att skala FillLayer med gradient.

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // hämtar ett fyllningslager
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
    fillLayer.Update(); // Updates pixels data

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Se även

* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


