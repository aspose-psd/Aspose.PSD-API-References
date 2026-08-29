---
title: "WarpSettings.RenderQuality"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "WarpSettings eigenschap. Haalt de waarde van warp-renderkwaliteit op of stelt deze in, tussen snelheid en kwaliteit"
type: docs
weight: 50
url: /nl/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/renderquality/
---
{{< psd/tize >}}
## WarpSettings.RenderQuality property

Haalt op of stelt de waarde van warp-renderkwaliteit in - tussen snelheid en kwaliteit

```csharp
public RenderQuality RenderQuality { get; set; }
```

## Voorbeelden

De volgende code toont de WarpSettings.RenderQuality-eigenschap om warp-deformatie te configureren.

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

RenderQuality[] qualityValues = { RenderQuality.Turbo, RenderQuality.Fast, RenderQuality.Normal, RenderQuality.Excellent };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // Het haalt WarpSettings op van de Smart Layer
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Het stelt de grootte van het warp-verwerkingsgebied in
        warpSettings.RenderQuality = qualityValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + qualityValues[i].ToString() + ".png";
        outputFiles.Add(outputFile);

        // Er zou hier geen fout moeten zijn
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Zie ook

* enum [RenderQuality](../../renderquality/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


